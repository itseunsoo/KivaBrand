---
layout: pages
title: Photo Gallery
favorites:
- "/uploads/better_travel_photos-02.jpeg"
- "/uploads/kiva-slack-customer-story-hero.jpg"
- "/uploads/greenloans.jpg"
favorites-gallery:
- "/uploads/greenloans.jpg"
- "/uploads/kiva-slack-customer-story-hero.jpg"
- "/uploads/better_travel_photos-02.jpeg"
recents:
- "/uploads/greenloans.jpg"
- "/uploads/kiva-slack-customer-story-hero.jpg"
- "/uploads/better_travel_photos-02.jpeg"
- "/uploads/about-top-sm-retina_0.jpg"

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