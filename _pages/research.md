---
layout: page
permalink: /research/
title: Research
years: [2024,2023,2022]
tyears: [2023]
nav: true
sort_menu: 1
---

### Research Interests

My research lies at the intersection of machine learning and knowledge representation

##### Machine Learning 

- **Machine learning on graphs [NeurIPS'22a, NeurIPS'22b]**, including graph neural networks and their applications 
- **Geometric representation learning [NeurIPS'22b, KDD'22, ICDE'24, ACL-findings'22]**, e.g., hyperbolic embeddings
- **Large language models (LLMs)** and its applications in reasoning

##### Knowledge Representation

- **Knowledge Graphs [KDD'22, ACL'23, SIGIR'23, WWW'22, ISWC'22, AAAI'24]**, including embeddings, construction, and reasoning
- **Semantic Web and Ontologies [ISWC'22, ISWC'23]**, e.g., Description Logic and ontology embeddings

### Selected Publications ([google scholar](https://scholar.google.com/citations?user=lmBXicIAAAAJ))

<br/>

#### Tutorial
<div class="publications">
<!-- <br/> -->
{% for y in page.tyears %}
  <div class="row m-0 p-0" style="border-top: 1px solid #ddd; flex-direction: row-reverse;">
    <div class="col-sm-1 mt-2 p-0 pr-1">
      <h3 class="bibliography-year">{{y}}</h3>
    </div>
    <div class="col-sm-11 p-0">
      {% bibliography -f tutorial -q @*[year={{y}}]* %}
    </div>
  </div>
{% endfor %}
</div>

#### Conference 

<div class="publications">
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
</div>
