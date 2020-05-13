---
layout: page
title: "New EO Training - Table of Contents"
permalink: "/slides/"
---

<ul>
  {% for page in site.slides %}
  <li>
      <a href="{{ page.url | relative_url }}">Slide {{ page.title }}</a>
  </li>
  {% endfor %}
</ul>