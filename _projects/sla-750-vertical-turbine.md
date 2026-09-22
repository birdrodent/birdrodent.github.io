---
name: SLA 750 Vertical Turbine
image: /Portfolio%20Projects/Xylem/SLA%20750%20Vertical%20Turbine/1.gif
description: A documentation project focused on the SLA 750 vertical turbine assembly, process, and outcome.
---

## SLA 750 Vertical Turbine

One of my primary responsibilities in my role as an AM Design Engineer was the production of functional prototypes using the AM lab’s 3D Systems SLA 750. In many instances I was able to demonstrate value as an intermediary step between CFD validation and first article tooling (in-house production through the AM lab was often cheaper and much, much faster than outsourcing).

In the unending pursuit of more energy-efficient pumps I was commissioned by various teams across North America to help validate some novel new pump geometry they’d discovered. Xylem’s sub-brand Goulds Water Technology based in Lubbock, TX has a wide variety of vertical turbine pumps in their portfolio, and this is one of many I was able to provide their R&D team for testing. 

Pictured below you can see some of the typical SLA printer production workflow; printing, desupporting, wash cycle, surface detailing, and final UV cure. Some cosmetic imperfections like the small chip beside the modeled threads are largely unavoidable but Large-Format SLA is the only current 3D printer technology able to capture this level of detail at this physical scale.

{% assign sla750_vertical_turbine_images = "1.gif,2.jpeg,3.gif,4.jpeg,5.jpeg,6.jpeg,7.jpeg,8.jpeg" | split: "," %}

<div class="row">
{% for image in sla750_vertical_turbine_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Xylem/SLA 750 Vertical Turbine/' | append: image | relative_url }}" alt="SLA 750 vertical turbine photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
