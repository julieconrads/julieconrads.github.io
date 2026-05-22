---
layout: page
title: gallery
permalink: /gallery/
description: Fieldwork photos from lakes, diving surveys, and lab work.
nav: true
nav_order: 4
---

<div class="gallery-grid">
  {% assign images = "quagga_mussels.jpg,quagga_underwater.jpg" | split: "," %}
  {% for image in images %}
    {% assign img_path = image | prepend: "assets/img/gallery/" %}
    <div class="gallery-item">
      <a href="{{ img_path | relative_url }}" target="_blank">
        <img src="{{ img_path | relative_url }}" alt="Fieldwork photo" loading="lazy" />
      </a>
    </div>
  {% endfor %}
</div>
