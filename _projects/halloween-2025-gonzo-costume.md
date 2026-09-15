---
name: Halloween 2025 - Gonzo Costume
image: /Portfolio%20Projects/Gonzo/g10.jpeg
description: A Halloween 2025 Gonzo costume project documenting the design, fabrication, and finished costume.
---

## Halloween 2025 - Gonzo Costume

A costume project inspired by Gonzo, documenting the design, fabrication, and finished build.

{% assign gonzo_images = "g1.jpeg,g2.jpeg,g3.jpeg,g4.jpeg,g5.jpeg,g6.jpeg,g7.jpeg,g8.jpeg,g9.jpeg,g10.jpeg" | split: "," %}

<div class="row">
{% for image in gonzo_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ "/Portfolio Projects/Gonzo/" | append: image | relative_url }}" alt="Halloween 2025 Gonzo costume photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
