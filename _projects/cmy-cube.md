---
name: CMY Cube
image: /Portfolio%20Projects/CMY%20Cube/1.jpeg
description: A CMY Cube project documenting the design and finished work.
---

## CMY Cube

A CMY Cube project documenting the design and finished work.

{% assign cmy_cube_images = "1.jpeg,2.jpeg,3.jpeg,4.jpeg" | split: "," %}

<div class="row">
{% for image in cmy_cube_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/CMY Cube/' | append: image | relative_url }}" alt="CMY Cube project photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
