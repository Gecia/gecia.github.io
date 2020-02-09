---
layout: page
permalink: /publications/
title: Publications
description: <i>*denotes equal contribution.</i>
years: [2020,2019,2018]
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<!-- <i>*denotes equal contribution.</i> -->