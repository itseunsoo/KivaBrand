---
layout: pages
title: Photo Gallery
favorites:
- "/uploads/better_travel_photos-02.jpeg"
- "/uploads/kiva-slack-customer-story-hero.jpg"
- "/uploads/greenloans.jpg"

---
# Kiva Favourites

<div class="triple-grid">
{% for image in page.favorites-gallery %}
<img src="{{ image | relative_url }}">
{% endfor %}
</div>

# Most Recent


<div class="triple-grid">
{% for image in page.recent-gallery %}
<img src="{{ image | relative_url }}">
{% endfor %}
</div>