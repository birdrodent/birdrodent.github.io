---
name: Let's Solve Water Sign
image: /Portfolio%20Projects/Xylem/Let's%20Solve%20Water%20Sign/6.jpeg
description: A Let's Solve Water sign project exploring design, fabrication, and presentation.
---

## Let's Solve Water Sign

A project documenting the design and fabrication of the Let's Solve Water sign.

{% assign water_sign_images = "1.jpeg,2.jpeg,3.jpeg,4.jpeg,5.jpeg,6.jpeg" | split: "," %}

<div class="row">
{% for image in water_sign_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ "/Portfolio Projects/Xylem/Let's Solve Water Sign/" | append: image | relative_url }}" alt="Let's Solve Water sign photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
