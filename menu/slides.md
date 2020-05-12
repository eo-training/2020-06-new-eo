---
layout: page
title: "New EO Training Slides"
permalink: "/slides/"
---

<table style="width:100%;">
  {% for page in site.slides %}
  <tr>
      <td>
        <a href="{{ page.url | relative_url }}">
            <img src="assets/slides/slide-{{ page.slug }}.jpeg" style="max-width:40%; border-radius:2px;">
        </a>
    </td>
    <td>{{ page.content }}</td>
</tr>
{% endfor %}
</ul>



<ul>
  {% for page in site.slides %}
  <li>
      <a href="{{ page.url | relative_url }}">Slide {{ page.title }}</a>
  </li>
  {% endfor %}
</ul>