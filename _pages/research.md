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

<!-- My research lies at the intersection of machine learning and knowledge  -->

##### Machine learning 

- **Learning on graph-structured data** [NeurIPS'22a], e.g., graph neural networks
- **Geometric representation learning** [NeurIPS'22a, NeurIPS'22b, KDD'22], e.g., infusing geometric inductive biases into embeddings
- **Neuro-symbolic learning** [NeurIPS'22b]: infusing knowledge and structure into machine learning

##### Knowledge representation 

- **Knowledge bases/graphs** [KDD'22, ACL'23, WWW'22, AAAI'24]: embedding, construction, and reasoning
- **Semantic web and ontologies** [ISWC'22, ISWC'23]: Description Logic and ontology reasoning
- **Knowledge + language models** [SIGIR'23]: infusing knowledge into language models or vice versa




<!-- ##### Neuro-symbolic learning -->



<br/>

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


