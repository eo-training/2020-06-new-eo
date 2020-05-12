---
layout: page
title: "New EO Training Slides"
permalink: "/slides/"
---

<ul>
  {% for page in site.slides %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>