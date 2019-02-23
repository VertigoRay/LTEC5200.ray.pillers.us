---
layout: collection
title: Military
permalink: /military/
---
<ul>
  {% for military in site.military %}
    <li>
      <a href="{{ military.url }}">{{ military.title }}</a>
    </li>
  {% endfor %}
</ul>