---
layout: pages
title: Photo Gallery
favorites:
- "/uploads/logo-construction.svg"
- "/uploads/logo-clearspace.svg"
- "/uploads/rules.jpeg"

---
# Kiva Favourites

<div class="triple-grid">
{% for image in page.favorites %}
<img src="{{ image | relative_url }}">
{% endfor %}
</div>

# Most Recent


<div class="quad-grid">
{% for image in page.recents %}
<img src="{{ image | relative_url }}">
{% endfor %}
</div>