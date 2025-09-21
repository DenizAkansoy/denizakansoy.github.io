---
title: "DebrisPy"
date: 2025-09-21
tags: ["software","debris discs","surface density","eccentricity distributions"]
description: "An open-source Python package for modelling debris-disc surface density profiles using semi-analytic methods."
summary: "DebrisPy provides a flexible, modular framework for computing azimuthally averaged surface density (ASD) profiles in debris discs, building on the semi-analytical formalism of Rafikov (2023). It supports arbitrary eccentricity distributions, adaptive integration, and Monte Carlo sampling, making it a useful tool for researchers exploring disc structure and evolution."
cover:
  image: "debrisdisc.png"     
  alt: "DebrisPy example"
  relative: true
---

##### Links

+ [GitHub Repository](https://github.com/DenizAkansoy/DebrisPy)  
+ [Mathematical framework (Rafikov 2023, *MNRAS*)](https://academic.oup.com/mnras/article/519/4/5607/6845736)  

---

##### Overview

**DebrisPy** is an open-source Python package with the goal of studying the structure and evolution of debris discs. The package implements the analytic formalism introduced by [Rafikov (2023)](https://academic.oup.com/mnras/article/519/4/5607/6845736), which establishes a direct connection between the azimuthally averaged surface density (ASD) of a disc and the underlying distribution of semi-major axes and eccentricities of its constituent particles.  

By working semi-analytically, DebrisPy offers a more efficient and robust alternative to traditional Monte Carlo approaches, while still including Monte Carlo methods for validation. The modular design of the package allows users to explore a wide range of eccentricity distributions and surface density profiles, making it adaptable to different astrophysical contexts.

Beyond reproducing the results of Rafikov (2023), DebrisPy extends the formalism with several numerical features. These include adaptive quadrature routines for accurate integration, curvature-based grid refinement to resolve sharp features in eccentricity space, and tools for convolution in order to compare theoretical results with resolution-limited observational data. Together, these capabilities make DebrisPy a flexible and general-purpose framework for researchers studying how different dynamical processes shape the surface density of debris disc.

---

##### Features

- Supports **arbitrary eccentricity distributions**.
- **Adaptive integration** routines for efficiency and accuracy.  
- **Curvature-based grid refinement** for resolving sharp features.  
- Both 1D and 2D **Monte Carlo sampling** to validate analytic solutions.  
- Modular design for easy extension.  

---

##### Example Figure

![](debrispy.png)  

*A synthetic surface density profile generated with DebrisPy.*  
