---
layout: page
title: Projects
permalink: /projects/
eyebrow: Portfolio
subtitle: Selected research and software directions.
---

<div class="project-grid">
{% for project in site.projects %}
  <article class="project-card">
    <h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
    <p>{{ project.summary }}</p>
  </article>
{% endfor %}
</div>
