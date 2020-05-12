---
layout: page
title: "New EO Training Slides"
permalink: "/slides/"
---

<ul>
  {% for page in site.slides %}
    <li>
      <a href="{{ page.url | relative_url }}">Slide {{ page.title }}</a>
    </li>
  {% endfor %}
</ul>