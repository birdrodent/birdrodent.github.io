---
name: E90 Desk Toy
tools: [CAD, 3D Printing, Design, Prototyping]
image: /Portfolio%20Projects/Xylem/E90%20Desk%20Toy/B7E150A1-4050-4E8E-B4D6-70F224346B0F_1_102_o.jpeg
description: A custom desk toy built around the E90 concept with iterative mechanical refinement.
---

## E90 Desk Toy

A custom desk toy project exploring form, motion, and visual interest through iterative 3D-printed mechanical design.

{% assign e90_images = "B7E150A1-4050-4E8E-B4D6-70F224346B0F_1_102_o.jpeg,2B13AF8B-2008-4286-A0A4-F25C009FF2C7_1_105_c.jpeg,2BFF7A81-A215-4464-A904-26F32236AB78_1_105_c.jpeg,3EE8ECD1-624F-475E-A3A7-063C6C4219AD_1_102_o.jpeg,91EACB61-2A6E-4FA6-A5A2-EE57F3776C40_1_105_c.jpeg,C39F86A7-4A05-4C91-AEC3-DFF05638F99A_1_102_o.jpeg,E3F887F8-875C-494A-9C9C-5E45CF221BDD_1_105_c.jpeg,EAD58886-6176-4A38-98DA-007366BB198F_1_102_o.jpeg" | split: "," %}

<div class="row">
{% for image in e90_images %}
  <div class="col-md-6 mb-4">
    {% if forloop.first %}
      <img src="{{ '/Portfolio Projects/Xylem/E90 Desk Toy/' | append: image | relative_url }}" alt="E90 desk toy photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy" style="background: white; padding-top: 2rem; padding-bottom: 2rem;">
    {% else %}
      <img src="{{ '/Portfolio Projects/Xylem/E90 Desk Toy/' | append: image | relative_url }}" alt="E90 desk toy photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
    {% endif %}
  </div>
{% endfor %}
</div>
