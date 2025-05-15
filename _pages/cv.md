---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<h2>🎓 Education</h2>
<ul class="clean-list">
  <li><strong>Ph.D in Scientific Computing</strong>, Uppsala University — <em>Expected 2028</em></li>
  <li><strong>M.S. in Advanced Computing Science</strong>, Tsinghua University — 2019</li>
  <li><strong>B.E. in Software Engineering</strong>, NUST — 2015</li>
</ul>

<h2>💼 Work Experience</h2>
<ul class="clean-list">
  <li>
    <strong>Freelance Developer</strong> <br>
    <em>Dec 2021 – Dec 2022</em>, Freelancer.com<br>
    Delivered over 50 projects in CV, ML, automation, scraping, and backend. Top 1% freelancer by performance.
  </li>
  <li>
    <strong>Software Engineer</strong><br>
    <em>Oct 2015 – Aug 2017</em>, NETSOL Technologies Inc.<br>
    R&D of financial applications. Supervisor: <a href="https://www.linkedin.com/in/naveed-shahid-08429514/" target="_blank">Naveed Shahid</a>.
  </li>
  <li>
    <strong>Intern</strong><br>
    <em>Mar 2014 – May 2014</em>, Microsoft Pakistan Chapter<br>
    Developed Windows-based mobile apps.
  </li>
</ul>

<h2>🛠️ Skills</h2>
<ul class="clean-list">
  <li><strong>Languages:</strong> C, C++, Python, Java, VB.NET</li>
  <li><strong>Systems:</strong> Distributed Systems</li>
  <li><strong>ML:</strong> Federated Learning, Adversarial Networks</li>
  <li><strong>Tools:</strong> TensorFlow, PyTorch, Docker</li>
  <li><strong>Other:</strong> Data scraping, Automation, Backend</li>
</ul>

<h2>📚 Publications</h2>
<ul class="clean-list">
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>


<h2>🎤 Talks</h2>
<ul class="clean-list">
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
</ul>

<h2>📖 Teaching</h2>
<ul class="clean-list">
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>


<h2>🏆 Awards & Achievements</h2>
<ul class="clean-list">
  <li>Top 1% freelancer on Freelancer.com based on client satisfaction and success.</li>
  <li>Chancellor's Silver Medal at NUST for academic excellence.</li>
  <li>Master’s thesis nominated for best thesis at Tsinghua University CS Department.</li>
</ul>

<style>
  ul.clean-list {
    list-style: none;
    padding-left: 0;
  }
  ul.clean-list li {
    margin-bottom: 1em;
  }
</style>

<!-- 

## Education
* Ph.D in Scientific Computing, Uppsala University, 2028 (expected)
* M.S. in Advanced Computing Science, Tsinghua University, 2019
* B.E. in Software Engineering, National University of Sciences and Technology (NUST), 2015

## Work experience

* Dec 2021 – Dec 2022: Freelance Developer
  * Freelancer.com
  * Delivered over 50 projects with 100% client satisfaction in the domains of computer vision, machine learning, automation, data scraping, and backend development.
  * Achieved top 1% freelancer status based on skills and performance.

* Oct 2015 – Aug 2017: Software Engineer
  * NETSOL Technologies Inc.
  * Duties included: Research and development of financial applications.
  * Supervisor: [Naveed Shahid](https://www.linkedin.com/in/naveed-shahid-08429514/)

* Mar 2014 – May 2014: Internship
  * Microsoft, Pakistan Chapter
  * Duties included: Developing Windows-based mobile applications.

  
## Skills
* Programming Languages: C, C++, Python, Java, VB.NET
* Distributed Systems
* Machine Learning: Federated Learning, Adversarial Networks 
* Development Tools: TensorFlow, PyTorch, Docker
* Additional Skills: Data scraping, Automation, Backend Development

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!--   
## Talks
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
-->
<!--   
## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> 

## Awards & Achievements
* Listed among the top 1% of freelancers on Freelancer.com based on client satisfaction and project success.  
* Awarded the Chancellor's Silver Medal for academic excellence during Bachelor’s studies at NUST.
* Master’s thesis recommended for overall best thesis award across all programs under the Department of Computer Science and Technology at Tsinghua University. -->
