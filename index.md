---
layout: home
page_title: "DY Kim"
page_description: "Porject Portfolio"
image: "/assets/images/preview.png"
---

<div class="profile-container">
  <img src="assets/images/profile.jpg" alt="DaeYong Kim" class="profile-img">
  <div class="profile-text" id="about">
    <h1>DaeYong Kim</h1>
    <p>
      Hi, I'm <strong>DaeYong Kim</strong>. I'm a MS student at 
      <strong>Ajou University</strong>, advised by <strong>Prof. Ri Yu</strong>.
      I focus on <strong>Computer Graphics</strong> such as 
      <strong>motion capture, human-scene interaction, etc.</strong>
    </p>
    <div class="contact infomation">contact: {{site.email}}</div>
    <div class="buttons">
      <a href="https://github.com/DaeeYong/" class="btn">GitHub</a>
      <a href="http://cgldragon.com/" class="btn">Blog</a>
    </div>
  </div>
</div>

<section class="updates">
  <h2>Updates</h2>
  <ul>
    <li><strong>Sep 2024</strong>: Our paper accepted to International Congress of Parkinson's Disease and Movement Disorders🎉</li>
    <li><strong>Jan 2023</strong>: Joined Computer Graphics Labs as a undergraduate research intern</li>
    <li><strong>Jul 2022</strong>: Joined Visual Computing Labs as a undergraduate research intern</li>
  </ul>
</section>

<section id="educations">
  <h2>Educations</h2>
  {% include educations.html %}
</section>

<section id="experiments">
  <h2>Experiments</h2>
  {% include experiments.html %}
</section>

<section id="publications">
  <h2>Publications</h2>
  {% include publications.html %}
</section>

<section id="projects">
  <h2>Projects</h2>
  {% include projects.html %}
</section>
<section id="seminars">
  <h2>Seminars</h2>
  {% include seminars.html %}
</section>

<section id="seminars">
  <h2>Seminars</h2>
  <ul>
    {% for year in site.data.seminars %}
      <li><a href="seminars/{{ year[0] }}">📅 {{ year[0] }} Seminars</a></li>
    {% endfor %}
  </ul>
</section>
