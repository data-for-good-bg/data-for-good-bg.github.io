---
title: Парламентарни избори Април 2023 - преференциален вот по партия
date: 2023-04-16 00:00:00
description: Графики на преференциалния вот на парламентарните избори.
featured_image: /img/posts/elections.png
authors: [ "nikola-tulechki" ]
categories: [ "democracy" ]
tags: [ "преференциален вот" ]
lang: bg
draft: false
type: "blog"
---

Тези инфографики показват разпределението на преференциалния вот за всяка партия на избора на 02.04.2023.

Всеки ред представлява кандидатската листа в даден избирателен район.
Всеки кръг е отделен кандидат, и редът им е същия като реда на кандидатите в листата.
Колкото по-голям е кръгът, толкова повече преференции е получил съответния кандидат.
Кръговете не са пропорционални от партия на партия.

Графиките са интерактивни. 
Щракване с мишката върху отделен кръг показва преференциите на кандидата секция по секция, 
както и тяхното отношение към общия вот за партията в секцията.
 
# КП ГЕРБ - СДС

<div class="chart-container">
  <div id="vis_gerb"></div>
</div>

## КП Продължаваме Промяната / Демократична България

<div class="chart-container">
  <div id="vis_ppdb"></div>
</div>

## ПП Възраждане

<div class="chart-container">
  <div id="vis_vuz"></div>
</div>

## ПП ДПС

<div class="chart-container">
  <div id="vis_dps"></div>
</div>


## KП БСП За България

<div class="chart-container">
  <div id="vis_bsp"></div>
</div>

## ПП Има Такъв Народ 

<div class="chart-container">
  <div id="vis_itn"></div>
</div>


Графиките и производните им данни могат да се използват съгласно условията на отворения лиценз [CC-BY](https://creativecommons.org/licenses/by/2.0/).

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
 
    vlSpec_gerb=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_gerb.title = "КП ГЕРБ СДС  - Разпределение на преференициалния вот - 02.04.2023" ;
    vlSpec_gerb.data.url = urlbase+"gerb_2023.csv" ;
    vlSpec_gerb.mark.color = "#00a8bd";
    vlSpec_gerb.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_gerb', vlSpec_gerb);

    vlSpec_ppdb=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_ppdb.title = "КП ПП ДБ  - Разпределение на преференициалния вот - 02.04.2023" ;
    vlSpec_ppdb.data.url = urlbase+"ppdb_2023.csv" ;
    vlSpec_ppdb.mark.color = "#125db0";
    vlSpec_ppdb.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_ppdb', vlSpec_ppdb);
    
    vlSpec_dps=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_dps.title = "ДПС  - Разпределение на преференициалния вот - 02.04.2023" ;
    vlSpec_dps.data.url = urlbase+"dps_2023.csv" ;
    vlSpec_dps.mark.color = "#0d518898";
    vlSpec_dps.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_dps', vlSpec_dps);

    vlSpec_vuz=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_vuz.title = "Възраждане  - Разпределение на преференициалния вот - 02.04.2023" ;
    vlSpec_vuz.data.url = urlbase+"vuz_2023.csv" ;
    vlSpec_vuz.mark.color = "#00923d";
    vlSpec_vuz.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_vuz', vlSpec_vuz);

    vlSpec_bsp=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_bsp.title = "БСП  - Разпределение на преференициалния вот - 02.04.2023" ;
    vlSpec_bsp.data.url = urlbase+"bsp_2023.csv" ;
    vlSpec_bsp.mark.color = "#ef5926";
    vlSpec_bsp.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_bsp', vlSpec_bsp);
 
    vlSpec_itn=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_itn.title = "ИТН  - Разпределение на преференициалния вот - 02.04.2023" ;
    vlSpec_itn.data.url = urlbase+"itn_2023.csv" ;
    vlSpec_itn.mark.color = "#ffad01";
    vlSpec_itn.width = containers[0].offsetWidth - 220;
    vegaEmbed('#vis_itn', vlSpec_itn);
}

init();
window.addEventListener('resize', init);
</script>
