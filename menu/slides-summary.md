---
layout: page
title: "New EO Training - Slides Thumbnails"
permalink: "/slides-thumbnails/"
---

{% for page in site.slides %}

<a href="{{ page.url | relative_url }}">

  <img src="assets/slides/slide-{{ page.slug }}.jpeg" style="max-width:10%; border-radius:2px; max-height:20vh;">

</a>

{% endfor %}
