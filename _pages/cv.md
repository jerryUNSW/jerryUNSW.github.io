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
* Ph.D in Computer Science, University of New South Wales (UNSW), 2022-Present
  * Supervisors: Scientia Prof. Xuemin Lin, Prof. Wenjie Zhang
  * Research Group: Data and Knowledge Research Group
  * Focus: Graph algorithms, differential privacy, cohesive subgraph computation

Research Interests
======
* Cohesive subgraph computation
* Motif counting
* Differential privacy
* Graph algorithms
* Large-scale data analysis

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
