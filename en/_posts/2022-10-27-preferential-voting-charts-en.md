---
title:  Parliamentary elections October 2022 - preferential vote by party
date: 2022-10-27 00:00:00
description: Graphs of the preferential vote in the parliamentary elections.
featured_image: /assets/img/elections.png
author: Nikola Tulechki
lang: en
---

These infographics show the distribution of the preferential vote for each party at the election on 02.10.2022.

Each row represents the candidate list in a constituency.
Each circle is a separate candidate, and their order is the same as the order of the candidates on the list.
The larger the circle, the more preferences the candidate has received.
The circles are not proportional from party to party.

The graphs are interactive. 
Hovering over an individual circle shows the candidate's preferences section by section, 
and their relation to the total vote for the party in the section.
 
# Coalition GERB - SDS

<div class="chart-container">
  <div id="vis_2022_gerb"></div>
</div>

## PP We Continue the Change

<div class="chart-container">
  <div id="vis_2022_pp"></div>
</div>

## PP Movement for Rights and Freedoms

<div class="chart-container">
  <div id="vis_2022_dps"></div>
</div>

## PP Revival

<div class="chart-container">
  <div id="vis_2022_vuz"></div>
</div>

## PP Bulgarian Socialist Party for Bulgaria

<div class="chart-container">
  <div id="vis_2022_bsp"></div>
</div>

## Coalition Democratic Bulgaria

<div class="chart-container">
  <div id="vis_2022_db"></div>
</div>

## PP Bulgarian Rise 

<div class="chart-container">
  <div id="vis_2022_bv"></div>
</div>

The graphs and the underlying data can be used under the terms of the open license [CC-BY](https://creativecommons.org/licenses/by/2.0/){:target="_blank"}.

<script type="text/javascript">
var vlSpec = {
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "",
  "data": {
    "url": ""
  },
  "width": 900,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color": "#2c92e6"
  },
  "encoding": {
    "x": {
      "field": "cand_number",
      "type": "ordinal",
      "axis": {"grid": false, "title": "Candidate number"}
    },
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": "MMC"}},
    "size": {
      "field": "pref_votes",
      "type": "quantitative",
      "scale": {"rangeMax": 5000}
    },
    "tooltip": [
      {"field": "mir_norm", "type": "ordinal", "title": "MMC"},
      {"field": "cand_number", "type": "ordinal", "title": "Number"},
      {"field": "name", "type": "nominal", "title": "Candidate"},
      {"field": "pref_votes", "type": "quantitative", "title": "Preferences"}
    ],
    "href": {"field": "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
var urlbase = "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/"

function init() {
    var containers = document.getElementsByClassName('chart-container');
 
    vlSpec_2022_gerb=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_gerb.title = "Coalition GERB - SDS - Preferential vote distribution - 02.10.2022" ;
    vlSpec_2022_gerb.data.url = urlbase+"gerb_2022.csv" ;
    vlSpec_2022_gerb.mark.color = "#2c92e6";
    vegaEmbed('#vis_2022_gerb', vlSpec_2022_gerb);

    vlSpec_2022_pp=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_pp.title = "PP We Continue the Change - Preferential vote distribution - 02.10.2022" ;
    vlSpec_2022_pp.data.url = urlbase+"pp_2022.csv" ;
    vlSpec_2022_pp.mark.color = "#1e0985";
    vegaEmbed('#vis_2022_pp', vlSpec_2022_pp);
    
    vlSpec_2022_dps=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_dps.title = "PP Movement for Rights and Freedoms - Preferential vote distribution - 02.10.20222" ;
    vlSpec_2022_dps.data.url = urlbase+"dps_2022.csv" ;
    vlSpec_2022_dps.mark.color = "#0d518898";  
     vegaEmbed('#vis_2022_dps', vlSpec_2022_dps);

    vlSpec_2022_vuz=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_vuz.title = "PP Revival - Preferential vote distribution - 02.10.2022" ;
    vlSpec_2022_vuz.data.url = urlbase+"vuz_2022.csv" ;
    vlSpec_2022_vuz.mark.color = "#7b5804";  
    vegaEmbed('#vis_2022_vuz', vlSpec_2022_vuz);

    vlSpec_2022_bsp=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_bsp.title = "PP Bulgarian Socialist Party - Preferential vote distribution - 02.10.2022" ;
    vlSpec_2022_bsp.data.url = urlbase+"bsp_2022.csv" ;
    vlSpec_2022_bsp.mark.color = "#BB3214";  
    vegaEmbed('#vis_2022_bsp', vlSpec_2022_bsp);

    vlSpec_2022_db=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_db.title = "PP Democratic Bulgaria - Preferential vote distribution - 02.10.2022" ;
    vlSpec_2022_db.data.url = urlbase+"db_2022.csv" ;
    vlSpec_2022_db.mark.color = "#DD06F4";  
    vegaEmbed('#vis_2022_db', vlSpec_2022_db);
    
    vlSpec_2022_bv=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_bv.title = "PP Bulgarian Rise - Preferential vote distribution - 02.10.2022" ;
    vlSpec_2022_bv.data.url = urlbase+"bv_2022.csv" ;
    vlSpec_2022_bv.mark.color = "#770C03";  
    vegaEmbed('#vis_2022_bv', vlSpec_2022_bv);
}

init();
window.addEventListener('resize', init);
</script>
