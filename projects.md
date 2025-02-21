---
layout: default
title: Projects
---

# Projects

{% assign projects = site.data.projects %}

{% for project in projects %}
  <h2>{{ project.title }}</h2>
  <p>{{ project.description }}</p>
  <p><strong>Technologies:</strong> {{ project.technologies }}</p>
  {% if project.github %}
    <a href="{{ project.github }}">GitHub Repository</a>
  {% endif %}
  {% if project.demo %}
    <a href="{{ project.demo }}">Demo</a>
  {% endif %}
{% endfor %}
