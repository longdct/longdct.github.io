---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- Education
====== -->
<h2 style="color:#87CEEB">Education</h2>
* Ph.D in Computer Science, George Mason University, 2022 - present
  * Advisor: Prof. ThanhVu Nguyen
* B.E. in Information Technology, Hanoi University of Science and Technology, 2021
  * Thesis: <i>TF-GeneNAS: An evolution-based training-free approach to Neural Architecture Search</i>
  * Thesis Advisor: Prof. Huynh Thi Thanh Binh

<!-- Research experience
====== -->
<h2 style="color:#87CEEB">Research Experience</h2>
* AI Resident, [<i>VinAI Research</i>](https://vinai.io/), 2020 - 2022
  * Mentor: Dr. Dat Quoc Nguyen
  * Research topic: Vietnamese-English machine translation

* Research Student, <i>Modelling, Simulation & Optimization Laboratory</i>, 2018 - 2021
  * Supervisor: Prof. Huynh Thi Thanh Binh
  * Research topic: Combining Evolutionary Algorithms and Deep Learning for solving combinatorial optimization problems

<!-- Publications
====== -->
<h2 style="color:#87CEEB">Publications</h2>
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
====== -->
<h2 style="color:#87CEEB">Talks</h2>
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
====== -->
<h2 style="color:#87CEEB">Teaching</h2>
  * Graduate Teaching Assistant, George Mason University
    * CS 211: Object-Oriented Programming
    * CS 580: Introduction to Artificial Intelligence
    * CS 584: Data Mining
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
