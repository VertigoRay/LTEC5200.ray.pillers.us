---
title: Military
layout: collection
permalink: /military/
sidebar:
  nav: military
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/TlO2gcs1YvM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<ul>
  {% for military in site.military %}
    <li>
      <a href="{{ military.url }}">{{ military.title }}</a>
    </li>
  {% endfor %}
</ul>