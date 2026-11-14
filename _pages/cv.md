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
* Ph.D. Student, Aerospace Engineering, Indian Institute of Science, Bengaluru
* M.Tech., Aerospace Engineering, Indian Institute of Science, Bengaluru
* B.E., Aerospace Engineering, Punjab Engineering College, Chandigarh

Research Interests
======
* Computational and continuum mechanics
* Micromagnetics
* Fluid-structure interactions
* Biomechanics
* Parallel computing
* Flow instabilities

Professional Services
======
* Journal reviewer: [Physics of Fluids](https://aip.scitation.org/journal/phf)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Contact
======
* Email: krishnaagr (at) iisc (dot) ac (dot) in
