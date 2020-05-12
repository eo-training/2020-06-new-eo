---
layout: page
title: "New EO Training Slides"
permalink: "/slides/"
---

<div>

  {% for page in site.slides %}
  <div class="slide-summary">

      <div class="slide-image">
        <a href="{{ page.url | relative_url }}">
            <img src="../assets/slides/slide-{{ page.slug }}.jpeg" style="width:100%;max-width:512px;border-radius:2px;">
        </a>
    </div>
    <div class="slide-notes" style="max-width:496px;">
        {{ page.content }}
    </div>

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