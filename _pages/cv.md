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
* Ph.D. in Operations Research, Georgia Institute of Technology, 2026 (expected)
* M.S. in Operations Research, Georgia Institute of Technology
* B.Tech. (Honors) in Mechanical Engineering, Indian Institute of Technology Madras, 2016

Research Experience
======
* 2019 – Present: Graduate Research Assistant
  * Physical Internet Center, H. Milton Stewart School of Industrial and Systems Engineering
  * Georgia Institute of Technology, Atlanta, GA
  * Advisor: Professor Benoit Montreuil
  * Research on hyperconnected supply chain networks, demand disruption forecasting, demand-supply alignment, and autonomous distribution systems for critical products

Skills
======
* Operations Research
  * Stochastic modeling and simulation
  * Mathematical programming and optimization
* Machine Learning & Data Analytics
  * Demand forecasting and time-series analysis
  * Disruption signal detection
  * Data visualization and dashboard development
* Programming
  * Python
  * R

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
