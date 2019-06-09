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
* B.E. in Electronics and Instrumentation, SJCE Mysore, 2014
* M.S. in Control Theory and Applications, Indian Institute of Technology Kanpur, 2019
* Ph.D in Control Theory and Applications, Indian Institute of Technology Kanpur, 2020 (expected)

Work experience
======
* Summer 2013: Intern
  * Instrumentation and Applied Physics, Indian Institute of Science, Bangalore
  * Duties included: Improving SNR of an Atomic Force Microscope
  * Supervisor: Dr. G. R. Jayanth
  
Skills
======
* Mathematical modeling
* Control Design
  * Linear, loop-shaping based design
  * Nonlinear Lyapunov-based design
  * Robust and adaptive control design
* Autopilot development
  * PX4
  * Ardupilot
* ROS, Matlab, Simulink, C++

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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
