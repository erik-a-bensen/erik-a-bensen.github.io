---
layout: page
permalink: /presentations/
title: Presentations
description: 
years: [2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}} && keywords=presentation]*%}
{% endfor %}

</div>