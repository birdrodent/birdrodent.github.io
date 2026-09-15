---
name: Xylem 8100 Series Scale Demo
tools: [Xylem, Instrumentation, Calibration, Process Control]
image: /assets/images/xylem-8100/IMG_8145.GIF
description: A demonstration of the Xylem 8100 Series scale system in operation.
---

## Xylem 8100 Series Scale Demo

A Scale Model of an 8100 series AC Fire split-case pump. This model was designed, printed, and displayed at a collection of trade shows including IMTS.

Extensive changes in the CAD were required to print effectively. The production model is ~33in end to end and contains 107 individual components. The scale demonstration model is ~1/3 the size and merges many components (Bolts, seals, bearings, etc.) into larger surrounding design features, simplifying the overall design to a much more managable 12 parts. A simple base was also designed and printed with a small placard with the AC fire logo and the series of pump.

{% assign xylem_images = "IMG_8145.GIF,IMG_8269.jpeg,IMG_8273.jpeg,IMG_8274.jpeg,IMG_8276.jpeg,IMG_8280.jpeg,IMG_8288.jpeg,IMG_8289.jpeg" | split: "," %}

<div class="row">
{% for image in xylem_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/assets/images/xylem-8100/' | append: image | relative_url }}" alt="Xylem 8100 Series scale demo photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
