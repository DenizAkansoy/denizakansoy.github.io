---
title: "Modelling Shadows in Scattered Light Observations as Signals from Companions in Protoplanetary Discs"
date: 2025-07-01
tags: ["protoplanetary discs","scattered light","radiative transfer","planet–disc interactions"]
author: ["Deniz Akansoy","Helen Petrou","Giulia Ballabio","Anna Penzlin"]
description: "3D radiative transfer simulations showing how embedded companions can cast detectable shadows, providing an indirect method to constrain companion masses and positions."
summary: "Using radmc-3d simulations, we demonstrate that companions ≥14 MJup cast detectable shadows in protoplanetary discs for a flared disc. For the studied disc geometry, we derive an empirical scaling between companion mass, orbital distance, and shadow morphology, suggesting shadows may serve as indirect diagnostics of massive companions."
cover:
  image: "shadow_temp.png"        
  alt: "Temperature maps of a disc with a 30 MJup companion at 5 au. Top: face-on view of the dust temperature distribution, illustrated at the mid plane, 3H/r, 4H/r, and 5H/r in each panel, respectively. Bottom: cross-section of the temperature map along a cut at the azimuthal position of the planet."
  relative: true
editPost:
  URL: "https://doi.org/10.1093/mnras/staf925"
  Text: "Monthly Notices of the Royal Astronomical Society"

---

##### Download

+ [Published paper (MNRAS)](https://doi.org/10.1093/mnras/staf925)  
+ [Preprint (arXiv:2506.04415)](https://arxiv.org/abs/2506.04415)  
+ Code available upon request  

---

##### Abstract

Over the past decade, Spectro-Polarimetric High-contrast Exoplanet REsearch scattered light observations of protoplanetary discs have revealed previously unseen features with unprecedented resolution. One such feature is radial streaks of reduced brightness that are commonly interpreted as shadows. A possible cause for these shadows is an embedded companion within the disc.  

In this work, we use 3D radiative transfer simulations with **radmc-3d** to investigate the shadowing effects of embedded companions across a range of orbital distances (5–30 au) and companion masses (0.5–30 MJup). We model μm dust grains, which are well coupled to the gas, to produce synthetic scattered light images of the disc. Companions with masses ≥14 MJup consistently cast detectable shadows throughout the disc.  

We derive an empirical solution describing the width and depth of the shadow as functions of companion mass and location. This scaling suggests that shadow features observed in scattered light images could serve as reliable indicators of companion mass and position, providing an indirect method for identifying and characterizing otherwise challenging-to-detect objects within these discs. Additionally, companion shadows influence the disc thermal structure, with notable cooling effects that could impact disc chemistry and the dynamics of planet formation.

---

##### Figure: Simulated scattered light image of the PDS 70 system. The white scale bar represents a distance of 20 au.

![](shadow_pds70.png)

---

##### Citation

Akansoy, D., Petrou, H., Ballabio, G., & Penzlin, A. (2025). *Modelling shadows in scattered light observations as signals from companions in protoplanetary discs*. **Monthly Notices of the Royal Astronomical Society, 540**(4), 3186–3203. https://doi.org/10.1093/mnras/staf925  

```bibtex
@article{Akansoy2025,
  author  = {Akansoy, Deniz and Petrou, Helen and Ballabio, Giulia and Penzlin, Anna},
  title   = {Modelling shadows in scattered light observations as signals from companions in protoplanetary discs},
  journal = {Monthly Notices of the Royal Astronomical Society},
  volume  = {540},
  number  = {4},
  pages   = {3186--3203},
  year    = {2025},
  month   = {July},
  doi     = {10.1093/mnras/staf925},
  url     = {https://arxiv.org/abs/2506.04415}
}
