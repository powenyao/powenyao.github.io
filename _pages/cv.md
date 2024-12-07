---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

Download <a href="/files/powen-yao-resume.pdf" download>
<i class="fas fa-fw fa-file-pdf" aria-hidden="true">
</i>Current Resume</a>

{% include base_path %}

Education
======

* Ph.D. in Computer Science, 2024 @ University of Southern California
  * Dissertation:
    <a href="/publication/2024-01-26-phd">
    <i class="fas fa-fw fa-arrow-right" aria-hidden="true">
    </i>Design Lenses for Extended Reality</a>
* M.S. in Computer Science, 2012 @ University of Southern California
* B.S. in Electrical Engineering, 2010 @ University of California, Irvine
  * Senior Project: Video Game Exercise Machine Project

Work experience
======

* Current: XR Advisor for the Medical VR team
  at [Easley-Dunn Productions](https://easleydunnproductions.com/temp_index.html)
* 2019-2023: Teaching Assistant for the AR/VR/MR course and Mobile Games course
    * AR/VR/MR: Equipment Manager and Student Team Advisor
    * Mobile Games: Restructured course & Introduced new Lectures focused on Innovation.
* 2017-2018: Substitute Military Service @ [Tourism Bureau](https://eng.taiwan.net.tw/) - Planning and Research Division
    * Served in the mandatory Substitute Military Service for the Republic of China
* 2012-2017: Teaching Assistant & GamePipe Lab Manager
    * Teaching Assistant for Networked Games, Networked Artificial Intelligence
    * Teaching Assistant for Advanced Game Projects (2012-2014), Mobile Games (2015-2017)
* 2012: Student Researcher @ USC - [Information Sciences Institute](https://www.isi.edu/)
    * Worked as the lead programmer and UI designer on [SEAVAK](https://youtu.be/45TnvCuu9l0): a multi-user data
      visualization & simulation tool designed for intelligence analysts
* Summer 2011: Student Researcher @ USC - [GamePipe Lab](https://mikezyda.com/USCGamePipe/)
    * Worked on AI on [Cosmopolis](https://youtu.be/FSWAgmOD8q4), a Massively Multiplayer Online Game, for game research
      at USC. Implemented a navigation mesh for AI terrain traversal and behavior trees for AI behavior

Publications
======
[Google Scholar Link](https://scholar.google.com/citations?user=BlSIZ14AAAAJ&hl=en)
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
