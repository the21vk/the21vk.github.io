---
title: Research
feature_text: |
  ## Research
  Magnetic reconnection, plasma dynamics, and numerical astrophysics
feature_image: "/assets/images/Plasmoid-sheet.jpg"
excerpt: "Research interests and current projects."
aside: False
---

My research focuses on fluid and plasma dynamics in astrophysical settings, with a particular interest in how magnetic fields evolve, reconnect, and influence the large-scale behavior of plasmas.

## Magnetic Reconnection

Magnetic reconnection is a process in which magnetic field lines break and rejoin, changing the topology of the magnetic field and rapidly converting magnetic energy into kinetic energy, heat, and accelerated particles. It is relevant across a wide range of systems, from fusion devices and Earth's magnetosphere to solar flares, astrophysical jets, accretion flows, and gamma-ray bursts.

## Tearing Instability And Flux-Tube Reconnection

One strand of my current work studies tearing-mode-like instabilities in flux-tube-like magnetic configurations. The goal is to understand how reconnection develops when the magnetic field has finite structure along the third dimension, and how this compares with the better-known two-dimensional tearing instability.

This direction was explored in my 2025 [paper](https://doi.org/10.1017/S0022377825100494) with Pallavi Bhat in the Journal of Plasma Physics, where we studied the linear regime of the tearing instability in three-dimensional flux-tube-like magnetic configurations using a combination of (semi-) analytical linear stability calculations and direct numerical simulations. The analytical calculations identified expected growth-rate scalings, while the simulations tested those predictions and revealed the non-trivial magnetic-field geometry that emerges once reconnection begins.

## Plasmoid-mediated reconnection

While the standard tearing mode leads to slow reconnection, with reconnection rates that vanish at astrophysical Lundquist numbers, the plasmoid instability enables a much faster regime with reconnection rates that become nearly independent of the Lundquist number. My [paper](https://arxiv.org/abs/2605.18946) with Axel Brandenburg, accepted in the Journal of Plasma Physics, investigates how these plasmoid-mediated reconnection rates depend on the magnetic Prandtl number. We find that, in the fully nonlinear regime of the plasmoid instability, the reconnection rate depends only weakly on the magnetic Prandtl number — in contrast to earlier analytical expectations and numerical studies of the linear regime, which suggested a much stronger dependence.


## Numerical Dissipation And The Magnetic Prandtl Number

In [work](https://arxiv.org/abs/2610.41493) with Philipp Grete, I am asking how the effective magnetic Prandtl number of implicit large eddy simulations can be controlled through the choice of reconstruction scheme, and what this means for the reliability of simulations of MHD turbulence and reconnection that rely on numerical dissipation.

## Inverse Hall Cascade

With Axel Brandenburg, I have studied the inverse Hall cascade, characterising its evolutionary tracks and isochrones. This work is currently [submitted](https://arxiv.org/abs/2610.40092) to the Journal of Plasma Physics.

## MHD Turbulence And Dynamos

I also think about magnetohydrodynamic turbulence, dynamos, and their interplay with reconnection. Turbulence can stretch, fold, and amplify magnetic fields, while reconnection can alter turbulent cascades by changing magnetic topology and releasing magnetic energy. Understanding this feedback is important for interpreting magnetic-field evolution in astrophysical environments.

## Methods

My primary tools are high-resolution numerical simulations and pen-and-paper calculations. I work with custom as well as open-source codes like Dedalus, the Pencil Code, Athena++, AthenaK, AthenaPK and PLUTO to connect simplified theoretical problems with plasma behavior relevant to astrophysical systems.
