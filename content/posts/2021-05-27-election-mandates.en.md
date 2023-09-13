---
title: Election 2021 -Distribution of mandates without voting risk
date: 2021-05-27 00:00:00
description: Simulation of the final distribution of mandates after elimination of sections with presumed risky votes.
featured_image: /img/posts/Easily-accessible-linked-open-elections-data.png
authors: [ "nikola-tulechki" ]
categories: [ "democracy" ]
tags: []
lang: en
draft: false
type: "blog"
---

```json:vega-light
{
    "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
    "description": "рисков вот - разлика в мандати по партия",
    "background": "#fff7d3",
    "data": {
      "values": [
        { "party": "BSP", "mandates": 3, "color": "rgba(239, 89, 38, 0.7)"},
        { "party": "GERB", "mandates": 2, "color": "rgba(0, 168, 189, 0.7)"},
        { "party": "DB", "mandates": 1, "color": "rgba(127, 62, 166, 0.7)"},
        { "party": "DPS", "mandates": -7, "color": "rgba(0, 146, 61, 0.7)"},
        { "party": "ISMV", "mandates": 0.2, "color": "rgba(255, 173, 1, 0.7)"},
        { "party": "ITN", "mandates": 1, "color": "rgba(104, 52, 2, 0.7)"}
      ]
    },
    "width": 600,
    "height": 250,
    "mark": "bar",
    "title": {
      "text": {"signal": "'risky votes - difference in mandates by party'"},
      "anchor": "start",
      "frame": "group",
      "titleFontSize": 15
    },
    "encoding": {
        "x": {"field": "party", "type": "nominal", "title": "", "axis": { "labelAngle": 0 } },
        "y": {"field": "mandates", "type": "quantitative", "title": "Mandates", "axis": { "titleFontWeight": "normal", "titleFontSize": 14 }, "scale": { "domainMax": 4, "domainMin": -8 } },
        "color": {"field": "color", "type": "nominal", "scale": null}
    }
}
```

### Methodology

**What would the National Assembly look like if there was no bought and controlled vote in the elections on April 4, 2021?** 

We tried to answer this question using the following data and tools:
* The study of the Anti-Corruption Fund (ACF) on the size and impact of the controlled and bought vote in the elections on 04.04.2021. (Available [here](https://acf.bg/bg/kontroliraniyat-i-kupen-vot-v-b/)).
* CEC's open data, which we maintain as a *Knowledge Network* (Described [here](https://www.ontotext.com/blog/5-star-linked-open-elections-data/))
* BIRD's mandate calculator, which applies the CEC methodology to user-supplied data. (Available [here](https://bird.bg/izbori2021/index.html))

#### Assumptions
To make this analysis possible, we have made several assumptions whose correctness cannot be guaranteed:
In the first place, "risky sections" are those sections that are captured by the ACF statistical model with a low threshold, i.e. the most pessimistic scenario that is guaranteed by definition to overgenerate results.  
Secondly, the simulation assumes that in the so called risk polling stations **nobody votes**. In other words, they are completely removed from the system. We are aware that the actual electoral behaviour is more complex, and most likely there would still be a vote in these polling stations.
These assumptions make the analysis illustrative only for a situation where the assumptions are true, and the reality could be substantially different.  

#### Generation of input data

Using this SPARQL Query, we generate input data directly in the structure expected by the mandate calculator, excluding sections where the ACF methodology detects anomalies raising suspicions of vote manipulation. 

```sparql
BASE <https://elections.ontotext.com/resource/>
PREFIX my: <https://elections.ontotext.com/resource/entity/>
PREFIX myd: <https://elections.ontotext.com/resource/prop/direct/>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX myp: <https://elections.ontotext.com/resource/prop/indirect/>
PREFIX myps: <https://elections.ontotext.com/resource/prop/statement/>
PREFIX mypq: <https://elections.ontotext.com/resource/prop/qualifier/>
PREFIX election: <https://elections.ontotext.com/resource/election/>
select ?mir ?partyName (sum(?valid_votes) as ?sum_valid_votes) 
where {
    bind(election:pi2021 as ?election) 
    ?party a my:ElectionParty ;
           rdfs:label ?partyName .
    ?voting myp:vote ?vote  ;
            myd:main_election ?election ;
            myd:election/myd:jurisdiction/myd:number ?mir ;
            myd:section ?sec ;
                                         .
    ?vote myps:vote/myd:party ?party;
                   mypq:valid_votes_recieved ?valid_votes ;
                   .
    filter not exists {
        ?sec myd:meta_section ?ms .
        ?ms myd:isVeryRisky2021 [] .
    }
} group by ?mir ?partyName order by ?mir ?partyName
``` 
[Request execution](https://elections.ontotext.com/sparql?name=&infer=true&sameAs=true&query=BASE%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2F%3E%0APREFIX%20my%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fentity%2F%3E%0APREFIX%20myd%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fdirect%2F%3E%0APREFIX%20rdfs%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2F2000%2F01%2Frdf-schema%23%3E%0APREFIX%20myp%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Findirect%2F%3E%0APREFIX%20myps%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fstatement%2F%3E%0APREFIX%20mypq%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fqualifier%2F%3E%0APREFIX%20election%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Felection%2F%3E%0Aselect%20%3Fmir%20%3FpartyName%20(sum(%3Fvalid_votes)%20as%20%3Fsum_valid_votes)%20%0Awhere%20%7B%0A%20%20%20%20bind(election%3Api2021%20as%20%3Felection)%20%0A%20%20%20%20%3Fparty%20a%20my%3AElectionParty%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20rdfs%3Alabel%20%3FpartyName%20.%0A%20%20%20%20%3Fvoting%20myp%3Avote%20%3Fvote%20%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20myd%3Amain_election%20%3Felection%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20myd%3Aelection%2Fmyd%3Ajurisdiction%2Fmyd%3Anumber%20%3Fmir%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20myd%3Asection%20%3Fsec%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20.%0A%20%20%20%20%3Fvote%20myps%3Avote%2Fmyd%3Aparty%20%3Fparty%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20mypq%3Avalid_votes_recieved%20%3Fvalid_votes%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20.%0A%20%20%20%20filter%20not%20exists%20%7B%0A%20%20%20%20%20%20%20%20%3Fsec%20myd%3Ameta_section%20%3Fms%20.%0A%20%20%20%20%20%20%20%20%3Fms%20myd%3AisVeryRisky2021%20%5B%5D%20.%0A%20%20%20%20%7D%0A%7D%20group%20by%20%3Fmir%20%3FpartyName%20order%20by%20%3Fmir%20%3FpartyName&execute)

We use `csvformat` to reformat the table with the correct separators:
```bash
csvformat -D=";" -K 1  pi2021_no_risky.csv  > pi2017_no_risky.ok.csv
```

### Results and analysis

Excluding the risky polling stations, we use the BIRD calculator to simulate the electoral process with nearly 310,000 less "risky" voters. This corresponds to the most pessimistic hypothesis in the ACF study. 

Due to the specifics of the methodology of the distribution of mandates, which is a [zero-sum game](https://en.wikipedia.org/wiki/Zero-sum_game), the only loser turns out to be the MRF party, which in a more honest vote loses seven seats. These seven mandates are redistributed among four other parties as follows: 

|Party  | Difference	| Real Mandates | Mandates without risky poll sections |
|--------|----------|----------------|----------------------------|
| BSP	 | +3	    |   43           |	          46              |
| GERB	 | +2       |   75	         |            77              |
| DB     | +1       | 	27           |            28              |
| MRF	 | **-7**   |	30	         |            23              |
| SUBWC   |	0       |	14           |            14              |
| TSP    |	+1	    |   51	         |            52              |

BSP - Bulgarian Socialist Party
GERB - 
DB - Democratic Bulgaria
MRF - Movement for Rights and Freedoms
SUBWC - Stand Up.BG! We are coming!
TSP - There Is Such A People
