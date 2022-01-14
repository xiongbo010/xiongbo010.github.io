---
layout: page
permalink: /research/
title: Research
years: [2021, 2020, 2019]
nav: true
---
My research interests span a wide array of topics around graph neural networks. Rather than focusing on a particular niche, I like to constantly look for new interesting and impactful problems. Some of the problems in graph neural networks that have caught my interest so far are:
- **Scalability**: How do we scale GNNs to billion nodes graphs?
- **Dynamic Graphs**: How do we learn on graphs that change over time? 
- **Missing Node Features**: How do apply GNNs to graphs where we only observe only a subset of features for each node (which is almost always the case in practice)?
- **Low Homophily Graphs**: How do we design GNNs that work on graphs with low label homophily (where neighbors tend to have different labels)

### Publications
Below is a list of my publications in reversed chronological order. 

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
