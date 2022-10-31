---
layout: page
permalink: /research/
title: Research
years: [2022]
nav: true
sort_menu: 1
---
My research interests focus on machine learning on relational data. In particular, geometric representation learning over relational & structured data.

**Geometric representention learning** maps relational data into low-dimensional geometric space that respects the underlying symbolic semantics,logical rules and structural/relational patterns, etc. Prior logical/symbolic knowledge can be then injected into the geometric embeddings to enhance machine learning models.

### Selected Publications ([google scholar](https://scholar.google.com/citations?user=lmBXicIAAAAJ))

<div class="publications">

<br/>
{% for y in page.years %}
  <div class="row m-0 p-0" style="border-top: 1px solid #ddd; flex-direction: row-reverse;">
    <div class="col-sm-1 mt-2 p-0 pr-1">
      <h3 class="bibliography-year">{{y}}</h3>
    </div>
    <div class="col-sm-11 p-0">
      {% bibliography -f papers -q @*[year={{y}}]* %}
    </div>
  </div>
{% endfor %}
