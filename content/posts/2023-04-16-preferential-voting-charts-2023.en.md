---
title: Parliamentary elections April 2023 - preferential vote by party
date: 2023-04-16 00:00:00
description: Graphs of the preferential vote in the parliamentary elections.
featured_image: /img/posts/elections.png
authors: [ "nikola-tulechki" ]
categories: [ "democracy" ]
tags: []
lang: en
draft: false
type: "blog"
---

These infographics show the distribution of the preferential vote for each party in the election on 02.04.2023.

Each row represents the candidate list in a constituency.
Each round is a separate candidate, and their order is the same as the order of the candidates on the list.
The larger the circle, the more preferences the candidate has received.
The circles are not proportional from party to party.

The graphics are interactive. 
Clicking the mouse on an individual circle shows the candidate's preferences section by section, 
and their relation to the total vote for the party in the section.
 
# Coalition GERB - SDS

<div class="chart-container">
  <div id="vis_gerb"></div>
</div>

## Coalition We Continue the Change / Democratic Bulgaria

<div class="chart-container">
  <div id="vis_ppdb"></div>
</div>

## PP Revival

<div class="chart-container">
  <div id="vis_vuz"></div>
</div>

## PP Movement for Rights and Freedoms

<div class="chart-container">
  <div id="vis_dps"></div>
</div>


## Coalition Bulgarian Socialist Party for Bulgaria

<div class="chart-container">
  <div id="vis_bsp"></div>
</div>

## PP There Is Such A People

<div class="chart-container">
  <div id="vis_itn"></div>
</div>


The graphs and the underlying data may be used under the terms of the open licence [CC-BY](https://creativecommons.org/licenses/by/2.0/).

<script type="text/javascript">
var vlSpec = {
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "",
  "background": "#fff7d3",
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
 
    vlSpec_gerb=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_gerb.title = "Coalition GERB - SDS  - Preferential vote distribution - 02.04.2023" ;
    vlSpec_gerb.data.url = urlbase+"gerb_2023.csv" ;
    vlSpec_gerb.mark.color = "#2c92e6";
    vlSpec_gerb.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_gerb', vlSpec_gerb);

    vlSpec_ppdb=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_ppdb.title = "Coalition We Continue the Change / Democratic Bulgaria  - Preferential vote distribution - 02.04.2023" ;
    vlSpec_ppdb.data.url = urlbase+"ppdb_2023.csv" ;
    vlSpec_ppdb.mark.color = "#1e0985";
    vlSpec_ppdb.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_ppdb', vlSpec_ppdb);
    
    vlSpec_dps=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_dps.title = "Movement for Rights and Freedoms  - Preferential vote distribution - 02.04.2023" ;
    vlSpec_dps.data.url = urlbase+"dps_2023.csv" ;
    vlSpec_dps.mark.color = "#0d518898";
    vlSpec_dps.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_dps', vlSpec_dps);

    vlSpec_vuz=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_vuz.title = "Revival  - Preferential vote distribution - 02.04.2023" ;
    vlSpec_vuz.data.url = urlbase+"vuz_2023.csv" ;
    vlSpec_vuz.mark.color = "#7b5804";
    vlSpec_vuz.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_vuz', vlSpec_vuz);

    vlSpec_bsp=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_bsp.title = "Bulgarian Socialist Party  - Preferential vote distribution - 02.04.2023" ;
    vlSpec_bsp.data.url = urlbase+"bsp_2023.csv" ;
    vlSpec_bsp.mark.color = "#BB3214";
    vlSpec_bsp.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_bsp', vlSpec_bsp);
 
    vlSpec_itn=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_itn.title = "There Is Such A People  - Preferential vote distribution - 02.04.2023" ;
    vlSpec_itn.data.url = urlbase+"itn_2023.csv" ;
    vlSpec_itn.mark.color = "#D8E013";  
    vlSpec_itn.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_itn', vlSpec_itn);
}

init();
window.addEventListener('resize', init);
</script>
