---
name: Xylem 8100 Series Scale Demo
tools: [Xylem, Instrumentation, Calibration, Process Control]
image: /assets/images/xylem-8100/IMG_8269.jpeg
description: A demonstration of the Xylem 8100 Series scale system in operation.
---

## Xylem 8100 Series Scale Demo

A field-ready instrumentation demo showcasing the 8100 Series scale system, setup, and calibration workflow in a practical application.

{% assign xylem_images = "IMG_8145.GIF,IMG_8269.jpeg,IMG_8273.jpeg,IMG_8274.jpeg,IMG_8276.jpeg,IMG_8280.jpeg,IMG_8288.jpeg,IMG_8289.jpeg" | split: "," %}

<div class="row">
{% for image in xylem_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/assets/images/xylem-8100/' | append: image | relative_url }}" alt="Xylem 8100 Series scale demo photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
