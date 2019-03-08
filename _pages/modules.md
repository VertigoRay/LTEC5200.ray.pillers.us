---
layout: collection
title: Modules
permalink: /modules/
sidebar:
  nav: modules
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZdHhs-I9FVo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<ul>
  {% for module in site.modules %}
    <li>
      <a href="{{ module.url }}">{{ module.title }}</a>
    </li>
  {% endfor %}
</ul>