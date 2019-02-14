---
layout: single
title: Modules
permalink: /modules/
---

<ul>
  {% for module in site.modules %}
    <li>
      <a href="{{ module.url }}">{{ module.title }}</a>
    </li>
  {% endfor %}
</ul>