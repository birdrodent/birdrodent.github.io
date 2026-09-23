---
name: Reno VICE Poker Chip
image: /Portfolio%20Projects/Reno%20VICE%20Poker%20Chip/8.jpg
description: A Reno VICE poker chip project documenting the design and finished work.
---

## Reno VICE Poker Chip

A Reno VICE poker chip project documenting the design and finished work.

{% assign reno_vice_images = "1.jpg,2.jpg,3.jpg,4.jpg,5.jpg,6.jpg,7.jpg,8.jpg" | split: "," %}

<div class="row">
{% for image in reno_vice_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Reno VICE Poker Chip/' | append: image | relative_url }}" alt="Reno VICE poker chip project photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
