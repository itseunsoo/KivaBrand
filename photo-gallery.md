---
layout: pages
title: "Photo Gallery"
---

Kiva Favourites

<div class="triple-grid">
  {% for image in page.favorites-gallery %}
  <img src="{{ image | relative_url }}">
  {% endfor %}
</div>

Most Recent
<div class="triple-grid">
  {% for image in page.recent-gallery %}
  <img src="{{ image | relative_url }}">
  {% endfor %}
</div>