---
layout: default
title: Case studies
permalink: /case-studies/
---

{% for case_study in site.case_studies %}
  <h2><a href="{{ case_study.url }}">{{ case_study.title }}</a></h2>
  <p>{{ case_study.content | markdownify }}</p>
{% endfor %}
