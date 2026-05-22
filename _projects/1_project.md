---
layout: page
title: Benthic Macroinvertebrates of Lake Zurich
description: Contrasting benthic communities between the Upper and Lower basins of Lake Zurich
img: assets/img/project1/PXL_20250430_131307756.MP.jpg
importance: 1
category: work
related_publications: false
---

## Overview

Lake Zurich is one of Switzerland's most important water bodies — a drinking water reservoir for over 1.3 million people and an ecosystem increasingly under pressure from biological invasions. Despite its ecological and societal significance, no comprehensive baseline survey of its benthic macroinvertebrate community had ever been conducted. This project fills that gap, and asks a new question: do the Upper Lake (Obersee) and Lower Lake (Untersee) differ in how they have been invaded?

Benthic invertebrates are sentinels of shoreline change. They recycle nutrients, feed fish, and — unlike pelagic organisms — are tied to substrate, so they cannot simply leave degraded habitat. This makes them ideal indicators of ecological change. The **littoral zone**, where light, substrate, and organisms collide, is where the invasion signal is strongest.

---

## Study Design

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project1/PXL_20250519_092735796-1400.webp" title="Benthic sampling fieldwork" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fieldwork for the benthic macroinvertebrate survey of Lake Zurich. © Julie Conrads
</div>

Sampling was carried out at **7 sites** — 5 in the Lower Lake and 2 in the Upper Lake — across three depth zones:

- **1 m** (sampled in 2024) — using a vacuum device
- **5 m** (sampled in 2025) — using Ekman grabs
- **15 m** (sampled in 2025) — using Ekman grabs

All samples were preserved in ethanol in the field, then sorted and identified under stereo- and compound microscopes. All individuals were enumerated and identified to the lowest possible taxonomic level.

---

## Dataset

The dataset comprises **92,085 individuals** across **65 taxa** and **8 classes** — the first quantitative, multi-site, multi-depth baseline for the benthic invertebrate community of Lake Zurich.

---

## Key Findings

**Community composition is structured primarily by depth.** Bivalves dominate shallow communities (1–5 m) in both basins, while 15 m communities are compositionally distinct. In the Upper Lake at 15 m, Clitellata (worms) account for 44% of individuals; in the Lower Lake at 15 m, Clitellata reach 39%.

**Invasive species dominate shallow water in both basins.** Non-native taxa account for the majority of individuals at 1 m and 5 m depth:

| Depth | Lower Lake (invasive %) | Upper Lake (invasive %) |
|-------|------------------------|------------------------|
| 1 m   | 85%                    | 59%                    |
| 5 m   | 68%                    | 69%                    |
| 15 m  | 24%                    | 8%                     |

**The two basins differ functionally.** Upper Lake communities occupy broader functional trait space across all categories (FDis, FEve, FRic), suggesting higher functional diversity despite similar invasion levels at shallow depths. The Lower Lake is characterised by sessile active filter feeders on fine and hard substrates, while the Upper Lake supports more mobile gatherers and soft-substrate taxa.

**The Quagga mussel invasion is still in its early stages in Lake Zurich.** The Zebra mussel (*Dreissena polymorpha*) currently dominates at most sites — but the Quagga mussel (*D. bugensis*), first detected here in 2024, is already present across the Lower Lake. In Lake Constance, where the Quagga mussel is established, densities reach ~8,000 ind. m⁻² — a stark contrast to the current situation in Lake Zurich (~28–74 ind. m⁻²), and a possible preview of what is to come.

**Compared to historical data, Zebra mussel densities have increased ~88× in the Lower Lake** (from 113 ind. m⁻² in 1978–1988 to 9,958 ind. m⁻² in 2024/25), while *Potamopyrgus antipodarum* (New Zealand mudsnail) has declined ~43× (from 28,905 to 676 ind. m⁻²).

---

## What Drives the Basin Contrast?

Three interacting factors likely explain why the Lower Lake shows a stronger invasion signal:

1. **Invasion pressure** — The Lower Lake has 53 registered marinas (536 permits) compared to 17 (206 permits) in the Upper Lake, and receives more boat traffic from high-risk source waters such as Lake Constance and Vierwaldstättersee.
2. **Habitat filtering** — 55% of the Lower Lake shoreline is artificial, compared to 35% in the Upper Lake. Modified shorelines filter out sensitive native taxa and create conditions where stress-tolerant and invasive species thrive.
3. **Basin morphology** — Water flows from Upper to Lower Lake through the Rapperswil narrows. The Lower Lake (~65 km², max. 137 m deep) receives input that has already passed through the Upper Lake (~27 km², max. 48 m deep).

A manuscript is currently in preparation.

---

## Photo Gallery

<div class="gallery-grid">
  {% assign proj1_images = "PXL_20251002_081954110.MP.jpg,PXL_20250930_083951018.jpg,PXL_20250907_132151098.MP.jpg,PXL_20250901_145453320.MP.jpg,PXL_20250811_100042006.MP.jpg,PXL_20250808_083403681.MP.jpg,PXL_20250612_122829804.jpg,PXL_20250522_122241168.MP.jpg,PXL_20250519_092735796.jpg,PXL_20250519_084259510.MP.jpg,PXL_20250513_110554490.jpg,PXL_20250508_092444771.jpg,PXL_20250502_095534927.jpg,PXL_20250430_131307756.MP.jpg,PXL_20250429_101718958.MP.jpg,PXL_20250415_100101058.MP.jpg,PXL_20250409_152545461.MP.jpg,PXL_20250408_073518398.MP.jpg,PXL_20250403_111905195.MP.jpg,PXL_20250320_173651219.MP.jpg" | split: "," %}
  {% for img in proj1_images %}
  <div class="gallery-item">
    <a href="{{ 'assets/img/project1/' | append: img | relative_url }}" target="_blank">
      <img src="{{ 'assets/img/project1/' | append: img | relative_url }}" alt="Benthic survey fieldwork, Lake Zurich" loading="lazy" />
    </a>
  </div>
  {% endfor %}
</div>
<div class="caption" style="margin-top: 0.5rem;">
    Fieldwork images from the benthic macroinvertebrate survey of Lake Zurich and Obersee. © Julie Conrads
</div>
