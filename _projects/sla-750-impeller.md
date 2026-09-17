---
name: SLA 750 Impeller
image: /Portfolio%20Projects/Xylem/SLA%20750%20Impeller/5.jpeg
description: An SLA 750 impeller project documenting the design, production, and finished component.
---

## SLA 750 Impeller

A project documenting the design and production of an impeller made for the SLA 750.

{% assign impeller_images = "1.jpeg,2.jpeg,3.jpeg,4.jpeg,5.jpeg,6.jpeg" | split: "," %}

<div class="row">
{% for image in impeller_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ "/Portfolio Projects/Xylem/SLA 750 Impeller/" | append: image | relative_url }}" alt="SLA 750 impeller project photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
