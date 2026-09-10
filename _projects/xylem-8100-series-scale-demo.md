---
name: Xylem 8100 Series Scale Demo
tools: [Xylem, Instrumentation, Calibration, Process Control]
image: /Portfolio%20Projects/Xylem/8100%20Series%20Scale%20Demo/IMG_8269.jpeg
description: A demonstration of the Xylem 8100 Series scale system in operation.
---

## Xylem 8100 Series Scale Demo

A field-ready instrumentation demo showcasing the 8100 Series scale system, setup, and calibration workflow in a practical application.

<div class="row">
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Xylem/8100 Series Scale Demo/IMG_8145.GIF' | relative_url }}" alt="Xylem 8100 Series scale demo overview" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Xylem/8100 Series Scale Demo/IMG_8269.jpeg' | relative_url }}" alt="Xylem 8100 Series scale demo detail" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
</div>

{% assign xylem_images = "IMG_8269.jpeg,IMG_8273.jpeg,IMG_8274.jpeg,IMG_8276.jpeg,IMG_8280.jpeg,IMG_8288.jpeg,IMG_8289.jpeg" | split: "," %}

<div class="row">
{% for image in xylem_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Xylem/8100 Series Scale Demo/' | append: image | relative_url }}" alt="Xylem 8100 Series scale demo photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
