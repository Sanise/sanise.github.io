---
layout: project
title: Projets en cours
---

<ul>
  {% for project in site.data.projects %}
    <li>
      <a href="{{ project.link }}">
        <img src="{{ project.image }}" alt="{{ project.name }} image">
        <h2>{{ project.name }}</h2>
        <p>{{ project.description }}</p>
      </a>
    </li>
  {% endfor %}
</ul>
