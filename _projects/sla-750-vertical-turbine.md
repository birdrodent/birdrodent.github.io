---
name: SLA 750 Vertical Turbine
image: /Portfolio%20Projects/Xylem/SLA%20750%20Vertical%20Turbine/1.gif
description: A documentation project focused on the SLA 750 vertical turbine assembly, process, and outcome.
---

## SLA 750 Vertical Turbine

A visual record of the vertical turbine work, from setup through final results.

{% assign sla750_vertical_turbine_images = "1.gif,2.jpeg,3.gif,4.jpeg,5.jpeg,6.jpeg,7.jpeg,8.jpeg" | split: "," %}

<div class="row">
{% for image in sla750_vertical_turbine_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Xylem/SLA 750 Vertical Turbine/' | append: image | relative_url }}" alt="SLA 750 vertical turbine photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
