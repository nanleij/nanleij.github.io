---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<!-- <div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div> -->
<div class="publications">
 {% bibliography -f papers --group_by type %}
</div>

<!-- ## Talks
<h2 class="year">{2022}</h2>
 - ESI - Conference on Optimal Point Configurations (online) - A specialized SDP solver for sums-of-squares problems in discrete geometry - based on arXiv/2202.12077 -->
