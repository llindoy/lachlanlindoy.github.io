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
* Ph.D in Physical and Theoretical Chemistry, University of Oxford, 2020 
* B.Sc. (Advanced) (Honours), University of Sydney, 2015

Work experience
======
* June 2024: Senior Scientist
  * National Physical Laboratory

* January 2023: Higher Scientist
  * National Physical Laboratory

* January 2020: Postdoctoral Research Scientist
  * Columbia University
  * Supervisor: Professor David Reichman
  
Skills
======


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
  
