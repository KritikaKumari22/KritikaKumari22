---
layout: default
title: Home
---
<section class="hero" aria-labelledby="intro-title">
  <div class="hero-card">
    <p class="eyebrow">Academic portfolio</p>
    <h1 id="intro-title">{{ site.author.name }}</h1>
    <p class="lead">{{ site.description }}</p>
    <div class="hero-actions">
      <a class="button primary" href="{{ '/research/' | relative_url }}">Explore research</a>
      <a class="button secondary" href="mailto:{{ site.author.email }}">Get in touch</a>
    </div>
  </div>
  <aside class="info-card" aria-label="Profile details">
    <p class="eyebrow">Profile</p>
    <ul class="quick-list">
      <li><span>Role</span>{{ site.author.role }}</li>
      <li><span>Affiliation</span>{{ site.author.affiliation }}</li>
      <li><span>Location</span>{{ site.author.location }}</li>
      <li><span>Email</span><a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></li>
      <li><span>GitHub</span><a href="https://github.com/{{ site.author.github }}">@{{ site.author.github }}</a></li>
    </ul>
  </aside>
</section>

<section class="section" aria-labelledby="focus-title">
  <p class="eyebrow">Research focus</p>
  <h2 id="focus-title">Computational models for biological systems.</h2>
  <div class="section-grid">
    <article class="feature-card">
      <h3>Machine learning for sequences</h3>
      <p>Building foundational models for biological sequence classification and discovery.</p>
    </article>
    <article class="feature-card">
      <h3>Protein dynamics</h3>
      <p>Studying molecular behavior with computational biology and data-driven methods.</p>
    </article>
    <article class="feature-card">
      <h3>Studying the Evolution of Vesicle trafficking networks in Proto-Eukaryotes </h3>
      <p>Using graph-theoretic Boolean modeling to investigate the emergence of complexity in the eukaryotic endomembrane system during evolution.</p>
    </article>
  </div>
</section>

<section class="callout" aria-labelledby="template-title">
  <p class="eyebrow">Site template</p>
  <!-- <h2 id="template-title">A clean Jekyll foundation for an academic website.</h2> -->
  <!-- <p>This site now separates content, layouts, and styling so it can grow into pages for publications, projects, CV content, and research updates.</p> -->
</section>
