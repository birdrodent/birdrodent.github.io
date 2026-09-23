---
name: Voron 2.4 + ERCF
image: /Portfolio%20Projects/Voron/16.jpeg
description: A self-sourced and one-of-a-kind Voron 2.4 build with an ERCF multi-material unit.
---

## Voron 2.4 + ERCF

I self-sourced, printed components for, built, and finally configured a 250mm spec Voron 2.4r2 in less than a month back in 2023. Since then it has received several modifications and additions (most of which I also assembled and configured), most notably the Enraged Rabbit Carrot Feeder multi-material unit, enabling multicolor and multimaterial printing through one nozzle.

In addition to building and configring the designs of others within this open-source design group I also designed and published a few parts of my own, linked below:
- [Revo Nozzle Skirt - 250mm Rework](https://www.printables.com/model/719629-revo-nozzle-skirt-250mm-rework)
- [ERCF/Filamentalist 2020 Mounts w/Magnetic Panels](https://www.printables.com/model/1134526-ercffilamentalist-2020-mounts-wmagnetic-panels)

Owning, using, maintaining, and continually modifying this machine has been a labor of love for the last several years. In a few time-critical work situations I was able to flex this machine into the production flow, enabling opportunities the team may have missed if solely replying on the printers onsite.

{% assign voron_images = "1.jpeg,2.jpeg,3.jpeg,4.jpeg,5.jpeg,6.jpeg,7.jpeg,8.jpeg,9.gif,10.jpeg,11.jpeg,12.jpeg,13.jpeg,14.jpeg,15.jpeg,16.jpeg" | split: "," %}

<div class="row">
{% for image in voron_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Voron/' | append: image | relative_url }}" alt="Voron 2.4 and ERCF project photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>