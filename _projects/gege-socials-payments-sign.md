---
name: Gege Socials/Payments Sign
image: /Portfolio%20Projects/Gege%20Socials%3APayments%20Sign/4.jpeg
description: A Gege Socials/Payments sign project documenting the design and finished work.
---

## Gege Socials/Payments Sign

A Gege Socials/Payments sign project documenting the design and finished work.

{% assign gege_socials_images = "1.PNG,2.gif,3.jpeg,4.jpeg,5.jpeg,6.jpeg" | split: "," %}

<div class="row">
{% for image in gege_socials_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Gege Socials:Payments Sign/' | append: image | relative_url }}" alt="Gege Socials/Payments sign project photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
