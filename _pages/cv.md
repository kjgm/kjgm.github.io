---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D on Algorithms for and Application of Optimal Decision Trees, Delft University of Technology, 2026 (expected)
  * Supervisors: Mathijs de Weerdt, Emir Demirović
* M.A. in Theology and Religious Studies, Evangelical Theological Faculty Leuven, ongoing
* M.S. in Computer Science, Delft University of Technology, 2017
  * Specialization: Algorithms
  * Master Thesis: [Decision diagrams for decomposed mixed integer linear programs](https://kjgm.github.io/publication/2017_master_thesis)
* B.S. in Computer Science, Delft University of Technology, 2014

Work experience
======
* Scientific Programmer (2017-2021)
  * Delft University of Technology
  * Project 1: Future proof flexible charging (URSES+)
  * Project 2: Logistics of rostering with the Dutch Railways (NS) 

* Student Coach
  * Navigators
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Software
======
  <ul>{% for post in site.software reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
    
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>