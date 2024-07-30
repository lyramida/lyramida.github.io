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
* B.S. in Mathematics, University of Science and Technology of China, 2026(expected)
* Suzhou High School of Jiangsu Province 江苏省苏州中学校 毕业
  
Skills
======
* LaTeX
* C programming
* Mathematica(beginner)

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
TA
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
