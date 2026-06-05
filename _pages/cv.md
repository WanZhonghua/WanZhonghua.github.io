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
* Ph.D in Computer Science and Technology, Nanjing University of Science and Technology, 2029 (expected)
* M.S.Engineering in Pattern Recognition and Intelligent System, Nanjing University of Science and Technology, 2024-2025
* B.S.Engineering in Artificial Intelligence, Nanjing University of Chinese Medicine, 2020-2024
  
Skills
======
* CET-6
* Industrial Internet Platform Development (MIIT Certified, Level 2)
* Driver’s License: Class C1 (China)


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
  
