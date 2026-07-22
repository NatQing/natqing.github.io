---
layout: index
title: Home
permalink: /
---

<section class="hero-row home-hero">
  <div class="portrait-wrap wow animated fadeIn">
    <div class="portrait portrait-placeholder">
      <img class="profile-photo" src="{{ '/assets/photos/portrait.jpeg' | relative_url }}" alt="Portrait of Yi Nathen Qing" onload="this.nextElementSibling.hidden=true" onerror="this.hidden=true">
      <span aria-hidden="true">NQ</span>
    </div>
  </div>
  <div class="hero-copy wow animated fadeInUp">
    <h1>Yi Nathen Qing</h1>
    <p class="lead">Hi, I’m Nathen! I’m a Bioengineering student at the <a href="https://www.washington.edu/" target="_blank" rel="noopener">University of Washington</a>. I spend most of my research time thinking about how we can design proteins on a computer, make them in the lab, and get them to do something useful.</p>
    <p>Right now, I’m working in the UW Baker Lab on the De Novo Design of Electron and Energy Conductive Protein Nanowires. Before that, I’ve bounced between synthetic biology, biomaterials, bioprinting, vascular modeling, and robotics—which is probably a good summary of how easily I get interested in new problems.</p>
    <p>Outside the lab, I like hiking, playing Minecraft, doing trivia, and exploring Seattle with friends. I’m always happy to talk about research, strange biological systems, or an unnecessarily elaborate Minecraft build.</p>
    <div class="hero-actions">
      <a class="btn btn-primary" href="{{ '/research/' | relative_url }}">See what I’m working on</a>
      <a class="btn btn-outline-primary" href="{{ '/resume/' | relative_url }}">Résumé</a>
    </div>
    <div class="contact-line" aria-label="Contact links">
      <a href="mailto:nathenqing@gmail.com"><i class="fas fa-envelope" aria-hidden="true"></i> nathenqing@gmail.com</a>
      <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank" rel="noopener"><i class="fab fa-linkedin" aria-hidden="true"></i> LinkedIn</a>
      <a href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
    </div>
  </div>
</section>

<section class="focus-strip" aria-labelledby="focus-heading">
  <p class="section-kicker">Current focus</p>
  <h2 id="focus-heading">De Novo Design of Electron and Energy Conductive Protein Nanowires</h2>
  <p>I’m designing protein nanowires that can conduct electrons and energy through predictable structures. The project moves back and forth between a parametric computational design pipeline and wet-lab expression, purification, and testing—exactly the kind of loop between code and experiments that I enjoy.</p>
</section>
