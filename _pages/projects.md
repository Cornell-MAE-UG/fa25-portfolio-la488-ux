---
layout: default
title: Liam Alcalay - Portfolio
permalink: /projects/
---

<div class="gallery-container">
  <div class="project-gallery">
    {% assign visible_projects = site.projects | where_exp: "project", "project.hidden != true" %}
    {% for project in visible_projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title }}</p>
        </a>
      </div>
    {% endfor %}
  </div>
</div>