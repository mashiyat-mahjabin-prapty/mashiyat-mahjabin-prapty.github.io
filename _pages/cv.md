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
* B.Sc. Engineering in Computer Science and Engineering, 2024
* Higher Secondary School Certificate Examination, 2018 

<!-- Work experience
======
* Summer 2024: Research Intern
  * National University of Singapore
  * Duties includes: Updates and improvements to template
  * Supervisor: Professor Dr. Yang Zhang

* Summer 2023: Machine Learning Intern
  * e-SRD Lab, BUET and NWPGCL
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub -->

Work Experience
======
  <ul>{% for post in site.works reversed %}
    {% include archive-single-work-cv.html %}
  {% endfor %}</ul>

Skills
======
* Language: C, C++, Java, Python, R, JavaScript, 
* Assembly, SQL
* Database: Oracle, PostgreSQL
* Version Controller: (Git)
* Framework: React, ExpressJS, PyTorch, Tensorflow
* Machine Learning
* Deep Learning
* Natural Language Processing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Achievements
======
  <ul>{% for post in site.achievements reversed %}
    {% include archive-single-achievement-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
