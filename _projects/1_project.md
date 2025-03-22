---
layout: page
title: Cancer Cell Migration
description: Substrate viscoelasticity modulates cell migration.
img: assets/img/Picture1.png
importance: 1
category: work
related_publications: true
---

<div class="justify-text">
Cell migration is pivotal in cancer metastasis, where cells navigate the extracellular matrix (ECM) and invade distant tissues. While the ECM is viscoelastic—exhibiting time-dependent stress relaxation—its influence on cell migration remains poorly understood. Here, we employ an integrated experimental and modeling approach to investigate filopodial cancer cell migration on viscoelastic substrates and uncover a striking transition from sub-diffusive to super-diffusive behavior driven by the substrate’s viscous relaxation timescale. Conventional motor-clutch based migration models fail to capture these anomalous migration modes, as they overlook the complex adhesion dynamics shaped by broad distribution of adhesion lifetimes. To address this, we develop a glassy motor-clutch model {% cite sharma2025glassy %} that incorporates the rugged energy landscape of adhesion clusters, where multiple metastable states yield long-tailed adhesion timescales. Our model reveals that migration dynamics are governed by the interplay between cellular and substrate timescales: slow-relaxing substrates prolong trapping, leading to sub-diffusion, while fast-relaxing substrates promote larger steps limiting trapping, leading to super-diffusion. Additionally, we uncover the role of actin polymerization and contractility in modulating adhesion dynamics and driving anomalous migration. These findings establish a mechanistic framework linking substrate viscoelasticity to cell motility, with implications for metastasis and cancer progression.

</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/glassy_model.png" title="Glassy Motor Clutch Model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The glassy motor-clutch model captures both sub- and super-diffusive migration modes modulated by substrate stress relaxation. A, Schematic representation of the 2D motor clutch model illustrating cell migration on a viscoelastic substrate. The model utilizes independent clutch modules in the X and Y directions. B, Energy landscape depicting protein unfolding with multiple pathways, each with varying off rates. 
</div>

