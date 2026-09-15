---
name: Form 4 Onboarding
image: /Portfolio%20Projects/Xylem/Form%204%20Onboarding/IMG_1152.gif
description: A documentation and process onboarding project for the Formlabs Form 4 resin printer workflow.
---

## Form 4 Onboarding

Documentation of the workflow, setup, and validation process for bringing the Formlabs Form 4 into service.

{% assign form4_images = "IMG_1091.jpeg,IMG_1139.jpeg,IMG_1140.jpeg,IMG_1152.gif,IMG_1806.jpeg,IMG_1856.jpeg" | split: "," %}

<div class="row">
{% for image in form4_images %}
  <div class="col-md-6 mb-4">
    <img src="{{ '/Portfolio Projects/Xylem/Form 4 Onboarding/' | append: image | relative_url }}" alt="Form 4 onboarding photo {{ forloop.index }}" class="img-fluid rounded voron-gallery-image" loading="lazy">
  </div>
{% endfor %}
</div>
