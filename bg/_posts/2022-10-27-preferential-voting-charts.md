---
title:  Парламентарни избори Октомври 2022 - префернциален вот по партия 
date: 2022-10-27 00:00:00
description: Графики на префернициалния вот на парламентарните избори.     
featured_image: /assets/img/elections.png
author: Nikola Tulechki 
lang: bg
---

Тези инфографики показват разпределенито на преференциалния вот за всяка партия на избора на 02.10.2022.

Всеки ред представлява кандидатската листа в даден избирателен район.
Всеки кръг е отделен кандидат, и редът им е същия като реда на кандидатите в листата.
Колкото по-голям е кръгът, толкова повече преференции е получил съответния кандидат.
Кръговете не са пропорционални от партия на партия.

Графиките са интерактивни. 
Щракване с мишката върху отделен кръг показва преференциите на кандидата секция по секция, 
както и тяхното отношение към общия вот за партията в секцията.
 
# КП ГЕРБ - СДС

<div class="chart-container">
  <div id="vis_2022_gerb"></div>
</div>

## КП Продължаваме Промяната

<div class="chart-container">
  <div id="vis_2022_pp"></div>
</div>

## ПП ДПС

<div class="chart-container">
  <div id="vis_2022_dps"></div>
</div>

## ПП Възраждане

<div class="chart-container">
  <div id="vis_2022_vuz"></div>
</div>

## KП БСП За България

<div class="chart-container">
  <div id="vis_2022_bsp"></div>
</div>

## KП Демократична България

<div class="chart-container">
  <div id="vis_2022_db"></div>
</div>

## ПП Български Възход

<div class="chart-container">
  <div id="vis_2022_bv"></div>
</div>

Графиките и производните им данни могат да се използват съгласно условията на отворения лиценз [CC-BY](https://creativecommons.org/licenses/by/2.0/).

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
 
    vlSpec_2022_gerb=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_gerb.title = "КП ГЕРБ СДС  - Разпределение на преференициалния вот - 02.10.2022" ;
    vlSpec_2022_gerb.data.url = urlbase+"gerb_2022.csv" ;
    vlSpec_2022_gerb.mark.color = "#2c92e6";
    vegaEmbed('#vis_2022_gerb', vlSpec_2022_gerb);

    vlSpec_2022_pp=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_pp.title = "ПП ПП  - Разпределение на преференициалния вот - 02.10.2022" ;
    vlSpec_2022_pp.data.url = urlbase+"pp_2022.csv" ;
    vlSpec_2022_pp.mark.color = "#1e0985";
    vegaEmbed('#vis_2022_pp', vlSpec_2022_pp);
    
    vlSpec_2022_dps=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_dps.title = "ДПС  - Разпределение на преференициалния вот - 02.10.2022" ;
    vlSpec_2022_dps.data.url = urlbase+"dps_2022.csv" ;
    vlSpec_2022_dps.mark.color = "#0d518898";  
     vegaEmbed('#vis_2022_dps', vlSpec_2022_dps);

    vlSpec_2022_vuz=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_vuz.title = "Възраждане  - Разпределение на преференициалния вот - 02.10.2022" ;
    vlSpec_2022_vuz.data.url = urlbase+"vuz_2022.csv" ;
    vlSpec_2022_vuz.mark.color = "#7b5804";  
    vegaEmbed('#vis_2022_vuz', vlSpec_2022_vuz);

    vlSpec_2022_bsp=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_bsp.title = "БСП  - Разпределение на преференициалния вот - 02.10.2022" ;
    vlSpec_2022_bsp.data.url = urlbase+"bsp_2022.csv" ;
    vlSpec_2022_bsp.mark.color = "#BB3214";  
    vegaEmbed('#vis_2022_bsp', vlSpec_2022_bsp);

    vlSpec_2022_db=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_db.title = "ДБ  - Разпределение на преференициалния вот - 02.10.2022" ;
    vlSpec_2022_db.data.url = urlbase+"db_2022.csv" ;
    vlSpec_2022_db.mark.color = "#DD06F4";  
    vegaEmbed('#vis_2022_db', vlSpec_2022_db);
    
    vlSpec_2022_bv=JSON.parse(JSON.stringify(vlSpec));
    vlSpec_2022_bv.title = "ДБ  - Разпределение на преференициалния вот - 02.10.2022" ;
    vlSpec_2022_bv.data.url = urlbase+"bv_2022.csv" ;
    vlSpec_2022_bv.mark.color = "#770C03";  
    vegaEmbed('#vis_2022_bv', vlSpec_2022_bv);
}

init();
window.addEventListener('resize', init);
</script>
