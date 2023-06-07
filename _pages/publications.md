---
layout: page
permalink: /publications/
title: Publications
description: 
pubyears: [2022, 2021, 2020, 2019]
revyears: [2023]
nav: true
nav_order: 0
---
<!-- _pages/publications.md -->
## In Review
<div class="publications">
{%- for y in page.revyears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}} && keywords=review]*%}
{% endfor %}

</div>

## Published
<div class="publications">
{%- for y in page.pubyears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}} && keywords=publication]*%}
{% endfor %}

</div>
