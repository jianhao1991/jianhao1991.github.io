---
layout: post
title:  A Framework for SRM Detectability&#58; The Case of Stratospheric Aerosol Injection
date: 2026-06-30
description: Integrating detection and attribution into a single detectability framework, and applying it to stratospheric aerosol injection scenarios in three Earth system models.
tags: Detectability Detection-Attribution SAI GeoMIP Earth-system-models
themes: [climate-engineering]
#categories: research
thumbnail: assets/img/detect_thumbnail.jpg
---

If solar radiation modification (SRM) were ever deployed, how would we know that it worked? Answering this requires more than detecting a change: the change must also be *attributed* to the intervention rather than to natural variability or to other forcings. In this ongoing work, I develop a framework for SRM *detectability* that integrates detection and attribution into a single measure, and apply it to stratospheric aerosol injection (SAI) scenarios simulated by three Earth system models. It extends the detectability thinking I applied to marine cloud brightening (MCB) through the inadvertent aerosol perturbation of the [IMO2020 shipping fuel regulation]({{ '/blog/2025/IMO/' | relative_url }}).

> **_The Framework_**
Detection asks whether a perturbed climate differs from the background state that preceded it; attribution asks whether that difference is due to the intervention, judged against a counterfactual simulation without SRM. Scoring both together, as a true detection rate against a false detection rate, yields a *detectability score* that penalizes false alarms as well as missed detections. I apply this to top-of-atmosphere shortwave reflection (monthly, 1° resolution) in CESM2-WACCM, E3SMv3, and UKESM1-1, using two GeoMIP-style scenarios branched from SSP2-4.5 in 2035: injection in the subtropics (30°N/S at 21 km) and at high latitudes (60°N/S at 15 km).

> **_The Science_**
Less than half of the globe is detectable, and where detection is possible it takes about 10 years on average, given a decade-long background record. The high-latitude injection scenario both enlarges the detectable area and shortens the average time to detectability. Spread across models is non-negligible, particularly at regional scales, which means that the confidence with which an intervention could be verified depends on the model used to assess it. These results echo the difficulty of detecting even a large, abrupt, real-world radiative forcing, as found for IMO2020, and underscore that monitoring requirements are an integral part of evaluating any climate intervention proposal.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/SAI_detectability_web.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

**References:**
- **J. Zhang** and G. Feingold: A framework for assessing SRM detectability: integrating detection and attribution. _In preparation_.
- **J. Zhang**, Y.-S. Chen, E. Gryspeerdt, T. Yamaguchi, and G. Feingold (2025): Radiative forcing from the 2020 shipping fuel regulation is large but hard to detect. _Commun. Earth Environ._, 6(18), 1–11. [*doi:10.1038/s43247-024-01911-9*](https://doi.org/10.1038/s43247-024-01911-9)
