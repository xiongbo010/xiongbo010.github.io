---
layout: page
permalink: /research/
title: Research
years: [2024,2023,2022]
byears: [2024]
dyears: [2024]
tyears: [2023]
pyears: [2024,2023]
nav: true
sort_menu: 1
---

Humans understand the world by establishing entities, concepts, and their mutual connections. My research aims to understand human knowledge and teach machines to "understand" how the world is interconnected. 
To achieve this, I am conducting fundamental research in the following areas:


###### Machine learning on relational data

- **Learning on graph-structured data** [NeurIPS'22a,ACL'23,AAAI'24, CIKM'24]
- **Geometric representation learning** [NeurIPS'22a, NeurIPS'22b, KDD'22], e.g., exploiting data geometry for machine learning
- **Application** in healthcare and biomedicine, etc. [AMIA'24, SIGIR'23]


###### Neural & symbolic knowledge representation 

- **Knowledge graphs** [KDD'22, ACL'23, AAAI'24]: embedding, construction, and reasoning
- **Semantic web and ontologies** [ISWC'22, ISWC'23]: Description logic and ontology reasoning

###### Interpretable and reliable AI

- **Neuro-symbolic learning** [NeurIPS'22b, ISWC'22, ICDE'24]: imposing structure and knowledge in machine learning
- **Symbolic knowledge meets large language models** [NAACL'24, Arxiv'24]: combining structured knowledge with language models






<!-- ##### Neuro-symbolic learning -->



<br/>

### Selected Publications ([google scholar](https://scholar.google.com/citations?user=lmBXicIAAAAJ))

<br/>


#### Book Chapter 

<div class="publications">
<!-- {% for y in page.byears %} -->
  <div class="row m-0 p-0" style="border-top: 1px solid #ddd; flex-direction: row-reverse;">
    <div class="col-sm-1 mt-2 p-0 pr-1">
      <!-- <h3 class="bibliography-year">{{y}}</h3> -->
    </div>
    <div class="col-sm-11 p-0">
      {% bibliography -f book -q @*[year={{y}}]* %}
    </div>
  </div>
<!-- {% endfor %} -->
</div>

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


#### Peer-Reviewed Research Paper

<div class="publications">
<!-- {% for y in page.years %} -->
  <div class="row m-0 p-0" style="border-top: 1px solid #ddd; flex-direction: row-reverse;">
    <div class="col-sm-1 mt-2 p-0 pr-1">
      <h3 class="bibliography-year">{{y}}</h3>
    </div>
    <div class="col-sm-11 p-0">
      {% bibliography -f papers -q @*[year={{y}}]* %}
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

#### Dissertation

<div class="publications">
<!-- {% for y in page.dyears %} -->
  <div class="row m-0 p-0" style="border-top: 1px solid #ddd; flex-direction: row-reverse;">
    <div class="col-sm-1 mt-2 p-0 pr-1">
      <!-- <h3 class="bibliography-year">{{y}}</h3> -->
    </div>
    <div class="col-sm-11 p-0">
      {% bibliography -f thesis -q @*[year={{y}}]* %}
    </div>
  </div>
<!-- {% endfor %} -->
</div>



