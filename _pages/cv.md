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
* B.S. Psychology, Certificate in Psychology and Biology of Perception, Minor in Chemistry, Loyola University Chicago, 2004
* B.A. in French, Loyola University Chicago, 2004
* M.S. in Applied Human Perception and Performance, Loyola University Chicago, 2008

Work experience
======
* LOCATION - TIME: TITLE
  * Description 1
  * Description 2
  * Description 3
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
