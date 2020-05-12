---
layout: page
title: "New EO Training Slides"
permalink: "/slides/"
---

<div>
  {% for page in site.slides %}

  <div style="display:inline-block;">
    <a href="{{ page.url | relative_url }}">
        <img src="../assets/slides/slide-{{ page.slug }}.jpeg" style="max-width:512px;border-radius:2px;">
    </a>
</div>
<div style="display:inline-block;margin-left:10px;">
    {{ page.content }}
</div>

<hr/>

{% endfor %}
</div>




<ul>
  {% for page in site.slides %}
  <li>
      <a href="{{ page.url | relative_url }}">Slide {{ page.title }}</a>
  </li>
  {% endfor %}
</ul>