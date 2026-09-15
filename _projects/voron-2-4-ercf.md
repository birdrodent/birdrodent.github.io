---
name: Voron 2.4 + ERCF
tools: [Voron 2.4, ERCF, 3D printing, CAD, Electronics]
image: /Portfolio%20Projects/Voron/IMG_9144.jpeg
description: A custom Voron 2.4 build with an ERCF multi-material setup.
---

## Voron 2.4 + ERCF

I self-sourced, printed components for, built, and finally configured a 250mm spec Voron 2.4r2 in less than a month back in 2023. Since then it has received several modifications and additions (most of which I also assembled and configured), most notably the Enraged Rabbit Carrot Feeder multi-material unit, enabling multicolor and multimaterial printing through one nozzle.

In addition to building and configring the designs of others within this open-source design group I also designed and published a few parts of my own, linked below:
- [Revo Nozzle Skirt - 250mm Rework](https://www.printables.com/model/719629-revo-nozzle-skirt-250mm-rework)
- [ERCF/Filamentalist 2020 Mounts w/Magnetic Panels](https://www.printables.com/model/1134526-ercffilamentalist-2020-mounts-wmagnetic-panels)

Owning, using, maintaining, and continually modifying this machine has been a labor of love for the last several years. In a few time-critical work situations I was able to flex this machine into the production flow, enabling opportunities the team may have missed if solely replying on the printers onsite.

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