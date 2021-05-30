---
title:  Избори 2021 - Рaзпределение на мандати без рисков вот
date: 2021-05-27 00:00:00
description: Симулация на окончателното разпределение на мандати след елиминиране на секциите с предполагаем рисков вот.      
featured_image: /assets/img/pages/Easily-accessible-linked-open-elections-data.png
author: Nikola Tulechki 
lang: bg
---

<!-- ![](/assets/img/pages/risky_mandates_2021.png) -->

<div class="chart-container">
  <canvas id="risky-mandates-chart"></canvas>
</div>

<script>
Chart.defaults.font.size = 16;

var ctx = document.getElementById('risky-mandates-chart').getContext('2d');

var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['БСП', 'ГЕРБ', 'ДБ', 'ДПС', 'ИСМВ', 'ИТН'],
        datasets: [{
            label: 'бр мандати',
            data: [3, 2, 1, -7, 0.2, 1],
            backgroundColor: [
                'rgba(204, 0, 0, 0.7)',
                'rgba(17, 85, 204, 0.7)',
                'rgba(153, 0, 255, 0.7)',
                'rgba(159, 197, 232, 0.7)',
                'rgba(235, 200, 21, 0.7)',
                'rgba(70, 189, 198, 0.7)'
            ],
            min: -100
        }]
    },
    options: {
        plugins: {
            legend: {
                display: false,
                position: 'bottom'
            },
            title: {
                display: true,
                align: 'start',
                text: 'рисков вот - разлика в мандати по партия'
            },
            tooltip: {
                callbacks: {
                    label: function(context) {
                        var label = context.dataset.label || '';
                        var value = context.dataset.data[context.dataIndex];

                        if (value === 0.2) {
                            value = 0;
                        }

                        return label + ': ' + value;
                    }
                }
            },
        },
        scales: {
            y: {
                title: {
                    display: true,
                    text: 'Мандати'
                },
                max: 4,
                min: -8
            }
        }
    }
});
</script>


### Методология 

**Как би изглеждало Народното Събрание ако на изборите на 4-ти април 2021 г. нямаше купен и контролиран вот?** 

Опитахме се да отговорим на този въпрос, използвайки следните данни и инструменти:
* Изследването на Антикорупционния Фонд (АКФ) за размера и влиянието на контролирания и купен вот на изборите на 04.04.2021г. (Достъпно [тук](https://acf.bg/bg/kontroliraniyat-i-kupen-vot-v-b/)).
* Отворените данни на ЦИК, които подържаме във вид на *Мрежа от Знание* (Описани [тук](https://www.ontotext.com/blog/5-star-linked-open-elections-data/))
* Мандатния калкулатор на BIRD, който прилага методиката на ЦИК на данни предоставени от потребителя. (Достъпен [тук](https://bird.bg/izbori2021/index.html))

#### Допускания
За да бъде възможен този анализ сме се основали върху няколко допускания, чиято вярност няма как да бъде гарантирана:
На първо място за "рискови секции" се смятат тези секции, които са прихванати от статистическия модел на АКФ с нисък праг, тоест най-песимистичнния сценарий, който е гарантиран по определние да свръхгенерира резултати.  
На второ място, симулацията предполага, че в т. нар. рискови секции **никой не гласува**. С други думи, те са изцяло извадени от системата. Наясно сме, че реалното електорално поведение е по-сложно и най-вероятно в тези секции все пак би имало вот.
Тези допускания правят анализа илюстративен, единствено за ситуация, в която допусканията са верни, като реалността би могла да е съществено различна.  

#### Генериране на входни данни

 Чрез тази SPARQL Заявка генерираме входни данни, директно в структурата очаквана от мандатния калкулатор, като изключваме секциите, в които методологията на АКФ открива аномалии, пораждащи съмнения за манипулация на вота. 

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
[Изпълняване на заявката](https://elections.ontotext.com/sparql?name=&infer=true&sameAs=true&query=BASE%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2F%3E%0APREFIX%20my%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fentity%2F%3E%0APREFIX%20myd%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fdirect%2F%3E%0APREFIX%20rdfs%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2F2000%2F01%2Frdf-schema%23%3E%0APREFIX%20myp%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Findirect%2F%3E%0APREFIX%20myps%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fstatement%2F%3E%0APREFIX%20mypq%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fqualifier%2F%3E%0APREFIX%20election%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Felection%2F%3E%0Aselect%20%3Fmir%20%3FpartyName%20(sum(%3Fvalid_votes)%20as%20%3Fsum_valid_votes)%20%0Awhere%20%7B%0A%20%20%20%20bind(election%3Api2021%20as%20%3Felection)%20%0A%20%20%20%20%3Fparty%20a%20my%3AElectionParty%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20rdfs%3Alabel%20%3FpartyName%20.%0A%20%20%20%20%3Fvoting%20myp%3Avote%20%3Fvote%20%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20myd%3Amain_election%20%3Felection%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20myd%3Aelection%2Fmyd%3Ajurisdiction%2Fmyd%3Anumber%20%3Fmir%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20myd%3Asection%20%3Fsec%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20.%0A%20%20%20%20%3Fvote%20myps%3Avote%2Fmyd%3Aparty%20%3Fparty%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20mypq%3Avalid_votes_recieved%20%3Fvalid_votes%20%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20.%0A%20%20%20%20filter%20not%20exists%20%7B%0A%20%20%20%20%20%20%20%20%3Fsec%20myd%3Ameta_section%20%3Fms%20.%0A%20%20%20%20%20%20%20%20%3Fms%20myd%3AisVeryRisky2021%20%5B%5D%20.%0A%20%20%20%20%7D%0A%7D%20group%20by%20%3Fmir%20%3FpartyName%20order%20by%20%3Fmir%20%3FpartyName&execute)

Използваме `csvformat` за да преформатирме таблицата с правилните сепаратори:
```bash
csvformat -D=";" -K 1  pi2021_no_risky.csv  > pi2017_no_risky.ok.csv
```

### Резултат и анализ

Изключвайки рисковите секции изпозлваме калкулатора на BIRD за да симулираме изборния процес с близо 310000 "рискови" избиратели по-малко. Това отговаря на най-песимистичната хипотеза в изследването на АКФ. 

Поради спецификата на методологията на разпределение на мандатите, която е [игра с нулев резултат](https://en.wikipedia.org/wiki/Zero-sum_game), единственият губещ се оказва партия ДПС, която при по-честен вот губи седем мандата. Тези седем мандата се преразпределят между четири други партии както следва: 

|Партия  | Разлика	| Реални мандати | Мандати без рискови секции |
|--------|----------|----------------|----------------------------|
| БСП	 | +3	    |   43           |	          46              |
| ГЕРБ	 | +2       |   75	         |            77              |
| ДБ     | +1       | 	27           |            28              |
| ДПС	 | **-7**   |	30	         |            23              |
| ИСМВ   |	0       |	14           |            14              |
| ИТН    |	+1	    |   51	         |            52              |
{: .table .table-striped .table-responsive}
