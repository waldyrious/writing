---
title: Writing
---

# Writing

<ul>
{% for page in site.pages %}
  {% if page.name != 'index.md' %}
    <li><a href="{{ page.url | relative_url }}">{{ page.title | default: page.name }}</a></li>
  {% endif %}
{% endfor %}
</ul>
