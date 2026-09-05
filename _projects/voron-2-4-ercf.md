---
name: Voron 2.4 + ERCF
tools: [Voron 2.4, ERCF, 3D printing, CAD, Electronics]
image: /Portfolio%20Projects/Voron/IMG_9144.jpeg
description: A custom Voron 2.4 build with an ERCF multi-material setup.
---

## Voron 2.4 + ERCF

A hands-on build focused on precision motion, multi-material printing, and thoughtful integration of the printer and ERCF hardware.

<div class="row">
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Voron/IMG_0586.jpeg' | relative_url }}" alt="Voron 2.4 with ERCF multi-material setup" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Voron/IMG_0682.jpeg' | relative_url }}" alt="Voron 2.4 build detail" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
</div>

{% assign voron_images = "IMG_1344.jpeg,IMG_1377.jpeg,IMG_1613.jpeg,IMG_5343.jpeg,IMG_5417.jpeg,IMG_5480.jpeg,IMG_5481.jpeg,IMG_5494.jpeg,IMG_8171.jpeg,IMG_9082.jpeg,IMG_9144.jpeg,IMG_9190.jpeg,IMG_9208.jpeg,IMG_9214.jpeg,IMG_9218.jpeg,IMG_9221.jpeg" | split: "," %}

<div class="row">
{% for image in voron_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Voron/' | append: image | relative_url }}" alt="Voron 2.4 and ERCF project photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>