---
layout: page
permalink: /research/
title: Research
years: [2024,2023,2022]
tyears: [2023]
pyears: [2024,2023]
nav: true
sort_menu: 1
---

### Research Interests

Humans understand the world by establishing entities, concepts, and their mutual connections. 
My research aims to understand human knowledge and teach machines to "understand" how the world is interconnected. 
To achieve this, I am conducting fundamental research in two primary areas:

###### Machine learning for structured/relational data

- **Learning on graph-structured data** [NeurIPS'22a,ACL'23,AAAI'24]
- **Neuro-symbolic learning** [NeurIPS'22b, ISWC'22, ICDE'24]: imposing structure and knowledge in machine learning
- **Geometric representation learning** [NeurIPS'22a, NeurIPS'22b, KDD'22], e.g., exploiting data geometry for machine learning

###### Neural & symbolic knowledge representation 

- **Knowledge graphs** [KDD'22, ACL'23, AAAI'24]: embedding, construction, and reasoning
- **Semantic web and ontologies** [ISWC'22, ISWC'23]: Description logic and ontology reasoning
- **Symbolic knowledge meets large language models** [NAACL'24, Arxiv'24]: combining structured knowledge with language models
- **Applications**: healthcare, biomedicine, etc. 




<!-- ##### Neuro-symbolic learning -->



<br/>

### Selected Publications ([google scholar](https://scholar.google.com/citations?user=lmBXicIAAAAJ))

<br/>


#### Tutorial
<div class="publications">
<!-- <br/> -->
<!-- {% for y in page.tyears %} -->
  <div class="row m-0 p-0" style="border-top: 1px solid #ddd; flex-direction: row-reverse;">
    <div class="col-sm-1 mt-2 p-0 pr-1">
      <!-- <h3 class="bibliography-year">{{y}}</h3> -->
    </div>
    <div class="col-sm-11 p-0">
      {% bibliography -f tutorial -q @*[year={{y}}]* %}
    </div>
  </div>
<!-- {% endfor %} -->
</div>

#### Preprint 

<div class="publications">
<!-- {% for y in page.pyears %} -->
  <div class="row m-0 p-0" style="border-top: 1px solid #ddd; flex-direction: row-reverse;">
    <div class="col-sm-1 mt-2 p-0 pr-1">
      <!-- <h3 class="bibliography-year">{{y}}</h3> -->
    </div>
    <div class="col-sm-11 p-0">
      {% bibliography -f preprint -q @*[year={{y}}]* %}
    </div>
  </div>
<!-- {% endfor %} -->
</div>

#### Conference & Journal

<div class="publications">
<!-- {% for y in page.years %} -->
  <div class="row m-0 p-0" style="border-top: 1px solid #ddd; flex-direction: row-reverse;">
    <div class="col-sm-1 mt-2 p-0 pr-1">
      <!-- <h3 class="bibliography-year">{{y}}</h3> -->
    </div>
    <div class="col-sm-11 p-0">
      {% bibliography -f papers -q @*[year={{y}}]* %}
    </div>
  </div>
<!-- {% endfor %} -->
</div>






