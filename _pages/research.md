---
layout: page
permalink: /research/
title: Research
years: [2022,2021]
nav: true
sort_menu: 1
---
<!-- I worked on geometric representation learning over relational & structured data. In particular, I am working on the following two directions.

**Geometric representention learning** incorporates geometric inductive biases into the representation space such that the underlying symbolic semantics, logical rules/constraints, relational and structural patterns in knowledge graphs, etc. are respected in the form of geometric interpretations. e.g., hierarchical patterns can be preserved in hyperbolic space.

**Machine learning with prior symbolic knowledge**: Prior symbolic knowledge can be geometrically injected into the represententions to enhance the inference of machine learning models. Prominent examples include structured/hierarchical multilabel prediction and ontology-enhanced machine learning.  -->


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
