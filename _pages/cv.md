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
* B.S. in Computer Science, Zhejiang Sci-Tech University, 2027 (expected)

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Programming Languages
  * C
  * C++
  * Python
* Mathematics
  * Calculus
  * Linear Algebra
* Physics
  * Mechanics

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams

# TEST
# **Maxwell Equations**
# $\nabla \cdot \vec{E} = \frac {ρ}{s} $
# $\nabla \cdot \vec{B} = 0$
# $\nabla \times \vec{E} = -\frac {\partial \vec{B}}{\partial t} $
# $\nabla \times \vec{B} = μ_0\vec{J}+μ_0ε_0\frac {\partial \vec{E}}{\partial t} $
