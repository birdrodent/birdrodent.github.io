---
name: CLERTY
image: /Portfolio%20Projects/CLERTY/1.jpeg
description: A CLERTY project documenting the design and finished work.
---

## CLERTY

A CLERTY project documenting the design and finished work.

{% assign clerty_images = "1.jpeg,2.gif,3.png,4.png,5.png,6.jpeg,7.jpeg,8.jpeg,9.jpeg,10.png" | split: "," %}

<div class="row">
{% for image in clerty_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/CLERTY/' | append: image | relative_url }}" alt="CLERTY project photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
