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
* **D.Phil. in Economics** (2022–Present)  
  University of Oxford — Computational Economics Lab

* **B.A.** (2018–2022)  
  Trinity College Dublin  
  *Foundation Scholarship*

Research Experience
======
* **Research Intern** (June 2024 – September 2024)  
  Bank of England

* **Research Intern** (June 2023 – August 2023)  
  Microsoft Research New England

Skills
======
* Auction Theory and Mechanism Design
* Agent-Based Macroeconomic Models
* Algorithmic Game Theory
* Computational Economics
* Market Design

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
