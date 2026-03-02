---
layout: default
title: Projects
---

# Projects

Here are some of the projects I've worked on:

{% for project in site.projects %}
## {{ project.title }}

{{ project.excerpt }}

[Read More]({{ project.url }})

---
{% endfor %}

[← Back Home](index.html)
