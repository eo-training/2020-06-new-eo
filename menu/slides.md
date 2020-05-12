---
layout: page
title: "New EO Training Slides"
permalink: "/slides/"
---

<ul>
  {% for page in site.slides %}
    <li>
      <a href="{{ slides.url }}">{{ slides.title }}</a>
    </li>
  {% endfor %}
</ul>