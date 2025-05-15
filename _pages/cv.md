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
    /* list-style: none;
    padding-left: 0; */
  }
  ul.clean-list li {
    margin-bottom: 1em;
  }
</style>