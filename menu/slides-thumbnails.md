---
layout: page
title: "New EO Training - Slides Summary"
permalink: "/slides-summary/"
---

<div>

  {% for page in site.slides %}
  <div class="slide-summary">

      <div class="slide-image">
        <a href="{{ page.url | relative_url }}">
            <img src="../assets/slides/slide-{{ page.slug }}.jpeg">
        </a>
    </div>
    <div class="slide-notes">
        {{ page.content }}
    </div>

</div>

{% endfor %}

</div>