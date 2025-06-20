---
title: Данни за матурите - дашборд
date: 2025-05-24 00:00:00
description: Дашборд с данни за представянето на матурите през годините
featured_image:
authors: [ "ognyana-hristova", "kosara-keskinova","vitali-baruh" ]
categories: [ "education" ]
tags: []
lang: bg
draft: false
type: "blog"
---

Данните за представянето на държавните зрелостни изпити след 12ти клас, познати като 'матури', са публично достъпни и често анализирани от организации в сферата на образованието, медии и родители-ентусиасти. Въпреки достъпността им обаче те не са във вид удобен за по-задълбочени анализи, най-вече заради това, че почти всяка година търпят малки промени.

От "Данни за добро" създадохме база от данни за матурите и интерактивен дашборд към нея. Дашбордът показва данните на различни нива (национално, общинско, училищно) и позволява да се правят сравнения между различни места и години.

Дашбордът е достъпен на този [линк](https://dashboards.data-for-good.bg/eddata/)!

[![Данни за матурите](/img/posts/2025-05-24-dashboard-maturi/map.png)](https://dashboards.data-for-good.bg/eddata/)

Въпросите, на които търсим отговор, включват:
* Кои са добрите примери сред училищата и общините извън "елитните гимназии" в големите населени места?
* Има ли промени или тенденции през годините, които заслужават вниманието ни?

## За данните

Данните за броя явили се и средните оценки от матури по училища са налични година по година на [Портала за отворени данни](https://data.egov.bg/).

Другият източник на данни, който сме използвали за географска информация като идентификатор и адрес на училище, населено място, област и община, е [Уикиданни](https://www.wikidata.org/wiki/Wikidata:WikiProject_Bulgaria/Administrative_Entities).

В подготовка на базата, тези данни са съединени, изчистени от несъответствия (например промени в имената на предметите през годините) и организирани в няколко таблици.

## За дашборда

Анализът на данните започва от най-високото ниво - национално, през регионално (област и община) и стига до най-ниското - училище. Данните са показани за всички налични години или с филтър за избиране на определена година.

Предметите за втора матура са групирани в четири категории - СТЕМ, Чужди езици, Дипломни проекти и Други. Защо се фокусираме върху СТЕМ предмети можете да прочетете в наш предишен анализ [тук](https://data-for-good.bg/posts/2022-12-23-stem-maturi-2021/).

Техническото изпълненние на дашборда е дело на [Витали Барух](https://data-for-good.bg/authors/vitali-baruh/). Дизайнът е от [Косара Кескинова](https://data-for-good.bg/authors/kosara-keskinova/).