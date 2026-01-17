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
* M.S. in Quantum Science and Technology, TUM&LMU, 2025-now
* B.S. in Physics, Hainan University, 2021-2025

Work experience
======
* Summer 2023: Teaching Assistant
  * Hainan University
  * Duties included: Exercises course on Mathematical Methods in Physics
  * Supervisor: Professor Yiqiang Du

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
