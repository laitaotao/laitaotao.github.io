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
* Ph.D. in Computer Science and Technology, Xiamen University, 2016  
* M.S. in Computer Software and Theory, Xiamen University, 2009

Work experience
======
* Spring 2019 – Present: Lecturer  
  * Minjiang University  
  * Duties include: Teaching computer science courses, advising student research, and conducting research in robust
  * estimation and geometric model fitting.

* Spring 2017 – Spring 2019: Postdoctoral Research Fellow 
  * Fujian Agriculture and Forestry University  
  * Duties included: Research on multi-model fitting algorithms and participation in National Natural Science Foundation projects.
  
Research direction
======
* Computer Vision and Pattern Recognition
  
Patents
======
  <ul>{% for patent in site.patents reversed %}
  <li>
    {{ patent.authors | join: ", " }}. "{{ patent.title }}." 
    Chinese Patent {{ patent.patent_number }}.
  </li>
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

