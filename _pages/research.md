---
layout: page
permalink: /research/
title: Research
years: [2022]
nav: true
sort_menu: 1
---
I worked on geometric representation learning over relational & structured data.

**Geometric representention learning** maps relational data into a low-dimensional geometric space that respects the underlying symbolic semantics,logical rules and structural/relational patterns, etc. 

**Machine learning with prior symbolic knowledge**: Prior symbolic knowledge can be **geometrically** injected into the  represententions to enhance the machine learning models.


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
