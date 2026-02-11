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
* DPhil in Statistics, University of Oxford, 2026 (submitted)
* MMath in Mathematics and Statistics, University of Oxford, 2020

Work experience
======
* Jan-Apr 2025: Statistical Intern
  * Oxford University Statistical Consulting
  * Statistical advice for clients, reports in Rmarkdown
  * Trained staff in GitHub and developed plan to migrate unit's code to GitHub.

* Aug 2020 - Sep 2021: Statistician
  * Oxford Vaccine Group, University of Oxford
  * Worked on COVID-19 vaccine trials
  
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

