---
title:  Дядото, внучката и липсващите идентификатори 
date: 2022-01-25 00:00:00
description: Една история за дядо, внуче, концентриран преференциален вот, липсващи идентификатори и сватба.     
featured_image: /img/posts/elections.png
authors: [ "nikola-tulechki" ]
categories: [ "democracy" ]
tags: []
draft: false
type: "blog"
---

Днес ще ви разкажем как за малко щяхме да се изложим и да обвиним неправилно хора в лъжа. 
 
Историята, освен интересна, защото се отнася до една от по-шарените части на българската електорална съвременност, 
е и поучителна, защото илюстрира колко е важно да се произвеждат еднозначни входни данни, 
каквито отворените данни на ЦИК за съжаление все още не са.  

Както знаете, заедно с нашите приятели от [Антикорупционния Фонд](https://acf.bg/bg/) много обичаме да се ровичкаме в изборни данни и
търсим статистически аномалии, които биха могли да са индикация за абнормално електорално поведение. 
Така, в рамките на рутинния ни вече анализ на третите парламентарни избори през 2021-ва година, 
изследвахме и случаите на концентрация на преференциален вот в малко на брой секции. 

Резултатът можете да видите в [този пост](https://acf.bg/bg/shampioni-po-preferentsii/).
Една от шампионките по преференции е г-жа Веселина Радославова, кандидат депутат на партия ДПС в МИР 26 София област.
Г-жа Радославова е спечелила внушителните 1151 преференции в малко на брой секции, което беше засечено от нашите статистически модели. 
За следващата част от историята е важно да се отбележи, че г-жа Радославова е внучка на г-н Александър Методиев, известен политик от ДПС в същия МИР. 

До тук добре. 

Няколко месеца по-късно, на 23.01.2022. Г-жа Радославова и г-н Методиев са гости в предаването
["Тази Събота и Неделя"](https://btvnovinite.bg/predavania/tazi-sabota-i-nedelia/aleksandar-metodiev-bat-sali-i-negovata-vnuchka-veselina.html)
по БТВ. 
Гледаме с интерес предаването.
От думите на гостите се разбира че интересът към политиката се предава през поколение. 
По-интересно обаче е, че на въпроса за спечелените преференции, дядото с увереност казва, че г-жа Радославова е спечелила **точно 1306** преференции. 
Не само това, но и че тя се е явява за трети път на избори. Това ни учудва, защото не отговаря на нашата представа и на числата, които сме извадили от данните. 
Нямаше как да не проверим това несъответствие. 

Тук стана интересно.

Използвайки [свързаните изборни данни](https://www.ontotext.com/blog/5-star-linked-open-elections-data/),
е лесно да се провери даден кандидат колко пъти се е явявал на избори.
[Тази заявка](https://elections.ontotext.com/sparql?name=&infer=true&sameAs=true&query=PREFIX%20my:%20%3Chttps:%2F%2Felections.ontotext.com%2Fresource%2Fentity%2F%3E%0APREFIX%20rdfs:%20%3Chttp:%2F%2Fwww.w3.org%2F2000%2F01%2Frdf-schema%23%3E%0APREFIX%20myd:%20%3Chttps:%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fdirect%2F%3E%0Aselect%20%3Fcandidate_uri%20%3Fcandidate_name%20%3Felection_label%20%3Felection_date%20%3Fcandidate_list_number%20%3Fparty_label%20%3Fparty_number%20where%20%7B%20%0A%09%3Fcandidate_uri%20a%20my:Candidate%20;%20rdfs:label%20%3Fcandidate_name%20;%20myd:candidacy%20%3Fel%20;%20myd:represents%20%3Fparty%20.%0A%20%20%20%20%3Fparty%20rdfs:label%20%3Fparty_label%20;%20myd:number%20%3Fparty_number.%20%0A%20%20%20%20optional%7B%3Fel%20rdfs:label%20%3Felection_label%20;%20myd:date%20%3Felection_date%7D%0A%20%20%20%20optional%7B%3Fcandidate_uri%20myd:number%20%3Fcandidate_list_number%7D%0A%20%20%20%20filter(contains(lcase(%3Fcandidate_name),%22%D0%B0%D0%BB%D0%B5%D0%BA%D1%81%D0%B0%D0%BD%D0%B4%D1%8A%D1%80%20%D1%85%D1%80%D0%B8%D1%81%D1%82%D0%BE%D0%B2%20%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%B8%D0%B5%D0%B2%22))%0A%7D%20order%20by%20desc(%3Felection_date)&execute)
например илюстрира кариерата на г-н Методиев и неговите шест отделни кандидатури за периода за който събираме данни. 
[Г-жа Радославова](https://elections.ontotext.com/sparql?name=&infer=true&sameAs=true&query=PREFIX%20my:%20%3Chttps:%2F%2Felections.ontotext.com%2Fresource%2Fentity%2F%3E%0APREFIX%20rdfs:%20%3Chttp:%2F%2Fwww.w3.org%2F2000%2F01%2Frdf-schema%23%3E%0APREFIX%20myd:%20%3Chttps:%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fdirect%2F%3E%0Aselect%20%3Fcandidate_uri%20%3Fcandidate_name%20%3Felection_label%20%3Felection_date%20%3Fcandidate_list_number%20%3Fparty_label%20%3Fparty_number%20where%20%7B%20%0A%09%3Fcandidate_uri%20a%20my:Candidate%20;%20rdfs:label%20%3Fcandidate_name%20;%20myd:candidacy%20%3Fel%20;%20myd:represents%20%3Fparty%20.%0A%20%20%20%20%3Fparty%20rdfs:label%20%3Fparty_label%20;%20myd:number%20%3Fparty_number.%20%0A%20%20%20%20optional%7B%3Fel%20rdfs:label%20%3Felection_label%20;%20myd:date%20%3Felection_date%7D%0A%20%20%20%20optional%7B%3Fcandidate_uri%20myd:number%20%3Fcandidate_list_number%7D%0A%20%20%20%20filter(contains(lcase(%3Fcandidate_name),%22%D0%B2%D0%B5%D1%81%D0%B5%D0%BB%D0%B8%D0%BD%D0%B0%20%D0%B8%D0%B2%D0%B0%D0%BD%D0%BE%D0%B2%D0%B0%20%D1%80%D0%B0%D0%B4%D0%BE%D1%81%D0%BB%D0%B0%D0%B2%D0%BE%D0%B2%D0%B0%22))%0A%7D%20order%20by%20desc(%3Felection_date)&execute)
обаче се появява само в една кандидатура - на изборите през ноември 2021-ва.

Този резултат отговаря на очакванията ни. Съмнението обаче остава, че все пак не може да се лъже в ефир за нещо толкова важно и лесно проверимо. 
Затова решихме все пак да хвърлим едно око на листите на ДПС за изборите 
[през месец април](https://elections.ontotext.com/sparql?name=%D0%9B%D0%B8%D1%81%D1%82%D0%B0%D1%82%D0%B0%20%D0%BD%D0%B0%20%D0%B4%D0%B0%D0%B4%D0%B5%D0%BD%D0%B0%20%D0%BF%D0%B0%D1%80%D1%82%D0%B8%D1%8F%20%D0%B7%D0%B0%20%D0%B4%D0%B0%D0%B4%D0%B5%D0%BD%20%D0%B8%D0%B7%D0%B1%D0%BE%D1%80&infer=true&sameAs=true&query=BASE%20%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2F%3E%0APREFIX%20my%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fentity%2F%3E%0APREFIX%20rdfs%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2F2000%2F01%2Frdf-schema%23%3E%0APREFIX%20wd%3A%20%3Chttp%3A%2F%2Fwww.wikidata.org%2Fentity%2F%3E%0APREFIX%20myd%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fdirect%2F%3E%0APREFIX%20election%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Felection%2F%3E%0Aselect%20%3Fcandidate%20%3FcandNumber%20%3Fname%20%3FlocalParty%20%3FlocalPartyLabel%20%3FlocalPartyNumber%20%3FlocalEl%20%3FlocalElLabel%20where%20%7B%20%0A%0A%20%20%20%20bind(wd%3AQ164242%20as%20%3Fparty)%20%23DPS%0A%20%20%20%20%23bind(wd%3AQ792527%20as%20%3Fparty)%20%23VMRO%0A%20%20%20%20%0A%23%20%20%20%20bind(%3Celection%2Fmi2015%2Fos%2F1910%3E%20as%20%3FlocalEl)%20%23%22%D0%9C%D0%B5%D1%81%D1%82%D0%BD%D0%B8%20%D0%98%D0%B7%D0%B1%D0%BE%D1%80%D0%B8%202015%20%D0%B7%D0%B0%20%D0%BE%D0%B1%D1%89%D0%B8%D0%BD%D1%81%D0%BA%D0%B8%20%D1%81%D1%8A%D0%B2%D0%B5%D1%82%201910.%20%D0%94%D1%83%D0%BB%D0%BE%D0%B2%D0%BE%22%0A%20%20%20%20bind(%3Celection%2Fpi2021%2F26%3E%20as%20%3FlocalEl)%20%23%22%D0%98%D0%B7%D0%B1%D0%BE%D1%80%D0%B8%20%D0%B7%D0%B0%20%D0%9F%D0%B0%D1%80%D0%BB%D0%B0%D0%BC%D0%B5%D0%BD%D1%82%20%D0%BD%D0%B0%20%D0%A0%D0%91%20%D0%9C%D0%98%D0%A0%20%2024.%20%D0%A1%D0%9E%D0%A4%D0%98%D0%AF%2024%20%D0%9C%D0%98%D0%A0%22%0A%23%20%20%20%20bind(%3Celection%2Fep2019%3E%20as%20%3FlocalEl)%20%23%22%D0%98%D0%B7%D0%B1%D0%BE%D1%80%D0%B8%20%D0%B7%D0%B0%20%D0%95%D0%B2%D1%80%D0%BE%D0%BF%D0%B5%D0%B9%D1%81%D0%BA%D0%B8%20%D0%9F%D0%B0%D1%80%D0%BB%D0%B0%D0%BC%D0%B5%D0%BD%D1%82%202019%22%0A%20%20%20%20%0A%20%20%20%20%3FlocalParty%20%20myd%3Aparty%2B%20%3Fparty%20%3B%20rdfs%3Alabel%20%3FlocalPartyLabel%20%3B%20myd%3Anumber%20%3FlocalPartyNumber%20%3B%20myd%3Acandidacy%20%3FlocalEl%20.%0A%20%20%20%20%3Fcandidate%20a%20my%3ACandidate%20%3B%20myd%3Arepresents%20%3FlocalParty%20%20%3B%20rdfs%3Alabel%20%3Fname%20%3B%20myd%3Anumber%20%3FcandNumber%20.%0A%20%20%20%20%0A%20%20%20%20%3FlocalEl%20rdfs%3Alabel%20%3FlocalElLabel%20.%0A%7D%20order%20by%20%3FcandNumber%20&execute)
и 
[през месец юли](https://elections.ontotext.com/sparql?name=%D0%9B%D0%B8%D1%81%D1%82%D0%B0%D1%82%D0%B0%20%D0%BD%D0%B0%20%D0%B4%D0%B0%D0%B4%D0%B5%D0%BD%D0%B0%20%D0%BF%D0%B0%D1%80%D1%82%D0%B8%D1%8F%20%D0%B7%D0%B0%20%D0%B4%D0%B0%D0%B4%D0%B5%D0%BD%20%D0%B8%D0%B7%D0%B1%D0%BE%D1%80&infer=true&sameAs=true&query=BASE%20%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2F%3E%0APREFIX%20my%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fentity%2F%3E%0APREFIX%20rdfs%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2F2000%2F01%2Frdf-schema%23%3E%0APREFIX%20wd%3A%20%3Chttp%3A%2F%2Fwww.wikidata.org%2Fentity%2F%3E%0APREFIX%20myd%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fdirect%2F%3E%0APREFIX%20election%3A%20%3Chttps%3A%2F%2Felections.ontotext.com%2Fresource%2Felection%2F%3E%0Aselect%20%3Fcandidate%20%3FcandNumber%20%3Fname%20%3FlocalParty%20%3FlocalPartyLabel%20%3FlocalPartyNumber%20%3FlocalEl%20%3FlocalElLabel%20where%20%7B%20%0A%0A%20%20%20%20bind(wd%3AQ164242%20as%20%3Fparty)%20%23DPS%0A%20%20%20%20%23bind(wd%3AQ792527%20as%20%3Fparty)%20%23VMRO%0A%20%20%20%20%0A%23%20%20%20%20bind(%3Celection%2Fmi2015%2Fos%2F1910%3E%20as%20%3FlocalEl)%20%23%22%D0%9C%D0%B5%D1%81%D1%82%D0%BD%D0%B8%20%D0%98%D0%B7%D0%B1%D0%BE%D1%80%D0%B8%202015%20%D0%B7%D0%B0%20%D0%BE%D0%B1%D1%89%D0%B8%D0%BD%D1%81%D0%BA%D0%B8%20%D1%81%D1%8A%D0%B2%D0%B5%D1%82%201910.%20%D0%94%D1%83%D0%BB%D0%BE%D0%B2%D0%BE%22%0A%20%20%20%20bind(%3Celection%2Fpi2021_07%2F26%3E%20as%20%3FlocalEl)%20%23%22%D0%98%D0%B7%D0%B1%D0%BE%D1%80%D0%B8%20%D0%B7%D0%B0%20%D0%9F%D0%B0%D1%80%D0%BB%D0%B0%D0%BC%D0%B5%D0%BD%D1%82%20%D0%BD%D0%B0%20%D0%A0%D0%91%20%D0%9C%D0%98%D0%A0%20%2024.%20%D0%A1%D0%9E%D0%A4%D0%98%D0%AF%2024%20%D0%9C%D0%98%D0%A0%22%0A%23%20%20%20%20bind(%3Celection%2Fep2019%3E%20as%20%3FlocalEl)%20%23%22%D0%98%D0%B7%D0%B1%D0%BE%D1%80%D0%B8%20%D0%B7%D0%B0%20%D0%95%D0%B2%D1%80%D0%BE%D0%BF%D0%B5%D0%B9%D1%81%D0%BA%D0%B8%20%D0%9F%D0%B0%D1%80%D0%BB%D0%B0%D0%BC%D0%B5%D0%BD%D1%82%202019%22%0A%20%20%20%20%0A%20%20%20%20%3FlocalParty%20%20myd%3Aparty%2B%20%3Fparty%20%3B%20rdfs%3Alabel%20%3FlocalPartyLabel%20%3B%20myd%3Anumber%20%3FlocalPartyNumber%20%3B%20myd%3Acandidacy%20%3FlocalEl%20.%0A%20%20%20%20%3Fcandidate%20a%20my%3ACandidate%20%3B%20myd%3Arepresents%20%3FlocalParty%20%20%3B%20rdfs%3Alabel%20%3Fname%20%3B%20myd%3Anumber%20%3FcandNumber%20.%0A%20%20%20%20%0A%20%20%20%20%3FlocalEl%20rdfs%3Alabel%20%3FlocalElLabel%20.%0A%7D%20order%20by%20%3FcandNumber%20&execute)
за МИР 26. Внимателен анализ на имената в листите ни даде и липсващото парче от този електорален пъзел.

Кандидат с имена "Веселина Иванова Василева" се е явявала съответно на 6-то място през април и на 7-мо място през юли.
Очевидно е и какво е причинило липсата в данните, а именно, че в някой щастлив момент между юли и ноември, г-ца Василева се е омъжила и е вече г-жа Радославова.  

Сега вече с можем да сметнем с [тази заявка](https://elections.ontotext.com/sparql?name=&infer=true&sameAs=true&query=PREFIX%20my:%20%3Chttps:%2F%2Felections.ontotext.com%2Fresource%2Fentity%2F%3E%0APREFIX%20rdfs:%20%3Chttp:%2F%2Fwww.w3.org%2F2000%2F01%2Frdf-schema%23%3E%0APREFIX%20myd:%20%3Chttps:%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fdirect%2F%3E%0APREFIX%20myp:%20%3Chttps:%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Findirect%2F%3E%0APREFIX%20myps:%20%3Chttps:%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fstatement%2F%3E%0APREFIX%20mypq:%20%3Chttps:%2F%2Felections.ontotext.com%2Fresource%2Fprop%2Fqualifier%2F%3E%0Aselect%0A(sum(%3Fpref)%20as%20%3Fsum)%20%0A%7B%0A%09%0A%20%20%20%20%7Bselect%20*%20where%20%7B%20%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Fcand%20a%20my:Candidate%20;%20rdfs:label%20%3Flab%20;%20myd:candidacy%20%3Fel%20.%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Fel%20myd:main_election%2Fmyd:type%20%22parliamentary%22%0A%20%20%20%20%20%20%20%20%20%20%20%20optional%7B%3Fel%20rdfs:label%20%3FelLabel%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20filter(contains(lcase(%3Flab),%22%D0%B2%D0%B5%D1%81%D0%B5%D0%BB%D0%B8%D0%BD%D0%B0%20%D0%B8%D0%B2%D0%B0%D0%BD%D0%BE%D0%B2%D0%B0%20%D1%80%D0%B0%D0%B4%D0%BE%D1%81%D0%BB%D0%B0%D0%B2%D0%BE%D0%B2%D0%B0%22)%20%7C%7C%0A%20%20%20%20%20%20%20%20%20%20%20%20contains(lcase(%3Flab),%22%D0%B2%D0%B5%D1%81%D0%B5%D0%BB%D0%B8%D0%BD%D0%B0%20%D0%B8%D0%B2%D0%B0%D0%BD%D0%BE%D0%B2%D0%B0%20%D0%B2%D0%B0%D1%81%D0%B8%D0%BB%D0%B5%D0%B2%D0%B0%22))%0A%20%20%20%20%7D%7D%0A%20%20%20%20%3Fvoting%20myp:preference_vote%20%3Fpv%20;%20myd:election%20%3Fel.%0A%20%20%20%20%3Fpv%20myps:preference_vote%20%3Fcand%20;%20mypq:valid_votes_recieved%20%3Fpref%20.%0A%7D%20&execute)
сборът преференции, 1303, който и отговаря на споделеното от г-н Методиев число.


**Изводът от всичко това е, че 3-те имена са крайно недостатъчни за идентификация на кандидатите в данните, които ЦИК споделят.**

Не за първи път го казваме, [тук](https://github.com/nikolatulechki/semanticElections/tree/master/analysis/cand-id)
сме описали и други случаи, в които трите имена водят до многозначие и невъзможност да се проследи траекторията на отделните кандидати.
Решението е просто. Ако искам да имаме наистина качествени данни  трябва отделните кандидати да са идентифицирани посредством уникален идентифиркатор
(например базиран на ЕГН), който да се споделя като част от отворените данни на ЦИК и да не се променя между отделни избори. 
