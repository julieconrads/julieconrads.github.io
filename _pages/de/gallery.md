---
layout: page
title: galerie
lang: de
permalink: /gallery/
description: Fotos von der Feldarbeit an Seen, von Taucheinsätzen und aus dem Labor.
nav: true
nav_order: 7
---

<div class="gallery-credit-note">
  <i class="fa-solid fa-camera"></i>
  <span>Alle Fotos © Julie Conrads, sofern nicht anders angegeben. Bitte kontaktieren Sie mich vor einer Weiterverwendung.</span>
</div>

<div class="gallery-masonry">

  <div class="gallery-masonry-item">
    <a href="{{ 'assets/img/gallery/quagga_constance_15m_1.jpg' | relative_url }}" target="_blank">
      <img src="{{ 'assets/img/gallery/quagga_constance_15m_1.jpg' | relative_url }}" alt="Quaggamuscheln in 15 m Tiefe, Bodensee" loading="lazy" />
      <div class="gallery-masonry-overlay"><span>Quaggamuscheln in 15 m Tiefe, Bodensee · © Christoph Walcher, Eawag</span></div>
    </a>
  </div>

  <div class="gallery-masonry-item">
    <a href="{{ 'assets/img/gallery/quagga_constance_15m_2.jpg' | relative_url }}" target="_blank">
      <img src="{{ 'assets/img/gallery/quagga_constance_15m_2.jpg' | relative_url }}" alt="Quaggamuschel-Kolonie, Bodensee" loading="lazy" />
      <div class="gallery-masonry-overlay"><span>Dichte Quaggamuschel-Kolonie, Bodensee · © Christoph Walcher, Eawag</span></div>
    </a>
  </div>

  <div class="gallery-masonry-item">
    <a href="{{ 'assets/img/gallery/quagga_harbour_bottinghofen.jpg' | relative_url }}" target="_blank">
      <img src="{{ 'assets/img/gallery/quagga_harbour_bottinghofen.jpg' | relative_url }}" alt="Quaggamuscheln an einem Hafenpfosten, Bottinghofen" loading="lazy" />
      <div class="gallery-masonry-overlay"><span>Quaggamuscheln an einem Hafenpfosten, Bottinghofen, Bodensee</span></div>
    </a>
  </div>

  <div class="gallery-masonry-item">
    <a href="{{ 'assets/img/gallery/quagga_bielersee.jpg' | relative_url }}" target="_blank">
      <img src="{{ 'assets/img/gallery/quagga_bielersee.jpg' | relative_url }}" alt="Quaggamuscheln auf Steinen, Bielersee" loading="lazy" />
      <div class="gallery-masonry-overlay"><span>Mit Quaggamuscheln bedeckte Steine, Bielersee</span></div>
    </a>
  </div>

  <div class="gallery-masonry-item">
    <a href="{{ 'assets/img/gallery/quagga_constance_40m.jpg' | relative_url }}" target="_blank">
      <img src="{{ 'assets/img/gallery/quagga_constance_40m.jpg' | relative_url }}" alt="Schalen von Quaggamuscheln, ~40 m, Bodensee" loading="lazy" />
      <div class="gallery-masonry-overlay"><span>Schalen von Quaggamuscheln in ~40 m Tiefe, Bodensee</span></div>
    </a>
  </div>

{% assign proj1_images = "PXL_20251002_081954110.MP.jpg,PXL_20250930_083951018.jpg,PXL_20250907_132151098.MP.jpg,PXL_20250901_145453320.MP.jpg,PXL_20250811_100042006.MP.jpg,PXL_20250808_083403681.MP.jpg,PXL_20250612_122829804.jpg,PXL_20250522_122241168.MP.jpg,PXL_20250519_092735796.jpg,PXL_20250519_084259510.MP.jpg,PXL_20250513_110554490.jpg,PXL_20250508_092444771.jpg,PXL_20250502_095534927.jpg,PXL_20250430_131307756.MP.jpg,PXL_20250429_101718958.MP.jpg,PXL_20250415_100101058.MP.jpg,PXL_20250409_152545461.MP.jpg,PXL_20250408_073518398.MP.jpg,PXL_20250403_111905195.MP.jpg,PXL_20250320_173651219.MP.jpg" | split: "," %}
{% for img in proj1_images %}

  <div class="gallery-masonry-item">
    <a href="{{ 'assets/img/project1/' | append: img | relative_url }}" target="_blank">
      <img src="{{ 'assets/img/project1/' | append: img | relative_url }}" alt="Feldarbeit für die benthische Erhebung, Zürichsee" loading="lazy" />
      <div class="gallery-masonry-overlay"><span>Erhebung der benthischen Makroinvertebraten, Zürichsee</span></div>
    </a>
  </div>
  {% endfor %}

</div>
