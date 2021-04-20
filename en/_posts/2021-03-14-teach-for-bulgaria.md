---
title: Teach for Bulgaria / Predicting teacher vacancies using sparse data
date: 2021-03-14 00:00:00
description: Teach for Bulgaria supports educational teams  and builds partnerships for the introduction of good practices in the education system in the country. We helped them predict future teacher vacancies using what sparse data was available.
featured_image: /assets/img/pages/school.jpg
author: Magdalena Petrova
lang: en
---

#### About Teach for Bulgaria

![](/assets/img/partner-logos/tfb/Zaedno_v_chas_EN-Logo_RGB_raster_transparency.png)

[Teach for Bulgaria](https://zaednovchas.bg/en/) work towards positive change in education in Bulgaria by recruiting, training, and developing new teachers, supports educational teams  and builds partnerships for the introduction of good practices in the education system in the country.


#### Background to the case
Although it is a non-governmental organization with high expertise and a holistic view of the education system in Bulgaria, the Teach for Bulgaria’s team was seeking an answer to the question of how many vacancies for teachers there will be per district and per subject  in the coming few years, and was trying to gain a better understanding of the factors influencing the demand for teachers.

Teach for Bulgaria needed that information in order to plan the recruitment of candidates for their leadership and professional development program so they can meet the demand for subject specialists in each district later on when the schools submit the  vacancies for teaching positions.

#### What we did?
##### Who worked on this and how long it took?

We, from Data for Good Bulgaria gathered a team of five volunteers - Andrew, Ivan, Magdalena, Nikola and Rumyana, each of whom established Data Scientists and/or Data Architects.
It took us 4 weeks to explore the data, analyse the problem and produce a prediction of the vacancies for teaching positions per subject and per district for the school years  2021-2022, 2022-2023, 2023-2024.

Our team crunched the data looking into two different hypotheses. On the one hand, we estimated the shortage of teachers, and on the other hand, calculated the number of teachers who will reach retirement age.

##### What was tricky in this project?
<img align="right" src="/assets/img/pages/what-we-did-Teach-for-Bulgaria-Data-for-Good-casestudy.PNG" width="400">In the process of analysing the data we encountered several problems. Although Teach for Bulgaria had comprehensive data, it was scattered. For example, one data set represented the number of teachers by subject, another the number of teachers by age, but none of them contained the number of teachers by subject and age that we needed in order to analyze the issue of teachers reaching retirement age. A separate difficulty was the presentation of the age of teachers as a range - we had the number of teachers aged 57-62 years, but we needed an exact age and gender to match that against the conditions for retirement age for teachers.

##### How did we solve the problem?
From the very beginning, Data for Good Bulgaria worked closely with Teach for Bulgaria and communicated our ideas for solving the problem. We discussed our approach and made sure we are on the right track.

We used tools such as Graph DB, Python and Jupyter for delivering the project, which included:
* Created a knowledge graph with educational data which served as a database allowing semantic modeling and harmonized unified data model.
* Analyzed the factors determining the demand for teachers, namely the number of students, birth rate and net enrollment rate in the education system
* Investigated factors determining the supply of teachers and the teachers to students ratio.
* Conducted an analysis of the current shortage of subject specialists
* Predicted the number of teachers who will reach retirement age by modeling the number of teachers by district, subject, age and gender by sampling based on assumptions for the respective distributions.
* The chosen approach allowed us to overcome the problem mentioned above.
* Calculated statistical error to assure Teach for Bulgaria of the reliability of the prediction.
* Documented the analysis process, which ensured reusability of the code in future analysis.
<br/><br/>
<p align="center">
<img src="/assets/img/pages/age-composition-of-teachers-in-Sofia-region-Teach-for-Bulgaria-Data-for-Good-casestudy.png"
     alt="Age composition of teachers in Sofia region Teach for Bulgaria & Data for Good casestudy"
     style="float: left; margin-right: 10px;" />
</p>

#### What was the result?
Data for Good Bulgaria provided free of charge the expertise and knowledge to Teach for Bulgaria, which received a reliable prediction of the number of teachers vacancies in each district of the country in the coming school years. That enabled Teach for Bulgaria to make data-driven decisions on the recruitment of candidates for their program and better plan their activities in short and mid-term, optimizing costs and maximizing impact.

For us, at Data for Good Bulgaria, this project was a valuable and purposeful experience.
