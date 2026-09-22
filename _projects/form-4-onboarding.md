---
name: Form 4 Onboarding
image: /Portfolio%20Projects/Xylem/Form%204%20Onboarding/IMG_1152.gif
description: A documentation and process onboarding project for the Formlabs Form 4 resin printer workflow.
---

## Form 4 Onboarding

In August 2025 I presented a business case for onboarding a Formlabs Form 4 into the AM Lab. Formlabs’ proprietary material Rigid 10K is another glass-composite engineering resin with mechanical properties similar to the SLA 750’s Accura Composite PIV (at a fraction of the latter’s cost).

As well, the (now much more common) “inverted” SLA variant that cures the resin through a clear FEP sheet at the bottom of the reservoir enables material switching with much less material investment. The SLA 750 and other Large-Format SLA submerge the printed layers down into the resivoir while curing from the top, requiring the reservoir has enough material to fully submerge the max Z-height of the print envelope. In the case of the SLA 750, this amounts to ~160 gallons of resin.

By comparison, the Formlabs’ reservoir typically contains ~250mL at any time, dispensing more resin as needed. These reservoirs and auxiliary tanks can be quickly switched out, enabling a wide variety of material options.

Due to the practicalities of physics these inverted SLA machines are somewhat limited in maximum possible size, but for smaller projects (Like the pictured residential-grade impellers) the Formlabs proved to be a valuable, cost and time-saving investment.

{% assign form4_images = "IMG_1091.jpeg,IMG_1139.jpeg,IMG_1140.jpeg,IMG_1152.gif,IMG_1806.jpeg,IMG_1856.jpeg" | split: "," %}

<div class="row">
{% for image in form4_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Xylem/Form 4 Onboarding/' | append: image | relative_url }}" alt="Form 4 onboarding photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
