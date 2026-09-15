---
name: Let's Solve Water Sign
image: /Portfolio%20Projects/Xylem/Let's%20Solve%20Water%20Sign/IMG_5286.jpeg
description: A Let's Solve Water sign project exploring design, fabrication, and presentation.
---

## Let's Solve Water Sign

A project documenting the design and fabrication of the Let's Solve Water sign.

{% assign water_sign_images = "IMG_5286.jpeg,IMG_9557.jpeg,IMG_9558.jpeg,IMG_9559.jpeg,18000874-6E89-4A90-9A77-2635402C6F5B_1_105_c.jpeg,83530354-D365-4088-91B9-495062A633E1_1_105_c.jpeg" | split: "," %}

<div class="row">
{% for image in water_sign_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ "/Portfolio Projects/Xylem/Let's Solve Water Sign/" | append: image | relative_url }}" alt="Let's Solve Water sign photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
