---
title:  Втора матура по СТЕМ предмети - Анализ на данни от матури за периода 2019-2022 г.
date: 2023-08-12 00:00:00
description: Анализ на представянето на матурите по СТЕМ предмети по области в България за периода 2019-2022 г.      
featured_image: /img/posts/color-graph.png
authors: ["ognyana-hristova","izabella-taskova"]
categories: ["education"]
lang: bg
draft: false
type: "blog"
---

###  Средношколците вече полагат по средно две матури, като отливът от СТЕМ може да е притеснителен

От 1990-те насам науката, технологиите, инженерството и математиката (англ. STEM (science, technology, engineering and mathematics)[^1],"СТЕМ") се наложиха като основна тема в образованието. Обществата с успешно образование по СТЕМ често бързо увеличават благосъстоянието си, а с това и разцвета си в всички други сфери - от намалена корупция до увеличени инвестиции в здраве и култура. За съжаление, общите тенденции в България са познати - по-малко деца и по-ниски оценки. По-интересно е какво следва - обещания за подобрение се крият в учителските заплати, които вече са над средните за страната, но и в конкретни училища, които се справят въпреки трудностите. Автори на статията са ["Данни за добро"](https://data-for-good.bg/) и ["Образование без раници"](https://obr.education/).

### 6 хиляди ученици по-малко значи по-малък потенциал за страната

Матурата (ДЗИ[^2]) по български език и литература (БЕЛ[^3]) е задължителна и затова подсказва общия брой завършващи средно образование в България. В последните години те намаляват - от явилите се 49 156 през 2019 г. до само 43 053 през 2022, това е спад от 12%. Макар спадът да е във всички области, той е по-голям в Ямбол (-32%) и Ловеч (-29%) и по-малък в областите с най-големите български градове.

<div class="chart-container">
  <div id="vis1"></div>
</div>

<script type="text/javascript">
var vlSpec1 = {

  "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json",
  "config": {
    "view": {
      "continuousHeight": 300,
      "continuousWidth": 400,
      "stroke": "transparent"
    }
  },
  "data": {
    "name": "data-ded6310303e98fe74c9fbb31a707bed5"
  },
  "datasets": {
    "data-ded6310303e98fe74c9fbb31a707bed5": [
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2425.0,
        "tot_pup_other": 413.0,
        "tot_pup_second": 1224.0,
        "tot_pup_stem": 811.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2571.0,
        "tot_pup_other": 1111.0,
        "tot_pup_second": 1683.0,
        "tot_pup_stem": 572.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2322.0,
        "tot_pup_other": 912.0,
        "tot_pup_second": 1417.0,
        "tot_pup_stem": 505.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2423.0,
        "tot_pup_other": 1138.0,
        "tot_pup_second": 1604.0,
        "tot_pup_stem": 466.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2300.0,
        "tot_pup_other": 1965.0,
        "tot_pup_second": 2212.0,
        "tot_pup_stem": 247.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2927.0,
        "tot_pup_other": 914.0,
        "tot_pup_second": 2100.0,
        "tot_pup_stem": 1186.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 3057.0,
        "tot_pup_other": 1404.0,
        "tot_pup_second": 2449.0,
        "tot_pup_stem": 1045.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2811.0,
        "tot_pup_other": 1177.0,
        "tot_pup_second": 2059.0,
        "tot_pup_stem": 882.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2853.0,
        "tot_pup_other": 1511.0,
        "tot_pup_second": 2277.0,
        "tot_pup_stem": 766.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2824.0,
        "tot_pup_other": 2351.0,
        "tot_pup_second": 2705.0,
        "tot_pup_stem": 354.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3355.0,
        "tot_pup_other": 1156.0,
        "tot_pup_second": 2112.0,
        "tot_pup_stem": 956.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3325.0,
        "tot_pup_other": 1632.0,
        "tot_pup_second": 2313.0,
        "tot_pup_stem": 681.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3210.0,
        "tot_pup_other": 1508.0,
        "tot_pup_second": 2163.0,
        "tot_pup_stem": 655.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3121.0,
        "tot_pup_other": 1660.0,
        "tot_pup_second": 2286.0,
        "tot_pup_stem": 626.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3101.0,
        "tot_pup_other": 2632.0,
        "tot_pup_second": 3017.0,
        "tot_pup_stem": 385.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1604.0,
        "tot_pup_other": 394.0,
        "tot_pup_second": 822.0,
        "tot_pup_stem": 428.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1598.0,
        "tot_pup_other": 688.0,
        "tot_pup_second": 1057.0,
        "tot_pup_stem": 369.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1449.0,
        "tot_pup_other": 569.0,
        "tot_pup_second": 941.0,
        "tot_pup_stem": 372.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1475.0,
        "tot_pup_other": 718.0,
        "tot_pup_second": 1001.0,
        "tot_pup_stem": 283.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1388.0,
        "tot_pup_other": 1267.0,
        "tot_pup_second": 1357.0,
        "tot_pup_stem": 90.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 576.0,
        "tot_pup_other": 168.0,
        "tot_pup_second": 356.0,
        "tot_pup_stem": 188.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 556.0,
        "tot_pup_other": 286.0,
        "tot_pup_second": 471.0,
        "tot_pup_stem": 185.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 555.0,
        "tot_pup_other": 250.0,
        "tot_pup_second": 433.0,
        "tot_pup_stem": 183.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 500.0,
        "tot_pup_other": 225.0,
        "tot_pup_second": 386.0,
        "tot_pup_stem": 161.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 447.0,
        "tot_pup_other": 382.0,
        "tot_pup_second": 440.0,
        "tot_pup_stem": 58.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1234.0,
        "tot_pup_other": 186.0,
        "tot_pup_second": 543.0,
        "tot_pup_stem": 357.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1304.0,
        "tot_pup_other": 477.0,
        "tot_pup_second": 714.0,
        "tot_pup_stem": 237.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1126.0,
        "tot_pup_other": 390.0,
        "tot_pup_second": 591.0,
        "tot_pup_stem": 201.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1182.0,
        "tot_pup_other": 608.0,
        "tot_pup_second": 779.0,
        "tot_pup_stem": 171.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1093.0,
        "tot_pup_other": 959.0,
        "tot_pup_second": 1017.0,
        "tot_pup_stem": 58.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 706.0,
        "tot_pup_other": 184.0,
        "tot_pup_second": 429.0,
        "tot_pup_stem": 245.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 704.0,
        "tot_pup_other": 301.0,
        "tot_pup_second": 536.0,
        "tot_pup_stem": 235.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 696.0,
        "tot_pup_other": 248.0,
        "tot_pup_second": 497.0,
        "tot_pup_stem": 249.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 706.0,
        "tot_pup_other": 402.0,
        "tot_pup_second": 590.0,
        "tot_pup_stem": 188.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 641.0,
        "tot_pup_other": 565.0,
        "tot_pup_second": 634.0,
        "tot_pup_stem": 69.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 1001.0,
        "tot_pup_other": 280.0,
        "tot_pup_second": 473.0,
        "tot_pup_stem": 193.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 952.0,
        "tot_pup_other": 464.0,
        "tot_pup_second": 566.0,
        "tot_pup_stem": 102.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 865.0,
        "tot_pup_other": 416.0,
        "tot_pup_second": 523.0,
        "tot_pup_stem": 107.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 915.0,
        "tot_pup_other": 459.0,
        "tot_pup_second": 560.0,
        "tot_pup_stem": 101.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 809.0,
        "tot_pup_other": 741.0,
        "tot_pup_second": 798.0,
        "tot_pup_stem": 57.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1078.0,
        "tot_pup_other": 188.0,
        "tot_pup_second": 658.0,
        "tot_pup_stem": 470.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1239.0,
        "tot_pup_other": 446.0,
        "tot_pup_second": 877.0,
        "tot_pup_stem": 431.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1108.0,
        "tot_pup_other": 375.0,
        "tot_pup_second": 755.0,
        "tot_pup_stem": 380.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1089.0,
        "tot_pup_other": 358.0,
        "tot_pup_second": 748.0,
        "tot_pup_stem": 390.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1017.0,
        "tot_pup_other": 714.0,
        "tot_pup_second": 959.0,
        "tot_pup_stem": 245.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 758.0,
        "tot_pup_other": 154.0,
        "tot_pup_second": 477.0,
        "tot_pup_stem": 323.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 821.0,
        "tot_pup_other": 311.0,
        "tot_pup_second": 636.0,
        "tot_pup_stem": 325.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 718.0,
        "tot_pup_other": 252.0,
        "tot_pup_second": 546.0,
        "tot_pup_stem": 294.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 711.0,
        "tot_pup_other": 346.0,
        "tot_pup_second": 625.0,
        "tot_pup_stem": 279.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 666.0,
        "tot_pup_other": 570.0,
        "tot_pup_second": 636.0,
        "tot_pup_stem": 66.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 978.0,
        "tot_pup_other": 282.0,
        "tot_pup_second": 497.0,
        "tot_pup_stem": 215.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 1025.0,
        "tot_pup_other": 619.0,
        "tot_pup_second": 806.0,
        "tot_pup_stem": 187.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 905.0,
        "tot_pup_other": 492.0,
        "tot_pup_second": 697.0,
        "tot_pup_stem": 205.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 868.0,
        "tot_pup_other": 502.0,
        "tot_pup_second": 679.0,
        "tot_pup_stem": 177.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 730.0,
        "tot_pup_other": 656.0,
        "tot_pup_second": 716.0,
        "tot_pup_stem": 60.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 924.0,
        "tot_pup_other": 194.0,
        "tot_pup_second": 533.0,
        "tot_pup_stem": 339.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 862.0,
        "tot_pup_other": 370.0,
        "tot_pup_second": 621.0,
        "tot_pup_stem": 251.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 793.0,
        "tot_pup_other": 324.0,
        "tot_pup_second": 500.0,
        "tot_pup_stem": 176.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 796.0,
        "tot_pup_other": 339.0,
        "tot_pup_second": 532.0,
        "tot_pup_stem": 193.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 638.0,
        "tot_pup_other": 579.0,
        "tot_pup_second": 627.0,
        "tot_pup_stem": 48.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1814.0,
        "tot_pup_other": 341.0,
        "tot_pup_second": 986.0,
        "tot_pup_stem": 645.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1680.0,
        "tot_pup_other": 660.0,
        "tot_pup_second": 1172.0,
        "tot_pup_stem": 512.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1534.0,
        "tot_pup_other": 497.0,
        "tot_pup_second": 958.0,
        "tot_pup_stem": 461.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1677.0,
        "tot_pup_other": 601.0,
        "tot_pup_second": 989.0,
        "tot_pup_stem": 388.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1498.0,
        "tot_pup_other": 1310.0,
        "tot_pup_second": 1407.0,
        "tot_pup_stem": 97.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 841.0,
        "tot_pup_other": 199.0,
        "tot_pup_second": 322.0,
        "tot_pup_stem": 123.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 751.0,
        "tot_pup_other": 360.0,
        "tot_pup_second": 462.0,
        "tot_pup_stem": 102.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 724.0,
        "tot_pup_other": 263.0,
        "tot_pup_second": 365.0,
        "tot_pup_stem": 102.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 679.0,
        "tot_pup_other": 519.0,
        "tot_pup_second": 596.0,
        "tot_pup_stem": 77.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 668.0,
        "tot_pup_other": 629.0,
        "tot_pup_second": 646.0,
        "tot_pup_stem": 17.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1841.0,
        "tot_pup_other": 374.0,
        "tot_pup_second": 1090.0,
        "tot_pup_stem": 716.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1684.0,
        "tot_pup_other": 621.0,
        "tot_pup_second": 1120.0,
        "tot_pup_stem": 499.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1608.0,
        "tot_pup_other": 564.0,
        "tot_pup_second": 1023.0,
        "tot_pup_stem": 459.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1581.0,
        "tot_pup_other": 601.0,
        "tot_pup_second": 917.0,
        "tot_pup_stem": 316.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1473.0,
        "tot_pup_other": 1174.0,
        "tot_pup_second": 1386.0,
        "tot_pup_stem": 212.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4413.0,
        "tot_pup_other": 1338.0,
        "tot_pup_second": 2862.0,
        "tot_pup_stem": 1524.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4514.0,
        "tot_pup_other": 2199.0,
        "tot_pup_second": 3253.0,
        "tot_pup_stem": 1054.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4206.0,
        "tot_pup_other": 1740.0,
        "tot_pup_second": 2935.0,
        "tot_pup_stem": 1195.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4241.0,
        "tot_pup_other": 2274.0,
        "tot_pup_second": 3307.0,
        "tot_pup_stem": 1033.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 3847.0,
        "tot_pup_other": 3437.0,
        "tot_pup_second": 3724.0,
        "tot_pup_stem": 287.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 862.0,
        "tot_pup_other": 131.0,
        "tot_pup_second": 613.0,
        "tot_pup_stem": 482.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 845.0,
        "tot_pup_other": 265.0,
        "tot_pup_second": 667.0,
        "tot_pup_stem": 402.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 748.0,
        "tot_pup_other": 203.0,
        "tot_pup_second": 526.0,
        "tot_pup_stem": 323.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 795.0,
        "tot_pup_other": 230.0,
        "tot_pup_second": 516.0,
        "tot_pup_stem": 286.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 718.0,
        "tot_pup_other": 602.0,
        "tot_pup_second": 703.0,
        "tot_pup_stem": 101.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1502.0,
        "tot_pup_other": 439.0,
        "tot_pup_second": 900.0,
        "tot_pup_stem": 461.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1453.0,
        "tot_pup_other": 704.0,
        "tot_pup_second": 1082.0,
        "tot_pup_stem": 378.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1332.0,
        "tot_pup_other": 585.0,
        "tot_pup_second": 988.0,
        "tot_pup_stem": 403.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1395.0,
        "tot_pup_other": 724.0,
        "tot_pup_second": 1073.0,
        "tot_pup_stem": 349.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1254.0,
        "tot_pup_other": 1110.0,
        "tot_pup_second": 1225.0,
        "tot_pup_stem": 115.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 831.0,
        "tot_pup_other": 136.0,
        "tot_pup_second": 446.0,
        "tot_pup_stem": 310.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 748.0,
        "tot_pup_other": 292.0,
        "tot_pup_second": 493.0,
        "tot_pup_stem": 201.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 688.0,
        "tot_pup_other": 217.0,
        "tot_pup_second": 394.0,
        "tot_pup_stem": 177.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 684.0,
        "tot_pup_other": 258.0,
        "tot_pup_second": 377.0,
        "tot_pup_stem": 119.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 597.0,
        "tot_pup_other": 523.0,
        "tot_pup_second": 586.0,
        "tot_pup_stem": 63.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1098.0,
        "tot_pup_other": 261.0,
        "tot_pup_second": 560.0,
        "tot_pup_stem": 299.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1041.0,
        "tot_pup_other": 416.0,
        "tot_pup_second": 645.0,
        "tot_pup_stem": 229.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1007.0,
        "tot_pup_other": 374.0,
        "tot_pup_second": 582.0,
        "tot_pup_stem": 208.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1002.0,
        "tot_pup_other": 567.0,
        "tot_pup_second": 778.0,
        "tot_pup_stem": 211.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 935.0,
        "tot_pup_other": 868.0,
        "tot_pup_second": 910.0,
        "tot_pup_stem": 42.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 762.0,
        "tot_pup_other": 102.0,
        "tot_pup_second": 450.0,
        "tot_pup_stem": 348.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 837.0,
        "tot_pup_other": 302.0,
        "tot_pup_second": 656.0,
        "tot_pup_stem": 354.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 694.0,
        "tot_pup_other": 237.0,
        "tot_pup_second": 495.0,
        "tot_pup_stem": 258.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 798.0,
        "tot_pup_other": 365.0,
        "tot_pup_second": 640.0,
        "tot_pup_stem": 275.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 688.0,
        "tot_pup_other": 559.0,
        "tot_pup_second": 673.0,
        "tot_pup_stem": 114.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8419.0,
        "tot_pup_other": 3998.0,
        "tot_pup_second": 6130.0,
        "tot_pup_stem": 2132.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8942.0,
        "tot_pup_other": 5457.0,
        "tot_pup_second": 7242.0,
        "tot_pup_stem": 1785.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8548.0,
        "tot_pup_other": 4668.0,
        "tot_pup_second": 6495.0,
        "tot_pup_stem": 1827.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8805.0,
        "tot_pup_other": 5667.0,
        "tot_pup_second": 7323.0,
        "tot_pup_stem": 1656.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8686.0,
        "tot_pup_other": 7933.0,
        "tot_pup_second": 8581.0,
        "tot_pup_stem": 648.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2260.0,
        "tot_pup_other": 605.0,
        "tot_pup_second": 1429.0,
        "tot_pup_stem": 824.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2331.0,
        "tot_pup_other": 962.0,
        "tot_pup_second": 1555.0,
        "tot_pup_stem": 593.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2120.0,
        "tot_pup_other": 899.0,
        "tot_pup_second": 1423.0,
        "tot_pup_stem": 524.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2048.0,
        "tot_pup_other": 993.0,
        "tot_pup_second": 1432.0,
        "tot_pup_stem": 439.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1805.0,
        "tot_pup_other": 1582.0,
        "tot_pup_second": 1749.0,
        "tot_pup_stem": 167.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 729.0,
        "tot_pup_other": 74.0,
        "tot_pup_second": 411.0,
        "tot_pup_stem": 337.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 723.0,
        "tot_pup_other": 191.0,
        "tot_pup_second": 458.0,
        "tot_pup_stem": 267.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 666.0,
        "tot_pup_other": 156.0,
        "tot_pup_second": 349.0,
        "tot_pup_stem": 193.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 629.0,
        "tot_pup_other": 184.0,
        "tot_pup_second": 392.0,
        "tot_pup_stem": 208.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 594.0,
        "tot_pup_other": 495.0,
        "tot_pup_second": 582.0,
        "tot_pup_stem": 87.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1551.0,
        "tot_pup_other": 426.0,
        "tot_pup_second": 1048.0,
        "tot_pup_stem": 622.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1569.0,
        "tot_pup_other": 659.0,
        "tot_pup_second": 1140.0,
        "tot_pup_stem": 481.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1421.0,
        "tot_pup_other": 540.0,
        "tot_pup_second": 941.0,
        "tot_pup_stem": 401.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1311.0,
        "tot_pup_other": 580.0,
        "tot_pup_second": 913.0,
        "tot_pup_stem": 333.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1366.0,
        "tot_pup_other": 1126.0,
        "tot_pup_second": 1287.0,
        "tot_pup_stem": 161.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1151.0,
        "tot_pup_other": 239.0,
        "tot_pup_second": 866.0,
        "tot_pup_stem": 627.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1292.0,
        "tot_pup_other": 369.0,
        "tot_pup_second": 1039.0,
        "tot_pup_stem": 670.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1185.0,
        "tot_pup_other": 294.0,
        "tot_pup_second": 878.0,
        "tot_pup_stem": 584.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1172.0,
        "tot_pup_other": 522.0,
        "tot_pup_second": 1066.0,
        "tot_pup_stem": 544.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1073.0,
        "tot_pup_other": 818.0,
        "tot_pup_second": 1017.0,
        "tot_pup_stem": 199.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 848.0,
        "tot_pup_other": 152.0,
        "tot_pup_second": 305.0,
        "tot_pup_stem": 153.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 900.0,
        "tot_pup_other": 306.0,
        "tot_pup_second": 402.0,
        "tot_pup_stem": 96.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 717.0,
        "tot_pup_other": 222.0,
        "tot_pup_second": 310.0,
        "tot_pup_stem": 88.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 712.0,
        "tot_pup_other": 284.0,
        "tot_pup_second": 357.0,
        "tot_pup_stem": 73.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 616.0,
        "tot_pup_other": 518.0,
        "tot_pup_second": 602.0,
        "tot_pup_stem": 84.0,
        "year": 2022
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1665.0,
        "tot_pup_other": 286.0,
        "tot_pup_second": 761.0,
        "tot_pup_stem": 475.0,
        "year": 2017
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1611.0,
        "tot_pup_other": 667.0,
        "tot_pup_second": 980.0,
        "tot_pup_stem": 313.0,
        "year": 2019
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1538.0,
        "tot_pup_other": 528.0,
        "tot_pup_second": 826.0,
        "tot_pup_stem": 298.0,
        "year": 2020
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1402.0,
        "tot_pup_other": 737.0,
        "tot_pup_second": 950.0,
        "tot_pup_stem": 213.0,
        "year": 2021
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1408.0,
        "tot_pup_other": 1236.0,
        "tot_pup_second": 1308.0,
        "tot_pup_stem": 72.0,
        "year": 2022
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 221.0,
        "tot_pup_other": 34.0,
        "tot_pup_second": 123.0,
        "tot_pup_stem": 89.0,
        "year": 2017
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 221.0,
        "tot_pup_other": 90.0,
        "tot_pup_second": 135.0,
        "tot_pup_stem": 45.0,
        "year": 2019
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 184.0,
        "tot_pup_other": 66.0,
        "tot_pup_second": 100.0,
        "tot_pup_stem": 34.0,
        "year": 2020
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 191.0,
        "tot_pup_other": 81.0,
        "tot_pup_second": 105.0,
        "tot_pup_stem": 24.0,
        "year": 2021
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 173.0,
        "tot_pup_other": 143.0,
        "tot_pup_second": 168.0,
        "tot_pup_stem": 25.0,
        "year": 2022
      }
    ]
  },
  "encoding": {
    "color": {
      "field": "year",
      "legend": {
        "title": "\u0413\u043e\u0434\u0438\u043d\u0430"
      },
      "scale": {
        "domain": [
          2019,
          2020,
          2021,
          2022
        ],
        "range": [
          "#FFAD01",
          "#EF5926",
          "#00923D",
          "#00A8BD"
        ]
      },
      "type": "nominal"
    },
    "tooltip": [
      {
        "field": "province",
        "type": "nominal"
      },
      {
        "field": "year",
        "type": "quantitative"
      },
      {
        "field": "tot_pup_bel",
        "type": "quantitative"
      }
    ],
    "x": {
      "axis": {
        "grid": false
      },
      "field": "tot_pup_bel",
      "title": "\u0411\u0440\u043e\u0439 \u0443\u0447\u0435\u043d\u0438\u0446\u0438 \u0441 \u043c\u0430\u0442\u0443\u0440\u0430 \u043f\u043e \u0411\u0415\u041b",
      "type": "quantitative"
    },
    "y": {
      "axis": {
        "grid": true,
        "labelLimit": 450
      },
      "field": "province",
      "sort": "x",
      "title": "",
      "type": "nominal"
    }
  },
  "height": {
    "step": 20
  },
  "mark": "point"
};    

function init() {
    var containers = document.getElementsByClassName('chart-container');
    if (containers.length) {
        vlSpec1.width = containers[0].offsetWidth - 80;
    }

    vegaEmbed('#vis1', vlSpec1);
}

init();
window.addEventListener('resize', init);
</script>

### Повече ученици вземат втора матура

Броят на явилите се на втора матура скача с цели 23%: от 33 798 през 2021 до 41 672 през 2022. С други думи, общо взетите втори матури вече са почти колкото "първите" по БЕЛ. Големи увеличения се наблюдават в областите София - град (+1339 явили се или +18%) и Ямбол (+50% или +200 явили се). Възможни причини за увеличенията са промени за учениците от професионалните и езиковите гимназии. От 2022 година дванадесетокласниците с професионално образование полагат задължителен изпит за професионална квалификация, който обединява двата предишни изпита по теория и по практика на професията и специалността. Също от 2022, завършващите езикови гимназии се явяват на втора матура по един от профилиращите предмети от втория гимназиален етап.[^4]

<div class="chart-container">
  <div id="vis2"></div>
</div>

<script type="text/javascript">
var vlSpec2 = {

  "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json",
  "config": {
    "view": {
      "continuousHeight": 300,
      "continuousWidth": 400,
      "stroke": "transparent"
    }
  },
  "data": {
    "name": "data-ded6310303e98fe74c9fbb31a707bed5"
  },
  "datasets": {
    "data-ded6310303e98fe74c9fbb31a707bed5": [
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2425.0,
        "tot_pup_other": 413.0,
        "tot_pup_second": 1224.0,
        "tot_pup_stem": 811.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2571.0,
        "tot_pup_other": 1111.0,
        "tot_pup_second": 1683.0,
        "tot_pup_stem": 572.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2322.0,
        "tot_pup_other": 912.0,
        "tot_pup_second": 1417.0,
        "tot_pup_stem": 505.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2423.0,
        "tot_pup_other": 1138.0,
        "tot_pup_second": 1604.0,
        "tot_pup_stem": 466.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2300.0,
        "tot_pup_other": 1965.0,
        "tot_pup_second": 2212.0,
        "tot_pup_stem": 247.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2927.0,
        "tot_pup_other": 914.0,
        "tot_pup_second": 2100.0,
        "tot_pup_stem": 1186.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 3057.0,
        "tot_pup_other": 1404.0,
        "tot_pup_second": 2449.0,
        "tot_pup_stem": 1045.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2811.0,
        "tot_pup_other": 1177.0,
        "tot_pup_second": 2059.0,
        "tot_pup_stem": 882.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2853.0,
        "tot_pup_other": 1511.0,
        "tot_pup_second": 2277.0,
        "tot_pup_stem": 766.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2824.0,
        "tot_pup_other": 2351.0,
        "tot_pup_second": 2705.0,
        "tot_pup_stem": 354.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3355.0,
        "tot_pup_other": 1156.0,
        "tot_pup_second": 2112.0,
        "tot_pup_stem": 956.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3325.0,
        "tot_pup_other": 1632.0,
        "tot_pup_second": 2313.0,
        "tot_pup_stem": 681.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3210.0,
        "tot_pup_other": 1508.0,
        "tot_pup_second": 2163.0,
        "tot_pup_stem": 655.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3121.0,
        "tot_pup_other": 1660.0,
        "tot_pup_second": 2286.0,
        "tot_pup_stem": 626.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3101.0,
        "tot_pup_other": 2632.0,
        "tot_pup_second": 3017.0,
        "tot_pup_stem": 385.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1604.0,
        "tot_pup_other": 394.0,
        "tot_pup_second": 822.0,
        "tot_pup_stem": 428.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1598.0,
        "tot_pup_other": 688.0,
        "tot_pup_second": 1057.0,
        "tot_pup_stem": 369.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1449.0,
        "tot_pup_other": 569.0,
        "tot_pup_second": 941.0,
        "tot_pup_stem": 372.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1475.0,
        "tot_pup_other": 718.0,
        "tot_pup_second": 1001.0,
        "tot_pup_stem": 283.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1388.0,
        "tot_pup_other": 1267.0,
        "tot_pup_second": 1357.0,
        "tot_pup_stem": 90.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 576.0,
        "tot_pup_other": 168.0,
        "tot_pup_second": 356.0,
        "tot_pup_stem": 188.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 556.0,
        "tot_pup_other": 286.0,
        "tot_pup_second": 471.0,
        "tot_pup_stem": 185.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 555.0,
        "tot_pup_other": 250.0,
        "tot_pup_second": 433.0,
        "tot_pup_stem": 183.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 500.0,
        "tot_pup_other": 225.0,
        "tot_pup_second": 386.0,
        "tot_pup_stem": 161.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 447.0,
        "tot_pup_other": 382.0,
        "tot_pup_second": 440.0,
        "tot_pup_stem": 58.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1234.0,
        "tot_pup_other": 186.0,
        "tot_pup_second": 543.0,
        "tot_pup_stem": 357.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1304.0,
        "tot_pup_other": 477.0,
        "tot_pup_second": 714.0,
        "tot_pup_stem": 237.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1126.0,
        "tot_pup_other": 390.0,
        "tot_pup_second": 591.0,
        "tot_pup_stem": 201.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1182.0,
        "tot_pup_other": 608.0,
        "tot_pup_second": 779.0,
        "tot_pup_stem": 171.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1093.0,
        "tot_pup_other": 959.0,
        "tot_pup_second": 1017.0,
        "tot_pup_stem": 58.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 706.0,
        "tot_pup_other": 184.0,
        "tot_pup_second": 429.0,
        "tot_pup_stem": 245.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 704.0,
        "tot_pup_other": 301.0,
        "tot_pup_second": 536.0,
        "tot_pup_stem": 235.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 696.0,
        "tot_pup_other": 248.0,
        "tot_pup_second": 497.0,
        "tot_pup_stem": 249.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 706.0,
        "tot_pup_other": 402.0,
        "tot_pup_second": 590.0,
        "tot_pup_stem": 188.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 641.0,
        "tot_pup_other": 565.0,
        "tot_pup_second": 634.0,
        "tot_pup_stem": 69.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 1001.0,
        "tot_pup_other": 280.0,
        "tot_pup_second": 473.0,
        "tot_pup_stem": 193.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 952.0,
        "tot_pup_other": 464.0,
        "tot_pup_second": 566.0,
        "tot_pup_stem": 102.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 865.0,
        "tot_pup_other": 416.0,
        "tot_pup_second": 523.0,
        "tot_pup_stem": 107.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 915.0,
        "tot_pup_other": 459.0,
        "tot_pup_second": 560.0,
        "tot_pup_stem": 101.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 809.0,
        "tot_pup_other": 741.0,
        "tot_pup_second": 798.0,
        "tot_pup_stem": 57.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1078.0,
        "tot_pup_other": 188.0,
        "tot_pup_second": 658.0,
        "tot_pup_stem": 470.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1239.0,
        "tot_pup_other": 446.0,
        "tot_pup_second": 877.0,
        "tot_pup_stem": 431.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1108.0,
        "tot_pup_other": 375.0,
        "tot_pup_second": 755.0,
        "tot_pup_stem": 380.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1089.0,
        "tot_pup_other": 358.0,
        "tot_pup_second": 748.0,
        "tot_pup_stem": 390.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1017.0,
        "tot_pup_other": 714.0,
        "tot_pup_second": 959.0,
        "tot_pup_stem": 245.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 758.0,
        "tot_pup_other": 154.0,
        "tot_pup_second": 477.0,
        "tot_pup_stem": 323.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 821.0,
        "tot_pup_other": 311.0,
        "tot_pup_second": 636.0,
        "tot_pup_stem": 325.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 718.0,
        "tot_pup_other": 252.0,
        "tot_pup_second": 546.0,
        "tot_pup_stem": 294.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 711.0,
        "tot_pup_other": 346.0,
        "tot_pup_second": 625.0,
        "tot_pup_stem": 279.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 666.0,
        "tot_pup_other": 570.0,
        "tot_pup_second": 636.0,
        "tot_pup_stem": 66.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 978.0,
        "tot_pup_other": 282.0,
        "tot_pup_second": 497.0,
        "tot_pup_stem": 215.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 1025.0,
        "tot_pup_other": 619.0,
        "tot_pup_second": 806.0,
        "tot_pup_stem": 187.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 905.0,
        "tot_pup_other": 492.0,
        "tot_pup_second": 697.0,
        "tot_pup_stem": 205.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 868.0,
        "tot_pup_other": 502.0,
        "tot_pup_second": 679.0,
        "tot_pup_stem": 177.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 730.0,
        "tot_pup_other": 656.0,
        "tot_pup_second": 716.0,
        "tot_pup_stem": 60.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 924.0,
        "tot_pup_other": 194.0,
        "tot_pup_second": 533.0,
        "tot_pup_stem": 339.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 862.0,
        "tot_pup_other": 370.0,
        "tot_pup_second": 621.0,
        "tot_pup_stem": 251.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 793.0,
        "tot_pup_other": 324.0,
        "tot_pup_second": 500.0,
        "tot_pup_stem": 176.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 796.0,
        "tot_pup_other": 339.0,
        "tot_pup_second": 532.0,
        "tot_pup_stem": 193.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 638.0,
        "tot_pup_other": 579.0,
        "tot_pup_second": 627.0,
        "tot_pup_stem": 48.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1814.0,
        "tot_pup_other": 341.0,
        "tot_pup_second": 986.0,
        "tot_pup_stem": 645.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1680.0,
        "tot_pup_other": 660.0,
        "tot_pup_second": 1172.0,
        "tot_pup_stem": 512.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1534.0,
        "tot_pup_other": 497.0,
        "tot_pup_second": 958.0,
        "tot_pup_stem": 461.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1677.0,
        "tot_pup_other": 601.0,
        "tot_pup_second": 989.0,
        "tot_pup_stem": 388.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1498.0,
        "tot_pup_other": 1310.0,
        "tot_pup_second": 1407.0,
        "tot_pup_stem": 97.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 841.0,
        "tot_pup_other": 199.0,
        "tot_pup_second": 322.0,
        "tot_pup_stem": 123.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 751.0,
        "tot_pup_other": 360.0,
        "tot_pup_second": 462.0,
        "tot_pup_stem": 102.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 724.0,
        "tot_pup_other": 263.0,
        "tot_pup_second": 365.0,
        "tot_pup_stem": 102.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 679.0,
        "tot_pup_other": 519.0,
        "tot_pup_second": 596.0,
        "tot_pup_stem": 77.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 668.0,
        "tot_pup_other": 629.0,
        "tot_pup_second": 646.0,
        "tot_pup_stem": 17.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1841.0,
        "tot_pup_other": 374.0,
        "tot_pup_second": 1090.0,
        "tot_pup_stem": 716.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1684.0,
        "tot_pup_other": 621.0,
        "tot_pup_second": 1120.0,
        "tot_pup_stem": 499.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1608.0,
        "tot_pup_other": 564.0,
        "tot_pup_second": 1023.0,
        "tot_pup_stem": 459.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1581.0,
        "tot_pup_other": 601.0,
        "tot_pup_second": 917.0,
        "tot_pup_stem": 316.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1473.0,
        "tot_pup_other": 1174.0,
        "tot_pup_second": 1386.0,
        "tot_pup_stem": 212.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4413.0,
        "tot_pup_other": 1338.0,
        "tot_pup_second": 2862.0,
        "tot_pup_stem": 1524.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4514.0,
        "tot_pup_other": 2199.0,
        "tot_pup_second": 3253.0,
        "tot_pup_stem": 1054.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4206.0,
        "tot_pup_other": 1740.0,
        "tot_pup_second": 2935.0,
        "tot_pup_stem": 1195.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4241.0,
        "tot_pup_other": 2274.0,
        "tot_pup_second": 3307.0,
        "tot_pup_stem": 1033.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 3847.0,
        "tot_pup_other": 3437.0,
        "tot_pup_second": 3724.0,
        "tot_pup_stem": 287.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 862.0,
        "tot_pup_other": 131.0,
        "tot_pup_second": 613.0,
        "tot_pup_stem": 482.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 845.0,
        "tot_pup_other": 265.0,
        "tot_pup_second": 667.0,
        "tot_pup_stem": 402.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 748.0,
        "tot_pup_other": 203.0,
        "tot_pup_second": 526.0,
        "tot_pup_stem": 323.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 795.0,
        "tot_pup_other": 230.0,
        "tot_pup_second": 516.0,
        "tot_pup_stem": 286.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 718.0,
        "tot_pup_other": 602.0,
        "tot_pup_second": 703.0,
        "tot_pup_stem": 101.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1502.0,
        "tot_pup_other": 439.0,
        "tot_pup_second": 900.0,
        "tot_pup_stem": 461.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1453.0,
        "tot_pup_other": 704.0,
        "tot_pup_second": 1082.0,
        "tot_pup_stem": 378.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1332.0,
        "tot_pup_other": 585.0,
        "tot_pup_second": 988.0,
        "tot_pup_stem": 403.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1395.0,
        "tot_pup_other": 724.0,
        "tot_pup_second": 1073.0,
        "tot_pup_stem": 349.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1254.0,
        "tot_pup_other": 1110.0,
        "tot_pup_second": 1225.0,
        "tot_pup_stem": 115.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 831.0,
        "tot_pup_other": 136.0,
        "tot_pup_second": 446.0,
        "tot_pup_stem": 310.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 748.0,
        "tot_pup_other": 292.0,
        "tot_pup_second": 493.0,
        "tot_pup_stem": 201.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 688.0,
        "tot_pup_other": 217.0,
        "tot_pup_second": 394.0,
        "tot_pup_stem": 177.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 684.0,
        "tot_pup_other": 258.0,
        "tot_pup_second": 377.0,
        "tot_pup_stem": 119.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 597.0,
        "tot_pup_other": 523.0,
        "tot_pup_second": 586.0,
        "tot_pup_stem": 63.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1098.0,
        "tot_pup_other": 261.0,
        "tot_pup_second": 560.0,
        "tot_pup_stem": 299.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1041.0,
        "tot_pup_other": 416.0,
        "tot_pup_second": 645.0,
        "tot_pup_stem": 229.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1007.0,
        "tot_pup_other": 374.0,
        "tot_pup_second": 582.0,
        "tot_pup_stem": 208.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1002.0,
        "tot_pup_other": 567.0,
        "tot_pup_second": 778.0,
        "tot_pup_stem": 211.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 935.0,
        "tot_pup_other": 868.0,
        "tot_pup_second": 910.0,
        "tot_pup_stem": 42.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 762.0,
        "tot_pup_other": 102.0,
        "tot_pup_second": 450.0,
        "tot_pup_stem": 348.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 837.0,
        "tot_pup_other": 302.0,
        "tot_pup_second": 656.0,
        "tot_pup_stem": 354.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 694.0,
        "tot_pup_other": 237.0,
        "tot_pup_second": 495.0,
        "tot_pup_stem": 258.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 798.0,
        "tot_pup_other": 365.0,
        "tot_pup_second": 640.0,
        "tot_pup_stem": 275.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 688.0,
        "tot_pup_other": 559.0,
        "tot_pup_second": 673.0,
        "tot_pup_stem": 114.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8419.0,
        "tot_pup_other": 3998.0,
        "tot_pup_second": 6130.0,
        "tot_pup_stem": 2132.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8942.0,
        "tot_pup_other": 5457.0,
        "tot_pup_second": 7242.0,
        "tot_pup_stem": 1785.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8548.0,
        "tot_pup_other": 4668.0,
        "tot_pup_second": 6495.0,
        "tot_pup_stem": 1827.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8805.0,
        "tot_pup_other": 5667.0,
        "tot_pup_second": 7323.0,
        "tot_pup_stem": 1656.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8686.0,
        "tot_pup_other": 7933.0,
        "tot_pup_second": 8581.0,
        "tot_pup_stem": 648.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2260.0,
        "tot_pup_other": 605.0,
        "tot_pup_second": 1429.0,
        "tot_pup_stem": 824.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2331.0,
        "tot_pup_other": 962.0,
        "tot_pup_second": 1555.0,
        "tot_pup_stem": 593.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2120.0,
        "tot_pup_other": 899.0,
        "tot_pup_second": 1423.0,
        "tot_pup_stem": 524.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2048.0,
        "tot_pup_other": 993.0,
        "tot_pup_second": 1432.0,
        "tot_pup_stem": 439.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1805.0,
        "tot_pup_other": 1582.0,
        "tot_pup_second": 1749.0,
        "tot_pup_stem": 167.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 729.0,
        "tot_pup_other": 74.0,
        "tot_pup_second": 411.0,
        "tot_pup_stem": 337.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 723.0,
        "tot_pup_other": 191.0,
        "tot_pup_second": 458.0,
        "tot_pup_stem": 267.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 666.0,
        "tot_pup_other": 156.0,
        "tot_pup_second": 349.0,
        "tot_pup_stem": 193.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 629.0,
        "tot_pup_other": 184.0,
        "tot_pup_second": 392.0,
        "tot_pup_stem": 208.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 594.0,
        "tot_pup_other": 495.0,
        "tot_pup_second": 582.0,
        "tot_pup_stem": 87.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1551.0,
        "tot_pup_other": 426.0,
        "tot_pup_second": 1048.0,
        "tot_pup_stem": 622.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1569.0,
        "tot_pup_other": 659.0,
        "tot_pup_second": 1140.0,
        "tot_pup_stem": 481.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1421.0,
        "tot_pup_other": 540.0,
        "tot_pup_second": 941.0,
        "tot_pup_stem": 401.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1311.0,
        "tot_pup_other": 580.0,
        "tot_pup_second": 913.0,
        "tot_pup_stem": 333.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1366.0,
        "tot_pup_other": 1126.0,
        "tot_pup_second": 1287.0,
        "tot_pup_stem": 161.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1151.0,
        "tot_pup_other": 239.0,
        "tot_pup_second": 866.0,
        "tot_pup_stem": 627.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1292.0,
        "tot_pup_other": 369.0,
        "tot_pup_second": 1039.0,
        "tot_pup_stem": 670.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1185.0,
        "tot_pup_other": 294.0,
        "tot_pup_second": 878.0,
        "tot_pup_stem": 584.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1172.0,
        "tot_pup_other": 522.0,
        "tot_pup_second": 1066.0,
        "tot_pup_stem": 544.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1073.0,
        "tot_pup_other": 818.0,
        "tot_pup_second": 1017.0,
        "tot_pup_stem": 199.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 848.0,
        "tot_pup_other": 152.0,
        "tot_pup_second": 305.0,
        "tot_pup_stem": 153.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 900.0,
        "tot_pup_other": 306.0,
        "tot_pup_second": 402.0,
        "tot_pup_stem": 96.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 717.0,
        "tot_pup_other": 222.0,
        "tot_pup_second": 310.0,
        "tot_pup_stem": 88.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 712.0,
        "tot_pup_other": 284.0,
        "tot_pup_second": 357.0,
        "tot_pup_stem": 73.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 616.0,
        "tot_pup_other": 518.0,
        "tot_pup_second": 602.0,
        "tot_pup_stem": 84.0,
        "year": 2022
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1665.0,
        "tot_pup_other": 286.0,
        "tot_pup_second": 761.0,
        "tot_pup_stem": 475.0,
        "year": 2017
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1611.0,
        "tot_pup_other": 667.0,
        "tot_pup_second": 980.0,
        "tot_pup_stem": 313.0,
        "year": 2019
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1538.0,
        "tot_pup_other": 528.0,
        "tot_pup_second": 826.0,
        "tot_pup_stem": 298.0,
        "year": 2020
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1402.0,
        "tot_pup_other": 737.0,
        "tot_pup_second": 950.0,
        "tot_pup_stem": 213.0,
        "year": 2021
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1408.0,
        "tot_pup_other": 1236.0,
        "tot_pup_second": 1308.0,
        "tot_pup_stem": 72.0,
        "year": 2022
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 221.0,
        "tot_pup_other": 34.0,
        "tot_pup_second": 123.0,
        "tot_pup_stem": 89.0,
        "year": 2017
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 221.0,
        "tot_pup_other": 90.0,
        "tot_pup_second": 135.0,
        "tot_pup_stem": 45.0,
        "year": 2019
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 184.0,
        "tot_pup_other": 66.0,
        "tot_pup_second": 100.0,
        "tot_pup_stem": 34.0,
        "year": 2020
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 191.0,
        "tot_pup_other": 81.0,
        "tot_pup_second": 105.0,
        "tot_pup_stem": 24.0,
        "year": 2021
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 173.0,
        "tot_pup_other": 143.0,
        "tot_pup_second": 168.0,
        "tot_pup_stem": 25.0,
        "year": 2022
      }
    ]
  },
  "encoding": {
    "color": {
      "field": "year",
      "legend": {
        "title": "\u0413\u043e\u0434\u0438\u043d\u0430"
      },
      "scale": {
        "domain": [
          2019,
          2020,
          2021,
          2022
        ],
        "range": [
          "#FFAD01",
          "#EF5926",
          "#00923D",
          "#00A8BD"
        ]
      },
      "type": "nominal"
    },
    "tooltip": [
      {
        "field": "province",
        "type": "nominal"
      },
      {
        "field": "year",
        "type": "quantitative"
      },
      {
        "field": "tot_pup_second",
        "type": "quantitative"
      }
    ],
    "x": {
      "axis": {
        "grid": false
      },
      "field": "tot_pup_second",
      "title": "\u0411\u0440\u043e\u0439 \u0443\u0447\u0435\u043d\u0438\u0446\u0438 \u0441 \u0432\u0442\u043e\u0440\u0430 \u043c\u0430\u0442\u0443\u0440\u0430",
      "type": "quantitative"
    },
    "y": {
      "axis": {
        "grid": true,
        "labelLimit": 450
      },
      "field": "province",
      "sort": "x",
      "title": "",
      "type": "nominal"
    }
  },
  "height": {
    "step": 20
  },
  "mark": "point"
};    

function init() {
    var containers = document.getElementsByClassName('chart-container');
    if (containers.length) {
        vlSpec2.width = containers[0].offsetWidth - 80;
    }

    vegaEmbed('#vis2', vlSpec2);
}

init();
window.addEventListener('resize', init);
</script>

### 10% от учениците с матура по СТЕМ, от 25% през 2019

Броят положили матура по СТЕМ е индикатор както за интереса на младежите към областите наука, технологии, инженерство и математика, така и за бъдещите студенти и професионалисти в тези сфери.

Също както общия брой на зрелостниците в страната, учениците с матура по СТЕМ предмети намаляват във всички области от 2019 до  2022. Но ако спадът по БЕЛ е 12%, то спадът по СТЕМ е две трети - от 12 601 през 2019 до 4228 през 2022. Забележете, че спадът е най-вече между 2021 и 2022 г. През 2019 общо положилите матура по СТЕМ в страната са 25% от всички дванадесетокласници, явили се на матура по БЕЛ. За 2022 делът им е 10%.

<div class="chart-container">
  <div id="vis3"></div>
</div>

<script type="text/javascript">
var vlSpec3 = {

  "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json",
  "config": {
    "view": {
      "continuousHeight": 300,
      "continuousWidth": 400,
      "stroke": "transparent"
    }
  },
  "data": {
    "name": "data-ded6310303e98fe74c9fbb31a707bed5"
  },
  "datasets": {
    "data-ded6310303e98fe74c9fbb31a707bed5": [
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2425.0,
        "tot_pup_other": 413.0,
        "tot_pup_second": 1224.0,
        "tot_pup_stem": 811.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2571.0,
        "tot_pup_other": 1111.0,
        "tot_pup_second": 1683.0,
        "tot_pup_stem": 572.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2322.0,
        "tot_pup_other": 912.0,
        "tot_pup_second": 1417.0,
        "tot_pup_stem": 505.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2423.0,
        "tot_pup_other": 1138.0,
        "tot_pup_second": 1604.0,
        "tot_pup_stem": 466.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 2300.0,
        "tot_pup_other": 1965.0,
        "tot_pup_second": 2212.0,
        "tot_pup_stem": 247.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2927.0,
        "tot_pup_other": 914.0,
        "tot_pup_second": 2100.0,
        "tot_pup_stem": 1186.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 3057.0,
        "tot_pup_other": 1404.0,
        "tot_pup_second": 2449.0,
        "tot_pup_stem": 1045.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2811.0,
        "tot_pup_other": 1177.0,
        "tot_pup_second": 2059.0,
        "tot_pup_stem": 882.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2853.0,
        "tot_pup_other": 1511.0,
        "tot_pup_second": 2277.0,
        "tot_pup_stem": 766.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 2824.0,
        "tot_pup_other": 2351.0,
        "tot_pup_second": 2705.0,
        "tot_pup_stem": 354.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3355.0,
        "tot_pup_other": 1156.0,
        "tot_pup_second": 2112.0,
        "tot_pup_stem": 956.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3325.0,
        "tot_pup_other": 1632.0,
        "tot_pup_second": 2313.0,
        "tot_pup_stem": 681.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3210.0,
        "tot_pup_other": 1508.0,
        "tot_pup_second": 2163.0,
        "tot_pup_stem": 655.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3121.0,
        "tot_pup_other": 1660.0,
        "tot_pup_second": 2286.0,
        "tot_pup_stem": 626.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 3101.0,
        "tot_pup_other": 2632.0,
        "tot_pup_second": 3017.0,
        "tot_pup_stem": 385.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1604.0,
        "tot_pup_other": 394.0,
        "tot_pup_second": 822.0,
        "tot_pup_stem": 428.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1598.0,
        "tot_pup_other": 688.0,
        "tot_pup_second": 1057.0,
        "tot_pup_stem": 369.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1449.0,
        "tot_pup_other": 569.0,
        "tot_pup_second": 941.0,
        "tot_pup_stem": 372.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1475.0,
        "tot_pup_other": 718.0,
        "tot_pup_second": 1001.0,
        "tot_pup_stem": 283.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 1388.0,
        "tot_pup_other": 1267.0,
        "tot_pup_second": 1357.0,
        "tot_pup_stem": 90.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 576.0,
        "tot_pup_other": 168.0,
        "tot_pup_second": 356.0,
        "tot_pup_stem": 188.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 556.0,
        "tot_pup_other": 286.0,
        "tot_pup_second": 471.0,
        "tot_pup_stem": 185.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 555.0,
        "tot_pup_other": 250.0,
        "tot_pup_second": 433.0,
        "tot_pup_stem": 183.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 500.0,
        "tot_pup_other": 225.0,
        "tot_pup_second": 386.0,
        "tot_pup_stem": 161.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 447.0,
        "tot_pup_other": 382.0,
        "tot_pup_second": 440.0,
        "tot_pup_stem": 58.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1234.0,
        "tot_pup_other": 186.0,
        "tot_pup_second": 543.0,
        "tot_pup_stem": 357.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1304.0,
        "tot_pup_other": 477.0,
        "tot_pup_second": 714.0,
        "tot_pup_stem": 237.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1126.0,
        "tot_pup_other": 390.0,
        "tot_pup_second": 591.0,
        "tot_pup_stem": 201.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1182.0,
        "tot_pup_other": 608.0,
        "tot_pup_second": 779.0,
        "tot_pup_stem": 171.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 1093.0,
        "tot_pup_other": 959.0,
        "tot_pup_second": 1017.0,
        "tot_pup_stem": 58.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 706.0,
        "tot_pup_other": 184.0,
        "tot_pup_second": 429.0,
        "tot_pup_stem": 245.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 704.0,
        "tot_pup_other": 301.0,
        "tot_pup_second": 536.0,
        "tot_pup_stem": 235.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 696.0,
        "tot_pup_other": 248.0,
        "tot_pup_second": 497.0,
        "tot_pup_stem": 249.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 706.0,
        "tot_pup_other": 402.0,
        "tot_pup_second": 590.0,
        "tot_pup_stem": 188.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 641.0,
        "tot_pup_other": 565.0,
        "tot_pup_second": 634.0,
        "tot_pup_stem": 69.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 1001.0,
        "tot_pup_other": 280.0,
        "tot_pup_second": 473.0,
        "tot_pup_stem": 193.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 952.0,
        "tot_pup_other": 464.0,
        "tot_pup_second": 566.0,
        "tot_pup_stem": 102.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 865.0,
        "tot_pup_other": 416.0,
        "tot_pup_second": 523.0,
        "tot_pup_stem": 107.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 915.0,
        "tot_pup_other": 459.0,
        "tot_pup_second": 560.0,
        "tot_pup_stem": 101.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 809.0,
        "tot_pup_other": 741.0,
        "tot_pup_second": 798.0,
        "tot_pup_stem": 57.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1078.0,
        "tot_pup_other": 188.0,
        "tot_pup_second": 658.0,
        "tot_pup_stem": 470.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1239.0,
        "tot_pup_other": 446.0,
        "tot_pup_second": 877.0,
        "tot_pup_stem": 431.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1108.0,
        "tot_pup_other": 375.0,
        "tot_pup_second": 755.0,
        "tot_pup_stem": 380.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1089.0,
        "tot_pup_other": 358.0,
        "tot_pup_second": 748.0,
        "tot_pup_stem": 390.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 1017.0,
        "tot_pup_other": 714.0,
        "tot_pup_second": 959.0,
        "tot_pup_stem": 245.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 758.0,
        "tot_pup_other": 154.0,
        "tot_pup_second": 477.0,
        "tot_pup_stem": 323.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 821.0,
        "tot_pup_other": 311.0,
        "tot_pup_second": 636.0,
        "tot_pup_stem": 325.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 718.0,
        "tot_pup_other": 252.0,
        "tot_pup_second": 546.0,
        "tot_pup_stem": 294.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 711.0,
        "tot_pup_other": 346.0,
        "tot_pup_second": 625.0,
        "tot_pup_stem": 279.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 666.0,
        "tot_pup_other": 570.0,
        "tot_pup_second": 636.0,
        "tot_pup_stem": 66.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 978.0,
        "tot_pup_other": 282.0,
        "tot_pup_second": 497.0,
        "tot_pup_stem": 215.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 1025.0,
        "tot_pup_other": 619.0,
        "tot_pup_second": 806.0,
        "tot_pup_stem": 187.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 905.0,
        "tot_pup_other": 492.0,
        "tot_pup_second": 697.0,
        "tot_pup_stem": 205.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 868.0,
        "tot_pup_other": 502.0,
        "tot_pup_second": 679.0,
        "tot_pup_stem": 177.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 730.0,
        "tot_pup_other": 656.0,
        "tot_pup_second": 716.0,
        "tot_pup_stem": 60.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 924.0,
        "tot_pup_other": 194.0,
        "tot_pup_second": 533.0,
        "tot_pup_stem": 339.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 862.0,
        "tot_pup_other": 370.0,
        "tot_pup_second": 621.0,
        "tot_pup_stem": 251.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 793.0,
        "tot_pup_other": 324.0,
        "tot_pup_second": 500.0,
        "tot_pup_stem": 176.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 796.0,
        "tot_pup_other": 339.0,
        "tot_pup_second": 532.0,
        "tot_pup_stem": 193.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 638.0,
        "tot_pup_other": 579.0,
        "tot_pup_second": 627.0,
        "tot_pup_stem": 48.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1814.0,
        "tot_pup_other": 341.0,
        "tot_pup_second": 986.0,
        "tot_pup_stem": 645.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1680.0,
        "tot_pup_other": 660.0,
        "tot_pup_second": 1172.0,
        "tot_pup_stem": 512.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1534.0,
        "tot_pup_other": 497.0,
        "tot_pup_second": 958.0,
        "tot_pup_stem": 461.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1677.0,
        "tot_pup_other": 601.0,
        "tot_pup_second": 989.0,
        "tot_pup_stem": 388.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 1498.0,
        "tot_pup_other": 1310.0,
        "tot_pup_second": 1407.0,
        "tot_pup_stem": 97.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 841.0,
        "tot_pup_other": 199.0,
        "tot_pup_second": 322.0,
        "tot_pup_stem": 123.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 751.0,
        "tot_pup_other": 360.0,
        "tot_pup_second": 462.0,
        "tot_pup_stem": 102.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 724.0,
        "tot_pup_other": 263.0,
        "tot_pup_second": 365.0,
        "tot_pup_stem": 102.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 679.0,
        "tot_pup_other": 519.0,
        "tot_pup_second": 596.0,
        "tot_pup_stem": 77.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 668.0,
        "tot_pup_other": 629.0,
        "tot_pup_second": 646.0,
        "tot_pup_stem": 17.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1841.0,
        "tot_pup_other": 374.0,
        "tot_pup_second": 1090.0,
        "tot_pup_stem": 716.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1684.0,
        "tot_pup_other": 621.0,
        "tot_pup_second": 1120.0,
        "tot_pup_stem": 499.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1608.0,
        "tot_pup_other": 564.0,
        "tot_pup_second": 1023.0,
        "tot_pup_stem": 459.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1581.0,
        "tot_pup_other": 601.0,
        "tot_pup_second": 917.0,
        "tot_pup_stem": 316.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1473.0,
        "tot_pup_other": 1174.0,
        "tot_pup_second": 1386.0,
        "tot_pup_stem": 212.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4413.0,
        "tot_pup_other": 1338.0,
        "tot_pup_second": 2862.0,
        "tot_pup_stem": 1524.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4514.0,
        "tot_pup_other": 2199.0,
        "tot_pup_second": 3253.0,
        "tot_pup_stem": 1054.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4206.0,
        "tot_pup_other": 1740.0,
        "tot_pup_second": 2935.0,
        "tot_pup_stem": 1195.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 4241.0,
        "tot_pup_other": 2274.0,
        "tot_pup_second": 3307.0,
        "tot_pup_stem": 1033.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 3847.0,
        "tot_pup_other": 3437.0,
        "tot_pup_second": 3724.0,
        "tot_pup_stem": 287.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 862.0,
        "tot_pup_other": 131.0,
        "tot_pup_second": 613.0,
        "tot_pup_stem": 482.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 845.0,
        "tot_pup_other": 265.0,
        "tot_pup_second": 667.0,
        "tot_pup_stem": 402.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 748.0,
        "tot_pup_other": 203.0,
        "tot_pup_second": 526.0,
        "tot_pup_stem": 323.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 795.0,
        "tot_pup_other": 230.0,
        "tot_pup_second": 516.0,
        "tot_pup_stem": 286.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 718.0,
        "tot_pup_other": 602.0,
        "tot_pup_second": 703.0,
        "tot_pup_stem": 101.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1502.0,
        "tot_pup_other": 439.0,
        "tot_pup_second": 900.0,
        "tot_pup_stem": 461.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1453.0,
        "tot_pup_other": 704.0,
        "tot_pup_second": 1082.0,
        "tot_pup_stem": 378.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1332.0,
        "tot_pup_other": 585.0,
        "tot_pup_second": 988.0,
        "tot_pup_stem": 403.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1395.0,
        "tot_pup_other": 724.0,
        "tot_pup_second": 1073.0,
        "tot_pup_stem": 349.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 1254.0,
        "tot_pup_other": 1110.0,
        "tot_pup_second": 1225.0,
        "tot_pup_stem": 115.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 831.0,
        "tot_pup_other": 136.0,
        "tot_pup_second": 446.0,
        "tot_pup_stem": 310.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 748.0,
        "tot_pup_other": 292.0,
        "tot_pup_second": 493.0,
        "tot_pup_stem": 201.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 688.0,
        "tot_pup_other": 217.0,
        "tot_pup_second": 394.0,
        "tot_pup_stem": 177.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 684.0,
        "tot_pup_other": 258.0,
        "tot_pup_second": 377.0,
        "tot_pup_stem": 119.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 597.0,
        "tot_pup_other": 523.0,
        "tot_pup_second": 586.0,
        "tot_pup_stem": 63.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1098.0,
        "tot_pup_other": 261.0,
        "tot_pup_second": 560.0,
        "tot_pup_stem": 299.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1041.0,
        "tot_pup_other": 416.0,
        "tot_pup_second": 645.0,
        "tot_pup_stem": 229.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1007.0,
        "tot_pup_other": 374.0,
        "tot_pup_second": 582.0,
        "tot_pup_stem": 208.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 1002.0,
        "tot_pup_other": 567.0,
        "tot_pup_second": 778.0,
        "tot_pup_stem": 211.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 935.0,
        "tot_pup_other": 868.0,
        "tot_pup_second": 910.0,
        "tot_pup_stem": 42.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 762.0,
        "tot_pup_other": 102.0,
        "tot_pup_second": 450.0,
        "tot_pup_stem": 348.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 837.0,
        "tot_pup_other": 302.0,
        "tot_pup_second": 656.0,
        "tot_pup_stem": 354.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 694.0,
        "tot_pup_other": 237.0,
        "tot_pup_second": 495.0,
        "tot_pup_stem": 258.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 798.0,
        "tot_pup_other": 365.0,
        "tot_pup_second": 640.0,
        "tot_pup_stem": 275.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 688.0,
        "tot_pup_other": 559.0,
        "tot_pup_second": 673.0,
        "tot_pup_stem": 114.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8419.0,
        "tot_pup_other": 3998.0,
        "tot_pup_second": 6130.0,
        "tot_pup_stem": 2132.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8942.0,
        "tot_pup_other": 5457.0,
        "tot_pup_second": 7242.0,
        "tot_pup_stem": 1785.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8548.0,
        "tot_pup_other": 4668.0,
        "tot_pup_second": 6495.0,
        "tot_pup_stem": 1827.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8805.0,
        "tot_pup_other": 5667.0,
        "tot_pup_second": 7323.0,
        "tot_pup_stem": 1656.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 8686.0,
        "tot_pup_other": 7933.0,
        "tot_pup_second": 8581.0,
        "tot_pup_stem": 648.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2260.0,
        "tot_pup_other": 605.0,
        "tot_pup_second": 1429.0,
        "tot_pup_stem": 824.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2331.0,
        "tot_pup_other": 962.0,
        "tot_pup_second": 1555.0,
        "tot_pup_stem": 593.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2120.0,
        "tot_pup_other": 899.0,
        "tot_pup_second": 1423.0,
        "tot_pup_stem": 524.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 2048.0,
        "tot_pup_other": 993.0,
        "tot_pup_second": 1432.0,
        "tot_pup_stem": 439.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1805.0,
        "tot_pup_other": 1582.0,
        "tot_pup_second": 1749.0,
        "tot_pup_stem": 167.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 729.0,
        "tot_pup_other": 74.0,
        "tot_pup_second": 411.0,
        "tot_pup_stem": 337.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 723.0,
        "tot_pup_other": 191.0,
        "tot_pup_second": 458.0,
        "tot_pup_stem": 267.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 666.0,
        "tot_pup_other": 156.0,
        "tot_pup_second": 349.0,
        "tot_pup_stem": 193.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 629.0,
        "tot_pup_other": 184.0,
        "tot_pup_second": 392.0,
        "tot_pup_stem": 208.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 594.0,
        "tot_pup_other": 495.0,
        "tot_pup_second": 582.0,
        "tot_pup_stem": 87.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1551.0,
        "tot_pup_other": 426.0,
        "tot_pup_second": 1048.0,
        "tot_pup_stem": 622.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1569.0,
        "tot_pup_other": 659.0,
        "tot_pup_second": 1140.0,
        "tot_pup_stem": 481.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1421.0,
        "tot_pup_other": 540.0,
        "tot_pup_second": 941.0,
        "tot_pup_stem": 401.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1311.0,
        "tot_pup_other": 580.0,
        "tot_pup_second": 913.0,
        "tot_pup_stem": 333.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1366.0,
        "tot_pup_other": 1126.0,
        "tot_pup_second": 1287.0,
        "tot_pup_stem": 161.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1151.0,
        "tot_pup_other": 239.0,
        "tot_pup_second": 866.0,
        "tot_pup_stem": 627.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1292.0,
        "tot_pup_other": 369.0,
        "tot_pup_second": 1039.0,
        "tot_pup_stem": 670.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1185.0,
        "tot_pup_other": 294.0,
        "tot_pup_second": 878.0,
        "tot_pup_stem": 584.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1172.0,
        "tot_pup_other": 522.0,
        "tot_pup_second": 1066.0,
        "tot_pup_stem": 544.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 1073.0,
        "tot_pup_other": 818.0,
        "tot_pup_second": 1017.0,
        "tot_pup_stem": 199.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 848.0,
        "tot_pup_other": 152.0,
        "tot_pup_second": 305.0,
        "tot_pup_stem": 153.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 900.0,
        "tot_pup_other": 306.0,
        "tot_pup_second": 402.0,
        "tot_pup_stem": 96.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 717.0,
        "tot_pup_other": 222.0,
        "tot_pup_second": 310.0,
        "tot_pup_stem": 88.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 712.0,
        "tot_pup_other": 284.0,
        "tot_pup_second": 357.0,
        "tot_pup_stem": 73.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 616.0,
        "tot_pup_other": 518.0,
        "tot_pup_second": 602.0,
        "tot_pup_stem": 84.0,
        "year": 2022
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1665.0,
        "tot_pup_other": 286.0,
        "tot_pup_second": 761.0,
        "tot_pup_stem": 475.0,
        "year": 2017
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1611.0,
        "tot_pup_other": 667.0,
        "tot_pup_second": 980.0,
        "tot_pup_stem": 313.0,
        "year": 2019
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1538.0,
        "tot_pup_other": 528.0,
        "tot_pup_second": 826.0,
        "tot_pup_stem": 298.0,
        "year": 2020
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1402.0,
        "tot_pup_other": 737.0,
        "tot_pup_second": 950.0,
        "tot_pup_stem": 213.0,
        "year": 2021
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 1408.0,
        "tot_pup_other": 1236.0,
        "tot_pup_second": 1308.0,
        "tot_pup_stem": 72.0,
        "year": 2022
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 221.0,
        "tot_pup_other": 34.0,
        "tot_pup_second": 123.0,
        "tot_pup_stem": 89.0,
        "year": 2017
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 221.0,
        "tot_pup_other": 90.0,
        "tot_pup_second": 135.0,
        "tot_pup_stem": 45.0,
        "year": 2019
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 184.0,
        "tot_pup_other": 66.0,
        "tot_pup_second": 100.0,
        "tot_pup_stem": 34.0,
        "year": 2020
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 191.0,
        "tot_pup_other": 81.0,
        "tot_pup_second": 105.0,
        "tot_pup_stem": 24.0,
        "year": 2021
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 173.0,
        "tot_pup_other": 143.0,
        "tot_pup_second": 168.0,
        "tot_pup_stem": 25.0,
        "year": 2022
      }
    ]
  },
  "encoding": {
    "color": {
      "field": "year",
      "legend": {
        "title": "\u0413\u043e\u0434\u0438\u043d\u0430"
      },
      "scale": {
        "domain": [
          2019,
          2020,
          2021,
          2022
        ],
        "range": [
          "#FFAD01",
          "#EF5926",
          "#00923D",
          "#00A8BD"
        ]
      },
      "type": "nominal"
    },
    "tooltip": [
      {
        "field": "province",
        "type": "nominal"
      },
      {
        "field": "year",
        "type": "quantitative"
      },
      {
        "field": "tot_pup_stem",
        "type": "quantitative"
      }
    ],
    "x": {
      "axis": {
        "grid": false
      },
      "field": "tot_pup_stem",
      "title": "\u0411\u0440\u043e\u0439 \u0443\u0447\u0435\u043d\u0438\u0446\u0438 \u0441 \u043c\u0430\u0442\u0443\u0440\u0430 \u043f\u043e \u0421\u0422\u0415\u041c",
      "type": "quantitative"
    },
    "y": {
      "axis": {
        "grid": true,
        "labelLimit": 450
      },
      "field": "province",
      "sort": "x",
      "title": "",
      "type": "nominal"
    }
  },
  "height": {
    "step": 20
  },
  "mark": "point"
};


function init() {
    var containers = document.getElementsByClassName('chart-container');
    if (containers.length) {
        vlSpec3.width = containers[0].offsetWidth - 80;
    }

    vegaEmbed('#vis3', vlSpec3);
}

init();
window.addEventListener('resize', init);
</script>

София - град (намаление с 1137 ученици), Пловдив (-767), Бургас (-691) и Шумен (-471) бележат най-голям отлив в броя ученици, явили се на матура по СТЕМ предмети между 2019 и 2022. Перник, Сливен, Пазарджик и Монтана са областите, в които положилите матура по СТЕМ през 2022 са с над 80%
по-малко спрямо 2019.

Този спад вероятно се дължи на промяната във втората матура за учениците от професионалните училища. Вместо избор между втора матура по общообразователен предмет или изпит по теория на професията, от 2022 те задължително полагат държавен изпит за придобиване на професионална квалификация, който обединява теория и практика на професията и специалността. И все пак, интересът към матурите по СТЕМ предмети намалява и сред завършващите училища, различни от професионални (общообразователни, специални, спортни, по изкуствата).


### Учениците от професионалните училища[^5] не полагат втора матура по СТЕМ, а вместо това по специалност на училището


<div class="chart-container">
  <div id="vis4"></div>
</div>

<script type="text/javascript">
var vlSpec4 = {

  "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json",
  "config": {
    "view": {
      "continuousHeight": 300,
      "continuousWidth": 400,
      "stroke": "transparent"
    }
  },
  "data": {
    "name": "data-7518a193b4993f56ff9dfb15d1a9cea9"
  },
  "datasets": {
    "data-7518a193b4993f56ff9dfb15d1a9cea9": [
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 1018.0,
        "tot_pup_other": 49.0,
        "tot_pup_second": 289.0,
        "tot_pup_stem": 240.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 1153.0,
        "tot_pup_other": 310.0,
        "tot_pup_second": 437.0,
        "tot_pup_stem": 127.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 954.0,
        "tot_pup_other": 224.0,
        "tot_pup_second": 323.0,
        "tot_pup_stem": 99.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 1103.0,
        "tot_pup_other": 228.0,
        "tot_pup_second": 298.0,
        "tot_pup_stem": 70.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 937.0,
        "tot_pup_other": 885.0,
        "tot_pup_second": 885.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 1174.0,
        "tot_pup_other": 173.0,
        "tot_pup_second": 746.0,
        "tot_pup_stem": 573.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 1226.0,
        "tot_pup_other": 406.0,
        "tot_pup_second": 856.0,
        "tot_pup_stem": 450.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 997.0,
        "tot_pup_other": 246.0,
        "tot_pup_second": 535.0,
        "tot_pup_stem": 289.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 999.0,
        "tot_pup_other": 370.0,
        "tot_pup_second": 594.0,
        "tot_pup_stem": 224.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 996.0,
        "tot_pup_other": 912.0,
        "tot_pup_second": 912.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 1128.0,
        "tot_pup_other": 149.0,
        "tot_pup_second": 435.0,
        "tot_pup_stem": 286.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 1103.0,
        "tot_pup_other": 299.0,
        "tot_pup_second": 420.0,
        "tot_pup_stem": 121.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 962.0,
        "tot_pup_other": 171.0,
        "tot_pup_second": 297.0,
        "tot_pup_stem": 126.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 912.0,
        "tot_pup_other": 225.0,
        "tot_pup_second": 306.0,
        "tot_pup_stem": 81.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 889.0,
        "tot_pup_other": 838.0,
        "tot_pup_second": 838.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 738.0,
        "tot_pup_other": 91.0,
        "tot_pup_second": 288.0,
        "tot_pup_stem": 197.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 781.0,
        "tot_pup_other": 175.0,
        "tot_pup_second": 374.0,
        "tot_pup_stem": 199.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 678.0,
        "tot_pup_other": 125.0,
        "tot_pup_second": 285.0,
        "tot_pup_stem": 160.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 607.0,
        "tot_pup_other": 123.0,
        "tot_pup_second": 215.0,
        "tot_pup_stem": 92.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 554.0,
        "tot_pup_other": 533.0,
        "tot_pup_second": 533.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 211.0,
        "tot_pup_other": 30.0,
        "tot_pup_second": 93.0,
        "tot_pup_stem": 63.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 160.0,
        "tot_pup_other": 35.0,
        "tot_pup_second": 89.0,
        "tot_pup_stem": 54.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 176.0,
        "tot_pup_other": 28.0,
        "tot_pup_second": 76.0,
        "tot_pup_stem": 48.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 155.0,
        "tot_pup_other": 22.0,
        "tot_pup_second": 64.0,
        "tot_pup_stem": 42.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 105.0,
        "tot_pup_other": 105.0,
        "tot_pup_second": 105.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 372.0,
        "tot_pup_other": 21.0,
        "tot_pup_second": 109.0,
        "tot_pup_stem": 88.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 432.0,
        "tot_pup_other": 73.0,
        "tot_pup_second": 116.0,
        "tot_pup_stem": 43.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 329.0,
        "tot_pup_other": 46.0,
        "tot_pup_second": 72.0,
        "tot_pup_stem": 26.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 371.0,
        "tot_pup_other": 60.0,
        "tot_pup_second": 74.0,
        "tot_pup_stem": 14.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 350.0,
        "tot_pup_other": 287.0,
        "tot_pup_second": 287.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 350.0,
        "tot_pup_other": 54.0,
        "tot_pup_second": 170.0,
        "tot_pup_stem": 116.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 327.0,
        "tot_pup_other": 101.0,
        "tot_pup_second": 230.0,
        "tot_pup_stem": 129.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 326.0,
        "tot_pup_other": 78.0,
        "tot_pup_second": 217.0,
        "tot_pup_stem": 139.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 328.0,
        "tot_pup_other": 141.0,
        "tot_pup_second": 239.0,
        "tot_pup_stem": 98.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 252.0,
        "tot_pup_other": 246.0,
        "tot_pup_second": 246.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 239.0,
        "tot_pup_other": 2.0,
        "tot_pup_second": 50.0,
        "tot_pup_stem": 48.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 255.0,
        "tot_pup_other": 20.0,
        "tot_pup_second": 42.0,
        "tot_pup_stem": 22.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 241.0,
        "tot_pup_other": 12.0,
        "tot_pup_second": 22.0,
        "tot_pup_stem": 10.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 298.0,
        "tot_pup_other": 13.0,
        "tot_pup_second": 31.0,
        "tot_pup_stem": 18.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 203.0,
        "tot_pup_other": 201.0,
        "tot_pup_second": 201.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 381.0,
        "tot_pup_other": 17.0,
        "tot_pup_second": 113.0,
        "tot_pup_stem": 96.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 453.0,
        "tot_pup_other": 73.0,
        "tot_pup_second": 145.0,
        "tot_pup_stem": 72.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 378.0,
        "tot_pup_other": 20.0,
        "tot_pup_second": 67.0,
        "tot_pup_stem": 47.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 386.0,
        "tot_pup_other": 27.0,
        "tot_pup_second": 70.0,
        "tot_pup_stem": 43.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 274.0,
        "tot_pup_other": 224.0,
        "tot_pup_second": 224.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 359.0,
        "tot_pup_other": 44.0,
        "tot_pup_second": 193.0,
        "tot_pup_stem": 149.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 366.0,
        "tot_pup_other": 144.0,
        "tot_pup_second": 282.0,
        "tot_pup_stem": 138.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 337.0,
        "tot_pup_other": 101.0,
        "tot_pup_second": 255.0,
        "tot_pup_stem": 154.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 293.0,
        "tot_pup_other": 121.0,
        "tot_pup_second": 234.0,
        "tot_pup_stem": 113.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 217.0,
        "tot_pup_other": 192.0,
        "tot_pup_second": 192.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 355.0,
        "tot_pup_other": 29.0,
        "tot_pup_second": 94.0,
        "tot_pup_stem": 65.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 359.0,
        "tot_pup_other": 170.0,
        "tot_pup_second": 205.0,
        "tot_pup_stem": 35.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 297.0,
        "tot_pup_other": 126.0,
        "tot_pup_second": 162.0,
        "tot_pup_stem": 36.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 256.0,
        "tot_pup_other": 98.0,
        "tot_pup_second": 133.0,
        "tot_pup_stem": 35.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 234.0,
        "tot_pup_other": 226.0,
        "tot_pup_second": 226.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 494.0,
        "tot_pup_other": 63.0,
        "tot_pup_second": 283.0,
        "tot_pup_stem": 220.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 449.0,
        "tot_pup_other": 130.0,
        "tot_pup_second": 269.0,
        "tot_pup_stem": 139.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 412.0,
        "tot_pup_other": 90.0,
        "tot_pup_second": 169.0,
        "tot_pup_stem": 79.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 428.0,
        "tot_pup_other": 104.0,
        "tot_pup_second": 179.0,
        "tot_pup_stem": 75.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 282.0,
        "tot_pup_other": 278.0,
        "tot_pup_second": 278.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 964.0,
        "tot_pup_other": 43.0,
        "tot_pup_second": 358.0,
        "tot_pup_stem": 315.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 822.0,
        "tot_pup_other": 157.0,
        "tot_pup_second": 392.0,
        "tot_pup_stem": 235.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 808.0,
        "tot_pup_other": 89.0,
        "tot_pup_second": 310.0,
        "tot_pup_stem": 221.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 798.0,
        "tot_pup_other": 77.0,
        "tot_pup_second": 212.0,
        "tot_pup_stem": 135.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 651.0,
        "tot_pup_other": 584.0,
        "tot_pup_second": 584.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 422.0,
        "tot_pup_other": 39.0,
        "tot_pup_second": 97.0,
        "tot_pup_stem": 58.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 388.0,
        "tot_pup_other": 125.0,
        "tot_pup_second": 190.0,
        "tot_pup_stem": 65.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 372.0,
        "tot_pup_other": 107.0,
        "tot_pup_second": 144.0,
        "tot_pup_stem": 37.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 353.0,
        "tot_pup_other": 250.0,
        "tot_pup_second": 275.0,
        "tot_pup_stem": 25.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 288.0,
        "tot_pup_other": 273.0,
        "tot_pup_second": 273.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 826.0,
        "tot_pup_other": 71.0,
        "tot_pup_second": 383.0,
        "tot_pup_stem": 312.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 693.0,
        "tot_pup_other": 131.0,
        "tot_pup_second": 289.0,
        "tot_pup_stem": 158.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 673.0,
        "tot_pup_other": 125.0,
        "tot_pup_second": 240.0,
        "tot_pup_stem": 115.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 666.0,
        "tot_pup_other": 98.0,
        "tot_pup_second": 162.0,
        "tot_pup_stem": 64.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 514.0,
        "tot_pup_other": 450.0,
        "tot_pup_second": 450.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 1730.0,
        "tot_pup_other": 271.0,
        "tot_pup_second": 931.0,
        "tot_pup_stem": 660.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 1772.0,
        "tot_pup_other": 554.0,
        "tot_pup_second": 1046.0,
        "tot_pup_stem": 492.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 1555.0,
        "tot_pup_other": 414.0,
        "tot_pup_second": 904.0,
        "tot_pup_stem": 490.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 1594.0,
        "tot_pup_other": 612.0,
        "tot_pup_second": 978.0,
        "tot_pup_stem": 366.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 1324.0,
        "tot_pup_other": 1230.0,
        "tot_pup_second": 1230.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 462.0,
        "tot_pup_other": 10.0,
        "tot_pup_second": 303.0,
        "tot_pup_stem": 293.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 447.0,
        "tot_pup_other": 84.0,
        "tot_pup_second": 295.0,
        "tot_pup_stem": 211.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 366.0,
        "tot_pup_other": 33.0,
        "tot_pup_second": 196.0,
        "tot_pup_stem": 163.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 413.0,
        "tot_pup_other": 44.0,
        "tot_pup_second": 163.0,
        "tot_pup_stem": 119.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 338.0,
        "tot_pup_other": 320.0,
        "tot_pup_second": 320.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 813.0,
        "tot_pup_other": 144.0,
        "tot_pup_second": 363.0,
        "tot_pup_stem": 219.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 718.0,
        "tot_pup_other": 235.0,
        "tot_pup_second": 406.0,
        "tot_pup_stem": 171.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 656.0,
        "tot_pup_other": 196.0,
        "tot_pup_second": 355.0,
        "tot_pup_stem": 159.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 665.0,
        "tot_pup_other": 225.0,
        "tot_pup_second": 364.0,
        "tot_pup_stem": 139.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 551.0,
        "tot_pup_other": 528.0,
        "tot_pup_second": 528.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 424.0,
        "tot_pup_other": 32.0,
        "tot_pup_second": 179.0,
        "tot_pup_stem": 147.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 360.0,
        "tot_pup_other": 71.0,
        "tot_pup_second": 162.0,
        "tot_pup_stem": 91.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 339.0,
        "tot_pup_other": 34.0,
        "tot_pup_second": 113.0,
        "tot_pup_stem": 79.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 302.0,
        "tot_pup_other": 53.0,
        "tot_pup_second": 80.0,
        "tot_pup_stem": 27.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 257.0,
        "tot_pup_other": 250.0,
        "tot_pup_second": 250.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 406.0,
        "tot_pup_other": 55.0,
        "tot_pup_second": 113.0,
        "tot_pup_stem": 58.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 446.0,
        "tot_pup_other": 128.0,
        "tot_pup_second": 203.0,
        "tot_pup_stem": 75.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 449.0,
        "tot_pup_other": 113.0,
        "tot_pup_second": 197.0,
        "tot_pup_stem": 84.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 370.0,
        "tot_pup_other": 232.0,
        "tot_pup_second": 277.0,
        "tot_pup_stem": 45.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 348.0,
        "tot_pup_other": 328.0,
        "tot_pup_second": 328.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 198.0,
        "tot_pup_other": 4.0,
        "tot_pup_second": 93.0,
        "tot_pup_stem": 89.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 247.0,
        "tot_pup_other": 51.0,
        "tot_pup_second": 169.0,
        "tot_pup_stem": 118.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 158.0,
        "tot_pup_other": 15.0,
        "tot_pup_second": 69.0,
        "tot_pup_stem": 54.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 212.0,
        "tot_pup_other": 22.0,
        "tot_pup_second": 97.0,
        "tot_pup_stem": 75.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 197.0,
        "tot_pup_other": 189.0,
        "tot_pup_second": 189.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 1624.0,
        "tot_pup_other": 475.0,
        "tot_pup_second": 910.0,
        "tot_pup_stem": 435.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 1784.0,
        "tot_pup_other": 817.0,
        "tot_pup_second": 1210.0,
        "tot_pup_stem": 393.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 1596.0,
        "tot_pup_other": 585.0,
        "tot_pup_second": 877.0,
        "tot_pup_stem": 292.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 1727.0,
        "tot_pup_other": 756.0,
        "tot_pup_second": 1032.0,
        "tot_pup_stem": 276.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 1581.0,
        "tot_pup_other": 1561.0,
        "tot_pup_second": 1561.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1067.0,
        "tot_pup_other": 136.0,
        "tot_pup_second": 528.0,
        "tot_pup_stem": 392.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1144.0,
        "tot_pup_other": 304.0,
        "tot_pup_second": 610.0,
        "tot_pup_stem": 306.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 992.0,
        "tot_pup_other": 254.0,
        "tot_pup_second": 510.0,
        "tot_pup_stem": 256.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 920.0,
        "tot_pup_other": 287.0,
        "tot_pup_second": 458.0,
        "tot_pup_stem": 171.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 695.0,
        "tot_pup_other": 668.0,
        "tot_pup_second": 668.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 377.0,
        "tot_pup_other": 18.0,
        "tot_pup_second": 143.0,
        "tot_pup_stem": 125.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 374.0,
        "tot_pup_other": 49.0,
        "tot_pup_second": 124.0,
        "tot_pup_stem": 75.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 378.0,
        "tot_pup_other": 40.0,
        "tot_pup_second": 89.0,
        "tot_pup_stem": 49.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 315.0,
        "tot_pup_other": 27.0,
        "tot_pup_second": 83.0,
        "tot_pup_stem": 56.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 271.0,
        "tot_pup_other": 268.0,
        "tot_pup_second": 268.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 513.0,
        "tot_pup_other": 57.0,
        "tot_pup_second": 308.0,
        "tot_pup_stem": 251.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 550.0,
        "tot_pup_other": 131.0,
        "tot_pup_second": 315.0,
        "tot_pup_stem": 184.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 457.0,
        "tot_pup_other": 84.0,
        "tot_pup_second": 217.0,
        "tot_pup_stem": 133.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 388.0,
        "tot_pup_other": 54.0,
        "tot_pup_second": 114.0,
        "tot_pup_stem": 60.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 407.0,
        "tot_pup_other": 364.0,
        "tot_pup_second": 364.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 458.0,
        "tot_pup_other": 33.0,
        "tot_pup_second": 321.0,
        "tot_pup_stem": 288.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 504.0,
        "tot_pup_other": 82.0,
        "tot_pup_second": 401.0,
        "tot_pup_stem": 319.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 460.0,
        "tot_pup_other": 60.0,
        "tot_pup_second": 324.0,
        "tot_pup_stem": 264.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 415.0,
        "tot_pup_other": 99.0,
        "tot_pup_second": 335.0,
        "tot_pup_stem": 236.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 341.0,
        "tot_pup_other": 312.0,
        "tot_pup_second": 312.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 447.0,
        "tot_pup_other": 32.0,
        "tot_pup_second": 65.0,
        "tot_pup_stem": 33.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 430.0,
        "tot_pup_other": 47.0,
        "tot_pup_second": 53.0,
        "tot_pup_stem": 6.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 336.0,
        "tot_pup_other": 21.0,
        "tot_pup_second": 22.0,
        "tot_pup_stem": 1.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 348.0,
        "tot_pup_other": 18.0,
        "tot_pup_second": 20.0,
        "tot_pup_stem": 2.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 217.0,
        "tot_pup_other": 213.0,
        "tot_pup_second": 213.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 789.0,
        "tot_pup_other": 54.0,
        "tot_pup_second": 259.0,
        "tot_pup_stem": 205.0,
        "year": 2017
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 770.0,
        "tot_pup_other": 207.0,
        "tot_pup_second": 311.0,
        "tot_pup_stem": 104.0,
        "year": 2019
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 763.0,
        "tot_pup_other": 131.0,
        "tot_pup_second": 244.0,
        "tot_pup_stem": 113.0,
        "year": 2020
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 632.0,
        "tot_pup_other": 166.0,
        "tot_pup_second": 220.0,
        "tot_pup_stem": 54.0,
        "year": 2021
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 629.0,
        "tot_pup_other": 552.0,
        "tot_pup_second": 552.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 118.0,
        "tot_pup_other": 18.0,
        "tot_pup_second": 79.0,
        "tot_pup_stem": 61.0,
        "year": 2017
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 121.0,
        "tot_pup_other": 31.0,
        "tot_pup_second": 58.0,
        "tot_pup_stem": 27.0,
        "year": 2019
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 83.0,
        "tot_pup_other": 15.0,
        "tot_pup_second": 22.0,
        "tot_pup_stem": 7.0,
        "year": 2020
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 91.0,
        "tot_pup_other": 6.0,
        "tot_pup_second": 9.0,
        "tot_pup_stem": 3.0,
        "year": 2021
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 78.0,
        "tot_pup_other": 75.0,
        "tot_pup_second": 75.0,
        "tot_pup_stem": 0.0,
        "year": 2022
      }
    ]
  },
  "encoding": {
    "color": {
      "field": "year",
      "legend": {
        "title": "\u0413\u043e\u0434\u0438\u043d\u0430"
      },
      "scale": {
        "domain": [
          2019,
          2020,
          2021,
          2022
        ],
        "range": [
          "#FFAD01",
          "#EF5926",
          "#00923D",
          "#00A8BD"
        ]
      },
      "type": "nominal"
    },
    "tooltip": [
      {
        "field": "province",
        "type": "nominal"
      },
      {
        "field": "year",
        "type": "quantitative"
      },
      {
        "field": "tot_pup_stem",
        "type": "quantitative"
      }
    ],
    "x": {
      "axis": {
        "grid": false
      },
      "field": "tot_pup_stem",
      "title": "\u0411\u0440\u043e\u0439 \u0443\u0447\u0435\u043d\u0438\u0446\u0438 \u0441 \u043c\u0430\u0442\u0443\u0440\u0430 \u043f\u043e \u0421\u0422\u0415\u041c, \u043f\u0440\u043e\u0444\u0435\u0441\u0438\u043e\u043d\u0430\u043b\u043d\u0438 \u0443\u0447\u0438\u043b\u0438\u0449\u0430",
      "type": "quantitative"
    },
    "y": {
      "axis": {
        "grid": true,
        "labelLimit": 450
      },
      "field": "province",
      "sort": "x",
      "title": "",
      "type": "nominal"
    }
  },
  "height": {
    "step": 20
  },
  "mark": "point"
};

function init() {
    var containers = document.getElementsByClassName('chart-container');
    if (containers.length) {
        vlSpec4.width = containers[0].offsetWidth - 80;
    }

    vegaEmbed('#vis4', vlSpec4);
}

init();
window.addEventListener('resize', init);
</script>


Броят ученици от професионалните училища, които избират матура по някои от СТЕМ предметите, намалява през периода 2019-2021. Всъщност през 2022 няма ученици от професионални гимназии, които се явяват на матура по СТЕМ предмети, а тези училища включват към 30 и 40% от гимназистите в страната. Възможно е учениците да вземат трета матура по тези предмети - които са извън разглежданите данни. От една страна, това означава, че учениците от професионални паралелки могат да се фокусират изцяло върху теорията и практиката на своята професия и да специализират по-тясно в изучаваната сфера. От друга страна обаче, това може да е пропусната възможност или потенциал в сферите, различни от избраната професия от учениците, включително и СТЕМ.

### По-малко ученици от училища, различни от професионални, полагат матура по СТЕМ

Общият брой ученици с матура по СТЕМ в училищата, различни от професионални, също спада между 2019 и 2022. И тук намалението от 2021 до 2022 г. е значително по-голямо, отколкото за предходните години.

<div class="chart-container">
  <div id="vis5"></div>
</div>

<script type="text/javascript">
var vlSpec5 = {

  "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json",
  "config": {
    "view": {
      "continuousHeight": 300,
      "continuousWidth": 400,
      "stroke": "transparent"
    }
  },
  "data": {
    "name": "data-a5057c4fb8da189e390f844e8ce38578"
  },
  "datasets": {
    "data-a5057c4fb8da189e390f844e8ce38578": [
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 1407.0,
        "tot_pup_other": 364.0,
        "tot_pup_second": 935.0,
        "tot_pup_stem": 571.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 1418.0,
        "tot_pup_other": 801.0,
        "tot_pup_second": 1246.0,
        "tot_pup_stem": 445.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 1368.0,
        "tot_pup_other": 688.0,
        "tot_pup_second": 1094.0,
        "tot_pup_stem": 406.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 1320.0,
        "tot_pup_other": 910.0,
        "tot_pup_second": 1306.0,
        "tot_pup_stem": 396.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 1363.0,
        "tot_pup_other": 1080.0,
        "tot_pup_second": 1327.0,
        "tot_pup_stem": 247.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 1753.0,
        "tot_pup_other": 741.0,
        "tot_pup_second": 1354.0,
        "tot_pup_stem": 613.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 1831.0,
        "tot_pup_other": 998.0,
        "tot_pup_second": 1593.0,
        "tot_pup_stem": 595.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 1814.0,
        "tot_pup_other": 931.0,
        "tot_pup_second": 1524.0,
        "tot_pup_stem": 593.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 1854.0,
        "tot_pup_other": 1141.0,
        "tot_pup_second": 1683.0,
        "tot_pup_stem": 542.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "tot_pup_bel": 1828.0,
        "tot_pup_other": 1439.0,
        "tot_pup_second": 1793.0,
        "tot_pup_stem": 354.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 2227.0,
        "tot_pup_other": 1007.0,
        "tot_pup_second": 1677.0,
        "tot_pup_stem": 670.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 2222.0,
        "tot_pup_other": 1333.0,
        "tot_pup_second": 1893.0,
        "tot_pup_stem": 560.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 2248.0,
        "tot_pup_other": 1337.0,
        "tot_pup_second": 1866.0,
        "tot_pup_stem": 529.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 2209.0,
        "tot_pup_other": 1435.0,
        "tot_pup_second": 1980.0,
        "tot_pup_stem": 545.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "tot_pup_bel": 2212.0,
        "tot_pup_other": 1794.0,
        "tot_pup_second": 2179.0,
        "tot_pup_stem": 385.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 866.0,
        "tot_pup_other": 303.0,
        "tot_pup_second": 534.0,
        "tot_pup_stem": 231.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 817.0,
        "tot_pup_other": 513.0,
        "tot_pup_second": 683.0,
        "tot_pup_stem": 170.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 771.0,
        "tot_pup_other": 444.0,
        "tot_pup_second": 656.0,
        "tot_pup_stem": 212.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 868.0,
        "tot_pup_other": 595.0,
        "tot_pup_second": 786.0,
        "tot_pup_stem": 191.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "tot_pup_bel": 834.0,
        "tot_pup_other": 734.0,
        "tot_pup_second": 824.0,
        "tot_pup_stem": 90.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 365.0,
        "tot_pup_other": 138.0,
        "tot_pup_second": 263.0,
        "tot_pup_stem": 125.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 396.0,
        "tot_pup_other": 251.0,
        "tot_pup_second": 382.0,
        "tot_pup_stem": 131.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 379.0,
        "tot_pup_other": 222.0,
        "tot_pup_second": 357.0,
        "tot_pup_stem": 135.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 345.0,
        "tot_pup_other": 203.0,
        "tot_pup_second": 322.0,
        "tot_pup_stem": 119.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "tot_pup_bel": 342.0,
        "tot_pup_other": 277.0,
        "tot_pup_second": 335.0,
        "tot_pup_stem": 58.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 862.0,
        "tot_pup_other": 165.0,
        "tot_pup_second": 434.0,
        "tot_pup_stem": 269.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 872.0,
        "tot_pup_other": 404.0,
        "tot_pup_second": 598.0,
        "tot_pup_stem": 194.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 797.0,
        "tot_pup_other": 344.0,
        "tot_pup_second": 519.0,
        "tot_pup_stem": 175.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 811.0,
        "tot_pup_other": 548.0,
        "tot_pup_second": 705.0,
        "tot_pup_stem": 157.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "tot_pup_bel": 743.0,
        "tot_pup_other": 672.0,
        "tot_pup_second": 730.0,
        "tot_pup_stem": 58.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 356.0,
        "tot_pup_other": 130.0,
        "tot_pup_second": 259.0,
        "tot_pup_stem": 129.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 377.0,
        "tot_pup_other": 200.0,
        "tot_pup_second": 306.0,
        "tot_pup_stem": 106.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 370.0,
        "tot_pup_other": 170.0,
        "tot_pup_second": 280.0,
        "tot_pup_stem": 110.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 378.0,
        "tot_pup_other": 261.0,
        "tot_pup_second": 351.0,
        "tot_pup_stem": 90.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "tot_pup_bel": 389.0,
        "tot_pup_other": 319.0,
        "tot_pup_second": 388.0,
        "tot_pup_stem": 69.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 762.0,
        "tot_pup_other": 278.0,
        "tot_pup_second": 423.0,
        "tot_pup_stem": 145.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 697.0,
        "tot_pup_other": 444.0,
        "tot_pup_second": 524.0,
        "tot_pup_stem": 80.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 624.0,
        "tot_pup_other": 404.0,
        "tot_pup_second": 501.0,
        "tot_pup_stem": 97.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 617.0,
        "tot_pup_other": 446.0,
        "tot_pup_second": 529.0,
        "tot_pup_stem": 83.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "tot_pup_bel": 606.0,
        "tot_pup_other": 540.0,
        "tot_pup_second": 597.0,
        "tot_pup_stem": 57.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 697.0,
        "tot_pup_other": 171.0,
        "tot_pup_second": 545.0,
        "tot_pup_stem": 374.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 786.0,
        "tot_pup_other": 373.0,
        "tot_pup_second": 732.0,
        "tot_pup_stem": 359.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 730.0,
        "tot_pup_other": 355.0,
        "tot_pup_second": 688.0,
        "tot_pup_stem": 333.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 703.0,
        "tot_pup_other": 331.0,
        "tot_pup_second": 678.0,
        "tot_pup_stem": 347.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "tot_pup_bel": 743.0,
        "tot_pup_other": 490.0,
        "tot_pup_second": 735.0,
        "tot_pup_stem": 245.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 399.0,
        "tot_pup_other": 110.0,
        "tot_pup_second": 284.0,
        "tot_pup_stem": 174.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 455.0,
        "tot_pup_other": 167.0,
        "tot_pup_second": 354.0,
        "tot_pup_stem": 187.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 381.0,
        "tot_pup_other": 151.0,
        "tot_pup_second": 291.0,
        "tot_pup_stem": 140.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 418.0,
        "tot_pup_other": 225.0,
        "tot_pup_second": 391.0,
        "tot_pup_stem": 166.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "tot_pup_bel": 449.0,
        "tot_pup_other": 378.0,
        "tot_pup_second": 444.0,
        "tot_pup_stem": 66.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 623.0,
        "tot_pup_other": 253.0,
        "tot_pup_second": 403.0,
        "tot_pup_stem": 150.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 666.0,
        "tot_pup_other": 449.0,
        "tot_pup_second": 601.0,
        "tot_pup_stem": 152.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 608.0,
        "tot_pup_other": 366.0,
        "tot_pup_second": 535.0,
        "tot_pup_stem": 169.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 612.0,
        "tot_pup_other": 404.0,
        "tot_pup_second": 546.0,
        "tot_pup_stem": 142.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "tot_pup_bel": 496.0,
        "tot_pup_other": 430.0,
        "tot_pup_second": 490.0,
        "tot_pup_stem": 60.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 430.0,
        "tot_pup_other": 131.0,
        "tot_pup_second": 250.0,
        "tot_pup_stem": 119.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 413.0,
        "tot_pup_other": 240.0,
        "tot_pup_second": 352.0,
        "tot_pup_stem": 112.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 381.0,
        "tot_pup_other": 234.0,
        "tot_pup_second": 331.0,
        "tot_pup_stem": 97.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 368.0,
        "tot_pup_other": 235.0,
        "tot_pup_second": 353.0,
        "tot_pup_stem": 118.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "tot_pup_bel": 356.0,
        "tot_pup_other": 301.0,
        "tot_pup_second": 349.0,
        "tot_pup_stem": 48.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 850.0,
        "tot_pup_other": 298.0,
        "tot_pup_second": 628.0,
        "tot_pup_stem": 330.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 858.0,
        "tot_pup_other": 503.0,
        "tot_pup_second": 780.0,
        "tot_pup_stem": 277.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 726.0,
        "tot_pup_other": 408.0,
        "tot_pup_second": 648.0,
        "tot_pup_stem": 240.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 879.0,
        "tot_pup_other": 524.0,
        "tot_pup_second": 777.0,
        "tot_pup_stem": 253.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "tot_pup_bel": 847.0,
        "tot_pup_other": 726.0,
        "tot_pup_second": 823.0,
        "tot_pup_stem": 97.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 419.0,
        "tot_pup_other": 160.0,
        "tot_pup_second": 225.0,
        "tot_pup_stem": 65.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 363.0,
        "tot_pup_other": 235.0,
        "tot_pup_second": 272.0,
        "tot_pup_stem": 37.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 352.0,
        "tot_pup_other": 156.0,
        "tot_pup_second": 221.0,
        "tot_pup_stem": 65.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 326.0,
        "tot_pup_other": 269.0,
        "tot_pup_second": 321.0,
        "tot_pup_stem": 52.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "tot_pup_bel": 380.0,
        "tot_pup_other": 356.0,
        "tot_pup_second": 373.0,
        "tot_pup_stem": 17.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 1015.0,
        "tot_pup_other": 303.0,
        "tot_pup_second": 707.0,
        "tot_pup_stem": 404.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 991.0,
        "tot_pup_other": 490.0,
        "tot_pup_second": 831.0,
        "tot_pup_stem": 341.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 935.0,
        "tot_pup_other": 439.0,
        "tot_pup_second": 783.0,
        "tot_pup_stem": 344.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 915.0,
        "tot_pup_other": 503.0,
        "tot_pup_second": 755.0,
        "tot_pup_stem": 252.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "tot_pup_bel": 959.0,
        "tot_pup_other": 724.0,
        "tot_pup_second": 936.0,
        "tot_pup_stem": 212.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 2683.0,
        "tot_pup_other": 1067.0,
        "tot_pup_second": 1931.0,
        "tot_pup_stem": 864.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 2742.0,
        "tot_pup_other": 1645.0,
        "tot_pup_second": 2207.0,
        "tot_pup_stem": 562.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 2651.0,
        "tot_pup_other": 1326.0,
        "tot_pup_second": 2031.0,
        "tot_pup_stem": 705.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 2647.0,
        "tot_pup_other": 1662.0,
        "tot_pup_second": 2329.0,
        "tot_pup_stem": 667.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "tot_pup_bel": 2523.0,
        "tot_pup_other": 2207.0,
        "tot_pup_second": 2494.0,
        "tot_pup_stem": 287.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 400.0,
        "tot_pup_other": 121.0,
        "tot_pup_second": 310.0,
        "tot_pup_stem": 189.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 398.0,
        "tot_pup_other": 181.0,
        "tot_pup_second": 372.0,
        "tot_pup_stem": 191.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 382.0,
        "tot_pup_other": 170.0,
        "tot_pup_second": 330.0,
        "tot_pup_stem": 160.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 382.0,
        "tot_pup_other": 186.0,
        "tot_pup_second": 353.0,
        "tot_pup_stem": 167.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "tot_pup_bel": 380.0,
        "tot_pup_other": 282.0,
        "tot_pup_second": 383.0,
        "tot_pup_stem": 101.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 689.0,
        "tot_pup_other": 295.0,
        "tot_pup_second": 537.0,
        "tot_pup_stem": 242.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 735.0,
        "tot_pup_other": 469.0,
        "tot_pup_second": 676.0,
        "tot_pup_stem": 207.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 676.0,
        "tot_pup_other": 389.0,
        "tot_pup_second": 633.0,
        "tot_pup_stem": 244.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 730.0,
        "tot_pup_other": 499.0,
        "tot_pup_second": 709.0,
        "tot_pup_stem": 210.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "tot_pup_bel": 703.0,
        "tot_pup_other": 582.0,
        "tot_pup_second": 697.0,
        "tot_pup_stem": 115.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 407.0,
        "tot_pup_other": 104.0,
        "tot_pup_second": 267.0,
        "tot_pup_stem": 163.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 388.0,
        "tot_pup_other": 221.0,
        "tot_pup_second": 331.0,
        "tot_pup_stem": 110.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 349.0,
        "tot_pup_other": 183.0,
        "tot_pup_second": 281.0,
        "tot_pup_stem": 98.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 382.0,
        "tot_pup_other": 205.0,
        "tot_pup_second": 297.0,
        "tot_pup_stem": 92.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "tot_pup_bel": 340.0,
        "tot_pup_other": 273.0,
        "tot_pup_second": 336.0,
        "tot_pup_stem": 63.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 692.0,
        "tot_pup_other": 206.0,
        "tot_pup_second": 447.0,
        "tot_pup_stem": 241.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 595.0,
        "tot_pup_other": 288.0,
        "tot_pup_second": 442.0,
        "tot_pup_stem": 154.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 558.0,
        "tot_pup_other": 261.0,
        "tot_pup_second": 385.0,
        "tot_pup_stem": 124.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 632.0,
        "tot_pup_other": 335.0,
        "tot_pup_second": 501.0,
        "tot_pup_stem": 166.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "tot_pup_bel": 587.0,
        "tot_pup_other": 540.0,
        "tot_pup_second": 582.0,
        "tot_pup_stem": 42.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 564.0,
        "tot_pup_other": 98.0,
        "tot_pup_second": 357.0,
        "tot_pup_stem": 259.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 590.0,
        "tot_pup_other": 251.0,
        "tot_pup_second": 487.0,
        "tot_pup_stem": 236.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 536.0,
        "tot_pup_other": 222.0,
        "tot_pup_second": 426.0,
        "tot_pup_stem": 204.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 586.0,
        "tot_pup_other": 343.0,
        "tot_pup_second": 543.0,
        "tot_pup_stem": 200.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "tot_pup_bel": 491.0,
        "tot_pup_other": 370.0,
        "tot_pup_second": 484.0,
        "tot_pup_stem": 114.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 6795.0,
        "tot_pup_other": 3523.0,
        "tot_pup_second": 5220.0,
        "tot_pup_stem": 1697.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 7158.0,
        "tot_pup_other": 4640.0,
        "tot_pup_second": 6032.0,
        "tot_pup_stem": 1392.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 6952.0,
        "tot_pup_other": 4083.0,
        "tot_pup_second": 5618.0,
        "tot_pup_stem": 1535.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 7078.0,
        "tot_pup_other": 4911.0,
        "tot_pup_second": 6291.0,
        "tot_pup_stem": 1380.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "tot_pup_bel": 7105.0,
        "tot_pup_other": 6372.0,
        "tot_pup_second": 7020.0,
        "tot_pup_stem": 648.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1193.0,
        "tot_pup_other": 469.0,
        "tot_pup_second": 901.0,
        "tot_pup_stem": 432.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1187.0,
        "tot_pup_other": 658.0,
        "tot_pup_second": 945.0,
        "tot_pup_stem": 287.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1128.0,
        "tot_pup_other": 645.0,
        "tot_pup_second": 913.0,
        "tot_pup_stem": 268.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1128.0,
        "tot_pup_other": 706.0,
        "tot_pup_second": 974.0,
        "tot_pup_stem": 268.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "tot_pup_bel": 1110.0,
        "tot_pup_other": 914.0,
        "tot_pup_second": 1081.0,
        "tot_pup_stem": 167.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 352.0,
        "tot_pup_other": 56.0,
        "tot_pup_second": 268.0,
        "tot_pup_stem": 212.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 349.0,
        "tot_pup_other": 142.0,
        "tot_pup_second": 334.0,
        "tot_pup_stem": 192.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 288.0,
        "tot_pup_other": 116.0,
        "tot_pup_second": 260.0,
        "tot_pup_stem": 144.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 314.0,
        "tot_pup_other": 157.0,
        "tot_pup_second": 309.0,
        "tot_pup_stem": 152.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "tot_pup_bel": 323.0,
        "tot_pup_other": 227.0,
        "tot_pup_second": 314.0,
        "tot_pup_stem": 87.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1038.0,
        "tot_pup_other": 369.0,
        "tot_pup_second": 740.0,
        "tot_pup_stem": 371.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 1019.0,
        "tot_pup_other": 528.0,
        "tot_pup_second": 825.0,
        "tot_pup_stem": 297.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 964.0,
        "tot_pup_other": 456.0,
        "tot_pup_second": 724.0,
        "tot_pup_stem": 268.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 923.0,
        "tot_pup_other": 526.0,
        "tot_pup_second": 799.0,
        "tot_pup_stem": 273.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "tot_pup_bel": 959.0,
        "tot_pup_other": 762.0,
        "tot_pup_second": 923.0,
        "tot_pup_stem": 161.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 693.0,
        "tot_pup_other": 206.0,
        "tot_pup_second": 545.0,
        "tot_pup_stem": 339.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 788.0,
        "tot_pup_other": 287.0,
        "tot_pup_second": 638.0,
        "tot_pup_stem": 351.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 725.0,
        "tot_pup_other": 234.0,
        "tot_pup_second": 554.0,
        "tot_pup_stem": 320.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 757.0,
        "tot_pup_other": 423.0,
        "tot_pup_second": 731.0,
        "tot_pup_stem": 308.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "tot_pup_bel": 732.0,
        "tot_pup_other": 506.0,
        "tot_pup_second": 705.0,
        "tot_pup_stem": 199.0,
        "year": 2022
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 401.0,
        "tot_pup_other": 120.0,
        "tot_pup_second": 240.0,
        "tot_pup_stem": 120.0,
        "year": 2017
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 470.0,
        "tot_pup_other": 259.0,
        "tot_pup_second": 349.0,
        "tot_pup_stem": 90.0,
        "year": 2019
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 381.0,
        "tot_pup_other": 201.0,
        "tot_pup_second": 288.0,
        "tot_pup_stem": 87.0,
        "year": 2020
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 364.0,
        "tot_pup_other": 266.0,
        "tot_pup_second": 337.0,
        "tot_pup_stem": 71.0,
        "year": 2021
      },
      {
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "tot_pup_bel": 399.0,
        "tot_pup_other": 305.0,
        "tot_pup_second": 389.0,
        "tot_pup_stem": 84.0,
        "year": 2022
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 876.0,
        "tot_pup_other": 232.0,
        "tot_pup_second": 502.0,
        "tot_pup_stem": 270.0,
        "year": 2017
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 841.0,
        "tot_pup_other": 460.0,
        "tot_pup_second": 669.0,
        "tot_pup_stem": 209.0,
        "year": 2019
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 775.0,
        "tot_pup_other": 397.0,
        "tot_pup_second": 582.0,
        "tot_pup_stem": 185.0,
        "year": 2020
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 770.0,
        "tot_pup_other": 571.0,
        "tot_pup_second": 730.0,
        "tot_pup_stem": 159.0,
        "year": 2021
      },
      {
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "tot_pup_bel": 779.0,
        "tot_pup_other": 684.0,
        "tot_pup_second": 756.0,
        "tot_pup_stem": 72.0,
        "year": 2022
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 103.0,
        "tot_pup_other": 16.0,
        "tot_pup_second": 44.0,
        "tot_pup_stem": 28.0,
        "year": 2017
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 100.0,
        "tot_pup_other": 59.0,
        "tot_pup_second": 77.0,
        "tot_pup_stem": 18.0,
        "year": 2019
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 101.0,
        "tot_pup_other": 51.0,
        "tot_pup_second": 78.0,
        "tot_pup_stem": 27.0,
        "year": 2020
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 100.0,
        "tot_pup_other": 75.0,
        "tot_pup_second": 96.0,
        "tot_pup_stem": 21.0,
        "year": 2021
      },
      {
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "tot_pup_bel": 95.0,
        "tot_pup_other": 68.0,
        "tot_pup_second": 93.0,
        "tot_pup_stem": 25.0,
        "year": 2022
      }
    ]
  },
  "encoding": {
    "color": {
      "field": "year",
      "legend": {
        "title": "\u0413\u043e\u0434\u0438\u043d\u0430"
      },
      "scale": {
        "domain": [
          2019,
          2020,
          2021,
          2022
        ],
        "range": [
          "#FFAD01",
          "#EF5926",
          "#00923D",
          "#00A8BD"
        ]
      },
      "type": "nominal"
    },
    "tooltip": [
      {
        "field": "province",
        "type": "nominal"
      },
      {
        "field": "year",
        "type": "quantitative"
      },
      {
        "field": "tot_pup_stem",
        "type": "quantitative"
      }
    ],
    "x": {
      "axis": {
        "grid": false
      },
      "field": "tot_pup_stem",
      "title": "\u0411\u0440\u043e\u0439 \u0443\u0447\u0435\u043d\u0438\u0446\u0438 \u0441 \u043c\u0430\u0442\u0443\u0440\u0430 \u043f\u043e \u0421\u0422\u0415\u041c, \u0443\u0447\u0438\u043b\u0438\u0449\u0430, \u0440\u0430\u0437\u043b\u0438\u0447\u043d\u0438 \u043e\u0442 \u043f\u0440\u043e\u0444\u0435\u0441\u0438\u043e\u043d\u0430\u043b\u043d\u0438",
      "type": "quantitative"
    },
    "y": {
      "axis": {
        "grid": true,
        "labelLimit": 450
      },
      "field": "province",
      "sort": "x",
      "title": "",
      "type": "nominal"
    }
  },
  "height": {
    "step": 20
  },
  "mark": "point"
};

function init() {
    var containers = document.getElementsByClassName('chart-container');
    if (containers.length) {
        vlSpec5.width = containers[0].offsetWidth - 80;
    }

    vegaEmbed('#vis5', vlSpec5);
}

init();
window.addEventListener('resize', init);
</script>

Възможно е този спад да се дължи и на промяната във втората матура за езиковите гимназии - от 2022 учениците там полагат втора матура по един от профилиращите предмети.[^6]

Отлив от над 60% в броя зрелостници с матура по СТЕМ предмети между 2019 и 2022 се наблюдава в Сливен, Враца, Софийска област,  Пазарджик и Кюстендил. Интересно е да проследим какво прави матурите по СТЕМ предмети по-малко привлекателни - промяната в изпитния формат, нужда от по-солидна подготовка, недостатъчна подготовка в училище,
балообразуването при приема на кандидат-студенти или други фактори.

------------------------------------------------------------------------

### Оценките по СТЕМ в училищата, различни от професионални, се понижават

<div class="chart-container">
  <div id="vis6"></div>
</div>

<script type="text/javascript">
var vlSpec6 = {
  "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json",
  "config": {
    "view": {
      "continuousHeight": 300,
      "continuousWidth": 400,
      "stroke": "transparent"
    }
  },
  "data": {
    "name": "data-eae588f18bb23085acd6c79c0fe90d32"
  },
  "datasets": {
    "data-eae588f18bb23085acd6c79c0fe90d32": [
      {
        "average_grade_stem": 4.64,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "year": 2017
      },
      {
        "average_grade_stem": 4.84,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "year": 2019
      },
      {
        "average_grade_stem": 4.69,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "year": 2020
      },
      {
        "average_grade_stem": 4.57,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "year": 2021
      },
      {
        "average_grade_stem": 3.87,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u043b\u0430\u0433\u043e\u0435\u0432\u0433\u0440\u0430\u0434",
        "year": 2022
      },
      {
        "average_grade_stem": 4.51,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "year": 2017
      },
      {
        "average_grade_stem": 4.56,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "year": 2019
      },
      {
        "average_grade_stem": 4.45,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "year": 2020
      },
      {
        "average_grade_stem": 4.41,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "year": 2021
      },
      {
        "average_grade_stem": 3.76,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0411\u0443\u0440\u0433\u0430\u0441",
        "year": 2022
      },
      {
        "average_grade_stem": 4.55,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "year": 2017
      },
      {
        "average_grade_stem": 4.5,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "year": 2019
      },
      {
        "average_grade_stem": 4.41,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "year": 2020
      },
      {
        "average_grade_stem": 4.57,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "year": 2021
      },
      {
        "average_grade_stem": 4.28,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0430\u0440\u043d\u0430",
        "year": 2022
      },
      {
        "average_grade_stem": 4.84,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "year": 2017
      },
      {
        "average_grade_stem": 4.68,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "year": 2019
      },
      {
        "average_grade_stem": 4.74,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "year": 2020
      },
      {
        "average_grade_stem": 4.73,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "year": 2021
      },
      {
        "average_grade_stem": 4.17,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0435\u043b\u0438\u043a\u043e \u0422\u044a\u0440\u043d\u043e\u0432\u043e",
        "year": 2022
      },
      {
        "average_grade_stem": 4.5,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "year": 2017
      },
      {
        "average_grade_stem": 4.36,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "year": 2019
      },
      {
        "average_grade_stem": 4.3,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "year": 2020
      },
      {
        "average_grade_stem": 4.02,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "year": 2021
      },
      {
        "average_grade_stem": 3.64,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0438\u0434\u0438\u043d",
        "year": 2022
      },
      {
        "average_grade_stem": 4.8,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "year": 2017
      },
      {
        "average_grade_stem": 4.94,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "year": 2019
      },
      {
        "average_grade_stem": 4.65,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "year": 2020
      },
      {
        "average_grade_stem": 4.74,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "year": 2021
      },
      {
        "average_grade_stem": 4.34,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0412\u0440\u0430\u0446\u0430",
        "year": 2022
      },
      {
        "average_grade_stem": 4.73,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "year": 2017
      },
      {
        "average_grade_stem": 4.79,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "year": 2019
      },
      {
        "average_grade_stem": 5.0,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "year": 2020
      },
      {
        "average_grade_stem": 4.65,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "year": 2021
      },
      {
        "average_grade_stem": 3.91,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0413\u0430\u0431\u0440\u043e\u0432\u043e",
        "year": 2022
      },
      {
        "average_grade_stem": 4.39,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "year": 2017
      },
      {
        "average_grade_stem": 4.56,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "year": 2019
      },
      {
        "average_grade_stem": 4.33,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "year": 2020
      },
      {
        "average_grade_stem": 4.33,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "year": 2021
      },
      {
        "average_grade_stem": 3.19,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0414\u043e\u0431\u0440\u0438\u0447",
        "year": 2022
      },
      {
        "average_grade_stem": 4.25,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "year": 2017
      },
      {
        "average_grade_stem": 4.52,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "year": 2019
      },
      {
        "average_grade_stem": 4.37,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "year": 2020
      },
      {
        "average_grade_stem": 4.64,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "year": 2021
      },
      {
        "average_grade_stem": 3.47,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044a\u0440\u0434\u0436\u0430\u043b\u0438",
        "year": 2022
      },
      {
        "average_grade_stem": 4.46,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "year": 2017
      },
      {
        "average_grade_stem": 4.31,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "year": 2019
      },
      {
        "average_grade_stem": 4.7,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "year": 2020
      },
      {
        "average_grade_stem": 4.58,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "year": 2021
      },
      {
        "average_grade_stem": 3.91,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041a\u044e\u0441\u0442\u0435\u043d\u0434\u0438\u043b",
        "year": 2022
      },
      {
        "average_grade_stem": 4.59,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "year": 2017
      },
      {
        "average_grade_stem": 4.49,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "year": 2019
      },
      {
        "average_grade_stem": 4.25,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "year": 2020
      },
      {
        "average_grade_stem": 4.38,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "year": 2021
      },
      {
        "average_grade_stem": 3.79,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041b\u043e\u0432\u0435\u0447",
        "year": 2022
      },
      {
        "average_grade_stem": 4.51,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "year": 2017
      },
      {
        "average_grade_stem": 4.38,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "year": 2019
      },
      {
        "average_grade_stem": 4.41,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "year": 2020
      },
      {
        "average_grade_stem": 4.31,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "year": 2021
      },
      {
        "average_grade_stem": 3.84,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041c\u043e\u043d\u0442\u0430\u043d\u0430",
        "year": 2022
      },
      {
        "average_grade_stem": 4.51,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "year": 2017
      },
      {
        "average_grade_stem": 4.32,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "year": 2019
      },
      {
        "average_grade_stem": 4.38,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "year": 2020
      },
      {
        "average_grade_stem": 4.29,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "year": 2021
      },
      {
        "average_grade_stem": 3.5,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0430\u0437\u0430\u0440\u0434\u0436\u0438\u043a",
        "year": 2022
      },
      {
        "average_grade_stem": 4.78,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "year": 2017
      },
      {
        "average_grade_stem": 4.73,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "year": 2019
      },
      {
        "average_grade_stem": 4.64,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "year": 2020
      },
      {
        "average_grade_stem": 4.6,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "year": 2021
      },
      {
        "average_grade_stem": 3.75,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u0435\u0440\u043d\u0438\u043a",
        "year": 2022
      },
      {
        "average_grade_stem": 4.5,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "year": 2017
      },
      {
        "average_grade_stem": 4.45,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "year": 2019
      },
      {
        "average_grade_stem": 4.31,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "year": 2020
      },
      {
        "average_grade_stem": 4.27,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "year": 2021
      },
      {
        "average_grade_stem": 3.63,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u0435\u0432\u0435\u043d",
        "year": 2022
      },
      {
        "average_grade_stem": 4.39,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "year": 2017
      },
      {
        "average_grade_stem": 4.36,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "year": 2019
      },
      {
        "average_grade_stem": 4.41,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "year": 2020
      },
      {
        "average_grade_stem": 4.33,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "year": 2021
      },
      {
        "average_grade_stem": 3.69,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u041f\u043b\u043e\u0432\u0434\u0438\u0432",
        "year": 2022
      },
      {
        "average_grade_stem": 4.55,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "year": 2017
      },
      {
        "average_grade_stem": 4.46,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "year": 2019
      },
      {
        "average_grade_stem": 4.44,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "year": 2020
      },
      {
        "average_grade_stem": 4.42,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "year": 2021
      },
      {
        "average_grade_stem": 3.78,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0430\u0437\u0433\u0440\u0430\u0434",
        "year": 2022
      },
      {
        "average_grade_stem": 4.8,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "year": 2017
      },
      {
        "average_grade_stem": 4.62,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "year": 2019
      },
      {
        "average_grade_stem": 4.65,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "year": 2020
      },
      {
        "average_grade_stem": 4.49,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "year": 2021
      },
      {
        "average_grade_stem": 4.11,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0420\u0443\u0441\u0435",
        "year": 2022
      },
      {
        "average_grade_stem": 4.93,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "year": 2017
      },
      {
        "average_grade_stem": 4.72,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "year": 2019
      },
      {
        "average_grade_stem": 4.37,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "year": 2020
      },
      {
        "average_grade_stem": 4.59,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "year": 2021
      },
      {
        "average_grade_stem": 3.79,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0438\u043b\u0438\u0441\u0442\u0440\u0430",
        "year": 2022
      },
      {
        "average_grade_stem": 4.5,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "year": 2017
      },
      {
        "average_grade_stem": 4.5,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "year": 2019
      },
      {
        "average_grade_stem": 4.44,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "year": 2020
      },
      {
        "average_grade_stem": 4.3,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "year": 2021
      },
      {
        "average_grade_stem": 2.95,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043b\u0438\u0432\u0435\u043d",
        "year": 2022
      },
      {
        "average_grade_stem": 4.79,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "year": 2017
      },
      {
        "average_grade_stem": 4.88,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "year": 2019
      },
      {
        "average_grade_stem": 4.98,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "year": 2020
      },
      {
        "average_grade_stem": 4.83,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "year": 2021
      },
      {
        "average_grade_stem": 4.24,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043c\u043e\u043b\u044f\u043d",
        "year": 2022
      },
      {
        "average_grade_stem": 4.6,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "year": 2017
      },
      {
        "average_grade_stem": 4.64,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "year": 2019
      },
      {
        "average_grade_stem": 4.67,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "year": 2020
      },
      {
        "average_grade_stem": 4.61,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "year": 2021
      },
      {
        "average_grade_stem": 4.53,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u043e\u0444\u0438\u044f \u0413\u0440\u0430\u0434",
        "year": 2022
      },
      {
        "average_grade_stem": 4.52,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "year": 2017
      },
      {
        "average_grade_stem": 4.62,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "year": 2019
      },
      {
        "average_grade_stem": 4.53,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "year": 2020
      },
      {
        "average_grade_stem": 4.25,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "year": 2021
      },
      {
        "average_grade_stem": 4.23,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0421\u0442\u0430\u0440\u0430 \u0417\u0430\u0433\u043e\u0440\u0430",
        "year": 2022
      },
      {
        "average_grade_stem": 4.95,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "year": 2017
      },
      {
        "average_grade_stem": 4.82,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "year": 2019
      },
      {
        "average_grade_stem": 4.66,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "year": 2020
      },
      {
        "average_grade_stem": 4.9,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "year": 2021
      },
      {
        "average_grade_stem": 3.76,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0422\u044a\u0440\u0433\u043e\u0432\u0438\u0449\u0435",
        "year": 2022
      },
      {
        "average_grade_stem": 4.23,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "year": 2017
      },
      {
        "average_grade_stem": 4.3,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "year": 2019
      },
      {
        "average_grade_stem": 4.44,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "year": 2020
      },
      {
        "average_grade_stem": 4.06,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "year": 2021
      },
      {
        "average_grade_stem": 3.67,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0425\u0430\u0441\u043a\u043e\u0432\u043e",
        "year": 2022
      },
      {
        "average_grade_stem": 4.42,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "year": 2017
      },
      {
        "average_grade_stem": 4.18,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "year": 2019
      },
      {
        "average_grade_stem": 4.12,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "year": 2020
      },
      {
        "average_grade_stem": 4.13,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "year": 2021
      },
      {
        "average_grade_stem": 3.14,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u0428\u0443\u043c\u0435\u043d",
        "year": 2022
      },
      {
        "average_grade_stem": 4.55,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "year": 2017
      },
      {
        "average_grade_stem": 5.05,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "year": 2019
      },
      {
        "average_grade_stem": 4.92,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "year": 2020
      },
      {
        "average_grade_stem": 4.27,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "year": 2021
      },
      {
        "average_grade_stem": 3.93,
        "province": "\u041e\u0431\u043b\u0430\u0441\u0442 \u042f\u043c\u0431\u043e\u043b",
        "year": 2022
      },
      {
        "average_grade_stem": 4.27,
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "year": 2017
      },
      {
        "average_grade_stem": 4.42,
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "year": 2019
      },
      {
        "average_grade_stem": 4.53,
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "year": 2020
      },
      {
        "average_grade_stem": 4.34,
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "year": 2021
      },
      {
        "average_grade_stem": 3.29,
        "province": "\u0421\u043e\u0444\u0438\u0439\u0441\u043a\u0430 \u043e\u0431\u043b\u0430\u0441\u0442",
        "year": 2022
      },
      {
        "average_grade_stem": 4.01,
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "year": 2017
      },
      {
        "average_grade_stem": 3.65,
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "year": 2019
      },
      {
        "average_grade_stem": 3.46,
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "year": 2020
      },
      {
        "average_grade_stem": 3.51,
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "year": 2021
      },
      {
        "average_grade_stem": 2.52,
        "province": "\u0421\u0442\u043e\u043b\u0438\u0447\u043d\u0430 \u043e\u0431\u0449\u0438\u043d\u0430",
        "year": 2022
      }
    ]
  },
  "encoding": {
    "color": {
      "field": "year",
      "legend": {
        "title": "\u0413\u043e\u0434\u0438\u043d\u0430"
      },
      "scale": {
        "domain": [
          2019,
          2020,
          2021,
          2022
        ],
        "range": [
          "#FFAD01",
          "#EF5926",
          "#00923D",
          "#00A8BD"
        ]
      },
      "type": "nominal"
    },
    "tooltip": [
      {
        "field": "province",
        "type": "nominal"
      },
      {
        "field": "year",
        "type": "quantitative"
      },
      {
        "field": "average_grade_stem",
        "type": "quantitative"
      }
    ],
    "x": {
      "axis": {
        "title": "\u0421\u0440\u0435\u0434\u043d\u0430 \u043e\u0446\u0435\u043d\u043a\u0430 \u043e\u0442 \u043c\u0430\u0442\u0443\u0440\u0430 \u043f\u043e \u0421\u0422\u0415\u041c \u043f\u0440\u0435\u0434\u043c\u0435\u0442\u0438"
      },
      "field": "average_grade_stem",
      "scale": {
        "domain": [
          2,
          6
        ]
      },
      "type": "quantitative"
    },
    "y": {
      "axis": {
        "grid": true,
        "labelLimit": 450,
        "title": "\u041e\u0431\u043b\u0430\u0441\u0442"
      },
      "field": "province",
      "sort": "x",
      "type": "nominal"
    }
  },
  "height": {
    "step": 20
  },
  "mark": "point",
  "title": "\u0421\u0440\u0435\u0434\u043d\u0430 \u043e\u0446\u0435\u043d\u043a\u0430 \u043e\u0442 \u043c\u0430\u0442\u0443\u0440\u0430 \u043f\u043e \u0421\u0422\u0415\u041c \u043f\u0440\u0435\u0434\u043c\u0435\u0442\u0438 \u043f\u043e \u043e\u0431\u043b\u0430\u0441\u0442\u0438, \u0443\u0447\u0438\u043b\u0438\u0449\u0430, \u0440\u0430\u0437\u043b\u0438\u0447\u043d\u0438 \u043e\u0442 \u043f\u0440\u043e\u0444\u0435\u0441\u0438\u043e\u043d\u0430\u043b\u043d\u0438 (2019-2022)"
};

function init() {
    var containers = document.getElementsByClassName('chart-container');
    if (containers.length) {
        vlSpec6.width = containers[0].offsetWidth - 80;
    }

    vegaEmbed('#vis6', vlSpec6);
}

init();
window.addEventListener('resize', init);
</script>

*Бележки: Графиката представя средна оценка на ниво област от втора матура по СТЕМ предмет. При осредняването, стойностите на ниво училище са претеглени по броя ученици, явили се на втора матура по СТЕМ предмет.*

Освен намаляващия интерес, спадат и оценките от матура по СТЕМ предмети във всички области на страната. Докато за 2019-2021 средните оценки варират от 4.02 до 5.05 със средна оценка за страната за трите години от 4.48, то през 2022 в повечето области те са под 4 (от средно 2.95 в област Сливен до 4.53 в София - град) със средна за страната от 3.74. Сравнително запазване на средните оценки има в малко области, например София - град и Варна. Средното намаление между 2021 и 2022 по области е
67 стотни (0.67), а в Шумен, Добрич и Софийска област то е цяла една единица от шестобалната скала.

Общо броят на взелите матури в страната намалява. Интересът към СТЕМ изглежда също се понижава. Сред причините са както по-малкия брой завършващи, така и промяната в изпитния формат на матурите за дванадесетокласниците от професионалните и езиковите гимназии. Освен това, средният успех от втората матура по СТЕМ предмети също бележи спад през целия период и е най-нисък през 2022.

Остават и много въпроси за обществото ни: Кои други фактори, които не се съдържат в данните, допринасят за намаляващия интерес и успех по СТЕМ предметите? Може ли тази тенденция да се промени и как? Какви стъпки трябва да се предприемат? Отговорите ще са в основата на някои от посоките за развитие и промени в образователната система в България.

### За "Данни за добро"

"Данни за добро" подкрепя представителите на гражданския сектор, които работят за разрешаването на значими задачи в обществена полза, като предоставят знания и услуги свързани с обработка и анализ на данни.

### За "Образование без раници"

"Образование без раници" работи българските деца да имат най-добрите в света безплатни образователни ресурси и в подкрепа на всички, ангажирани
в образованието и в постигането на високи образователни успехи - учащите, учителите, семейството и всички други.

------------------------------------------------------------------------
[^1]: В този анализ използваме дефиниция на СТЕМ предметите, която включва предмеите биология, математика, физика и химия.

[^2]: ДЗИ = Държавен зрелостен изпит, често наричан матура

[^3]: БЕЛ = Български език и литература - съдържа въпроси по правилно ползване на езика и писане на анализ на творба

[^4]: [https://www.segabg.com/category-education/maturata-po-profesiya-stava-zadulzhitelna-dogodina](https://www.segabg.com/category-education/maturata-po-profesiya-stava-zadulzhitelna-dogodina)

[^5]: В рамките на анализа професионални са всички училища, чието име съдържа думата "Професионален/на"

[^6]: [https://www.segabg.com/category-education/dnes-e-izpitut-po-profesiya-za-blizo-13-000-zrelostnici](https://www.segabg.com/category-education/dnes-e-izpitut-po-profesiya-za-blizo-13-000-zrelostnici)

