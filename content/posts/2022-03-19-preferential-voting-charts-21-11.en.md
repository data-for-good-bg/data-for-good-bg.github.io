---
title: Parliamentary elections - preferential vote by party
date: 2022-03-19 00:00:00
description: Graphs of the preferential vote in the parliamentary elections.
featured_image: /img/posts/elections.png
authors: [ "nikola-tulechki" ]
categories: [ "democracy" ]
tags: [ "преференциален вот" ]
lang: en
draft: false
type: "blog"
---

## November 2021

### Coalition We Continue the Change

<div class="chart-container">
  <div id="vis_2021_11_pp"></div>
</div>

### Coalition GERB - SDS

<div class="chart-container">
  <div id="vis_2021_11_gerb"></div>
</div>



<script type="text/javascript">
var vlSpec = {
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "",
  "background": "#fff7d3",
  "data": {
    "url": ""
  },
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
      {"field": "name", "type": "nominal", "title": "Кандидат"},
      {"field": "pref_votes", "type": "quantitative", "title": "Preferences"}
    ],
    "href": {"field": "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
var urlbase = "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/"

function init() {
    var containers = document.getElementsByClassName('chart-container');
 
    vlSpec_2021_11_pp=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2021_11_pp.title = "PP We Continue the Change - Preferential vote distribution - 14.11.2021" ;
    vlSpec_2021_11_pp.data.url = urlbase+"pp_2021_11.csv" ;
    vlSpec_2021_11_pp.mark.color = "#1e0985";  
    vlSpec_2021_11_pp.width = containers[1].offsetWidth - 180;
    
    vegaEmbed('#vis_2021_11_pp', vlSpec_2021_11_pp);
    
    vlSpec_2021_11_gerb=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2021_11_gerb.title = "GERB - Preferential vote distribution - 14.11.2021";
    vlSpec_2021_11_gerb.data.url = urlbase+"gerb_2021_11.csv";
    vlSpec_2021_11_gerb.mark.color = "#2c92e6";
    vlSpec_2021_11_gerb.width = containers[0].offsetWidth - 180;
    
    vegaEmbed('#vis_2021_11_gerb', vlSpec_2021_11_gerb);
}

init();
window.addEventListener('resize', init);
</script>
