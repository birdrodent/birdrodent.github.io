---
name: Halloween 2025 - Gonzo Costume
image: /Portfolio%20Projects/Gonzo/IMG_2493.jpeg
description: A Halloween 2025 Gonzo costume project documenting the design, fabrication, and finished costume.
---

## Halloween 2025 - Gonzo Costume

A costume project inspired by Gonzo, documenting the design, fabrication, and finished build.

{% assign gonzo_images = "IMG_2208.jpeg,IMG_2237.jpeg,IMG_2238.jpeg,IMG_2284.jpeg,IMG_2340.jpeg,IMG_2356.jpeg,IMG_2359.jpeg,IMG_2374.jpeg,IMG_2388.jpeg,IMG_2474.jpeg,IMG_2490.jpeg,IMG_2493.jpeg" | split: "," %}

<div class="row">
{% for image in gonzo_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ "/Portfolio Projects/Gonzo/" | append: image | relative_url }}" alt="Halloween 2025 Gonzo costume photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
