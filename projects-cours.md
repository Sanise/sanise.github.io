---
layout: project
title: Projets en cours
---


<h1>{{ page.title }}</h1>

<ul>
  {% for project in site.data.projects %}
    <li>
      <a href="{{ project.link }}">
        <img src="{{ project.image }}" alt="Image de {{ project.name }}">
        <h2>{{ project.name }}</h2>
        <p>{{ project.description }}</p>
      </a>
    </li>
  {% endfor %}
</ul>
