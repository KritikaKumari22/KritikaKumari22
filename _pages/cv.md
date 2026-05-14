---
layout: page
title: CV
permalink: /cv/
eyebrow: Background
subtitle: A concise academic profile that can be expanded with education, publications, awards, and teaching.
---

## Education

<ul class="timeline">
  <li>
    <time>Ph.D. in Biophysics</time>
    <strong>University of Wisconsin–Madison</strong>
    <p>Research in computational biology, machine learning, protein dynamics, and vesicle trafficking networks.</p>
  </li>
</ul>

## Research interests

{% for interest in site.author.interests %}
- {{ interest }}
{% endfor %}

## Contact

Email: [{{ site.author.email }}](mailto:{{ site.author.email }})  
GitHub: [@{{ site.author.github }}](https://github.com/{{ site.author.github }})
