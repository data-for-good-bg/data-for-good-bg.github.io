---
title:  Парламентарни избори - преференциален вот по партия 
date: 2022-03-19 00:00:00
description: Графики на преференциалния вот на парламентарните избори.     
featured_image: /assets/img/elections.png
author: Nikola Tulechki 
lang: bg
---

# Ноември 2021

## КП Продължаваме Промяната

<div class="chart-container">
  <div id="vis_2021_11_pp"></div>
</div>

# КП ГЕРБ - СДС

<div class="chart-container">
  <div id="vis_2021_11_gerb"></div>
</div>



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
      "axis": {"grid": false, "title": "Кандидат номер"}
    },
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": "МИР"}},
    "size": {
      "field": "pref_votes",
      "type": "quantitative",
      "scale": {"rangeMax": 5000}
    },
    "tooltip": [
      {"field": "mir_norm", "type": "ordinal", "title": "МИР"},
      {"field": "cand_number", "type": "ordinal", "title": "Номер"},
      {"field": "name", "type": "nominal", "title": "Кандидат"},
      {"field": "pref_votes", "type": "quantitative", "title": "Преференции"}
    ],
    "href": {"field": "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
var urlbase = "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/"

function init() {
    var containers = document.getElementsByClassName('chart-container');
 
    vlSpec_2021_11_pp=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2021_11_pp.title = "ПП ПП  - Разпределение на преференициалния вот - 14.11.2021" ;
    vlSpec_2021_11_pp.data.url = urlbase+"pp_2021_11.csv" ;
    vlSpec_2021_11_pp.mark.color = "#1e0985";  
    
    vegaEmbed('#vis_2021_11_pp', vlSpec_2021_11_pp);
    
    vlSpec_2021_11_gerb=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2021_11_gerb.title = "ГЕРБ  - Разпределение на преференициалния вот - 14.11.2021" ;
    vlSpec_2021_11_gerb.data.url = urlbase+"gerb_2021_11.csv" ;
    vlSpec_2021_11_gerb.mark.color = "#2c92e6";  
    
    vegaEmbed('#vis_2021_11_gerb', vlSpec_2021_11_gerb);
}

init();
window.addEventListener('resize', init);
</script>
