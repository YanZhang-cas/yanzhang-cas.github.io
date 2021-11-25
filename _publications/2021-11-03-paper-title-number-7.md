---
title: "An optimized Eulerian–Lagrangian method for two-phase flow with coarse particles: Implementation in open-source field operation and manipulation, verification, and validation"
collection: publications
permalink: /publication/2021-11-03-paper-title-number-7
excerpt: 'A coarse particle simulation method (based on OpenFOAM).'
date: 2021-11-03
venue: 'Physics of Fluids'
paperurl: 'https://aip.scitation.org/doi/abs/10.1063/5.0067553'
citation: 'Y. Zhang, X.B. Lu, X.H. Zhang. (2020). &quot;An optimized Eulerian–Lagrangian method for two-phase flow with coarse particles: Implementation in open-source field operation and manipulation, verification, and validation.&quot; <i>Physics of Fluids</i>. 33: 113307.'
---
The solid–liquid two-phase flow with coarse particles is ubiquitous in natural phenomena and engineering practice, which is characterized by coarse particles, high particle concentration, and large particle size distribution. In this work, the numerical models describing two-phase flows are reviewed, which given that the Eulerian–Lagrangian method is applicable in this work. Then, some modified models are proposed for the situation where the conventional Eulerian–Lagrangian method is not applicable to deal with coarse particles. The continuous phase equations of liquid are solved based on the finite volume method. The pressure implicit with splitting of operators algorithm for solving the Navier–Stokes (N–S) equations of the pseudo-single-phase flow, considering phase fraction and momentum exchange source term, is proposed. The discrete coarse particle is tracked in the Lagrangian method. A virtual mass distribution function is proposed for calculating coarse particle volume fraction. A weighted function method relating to the particle size is given for the interpolation between the Eulerian and Lagrangian fields. The barycentric coordinates are introduced into the particle localization. All the modified models are algorithmically implanted in the open-source field operation and manipulation (OpenFOAM) as a new solver named coarse discrete particle method FOAM (CoarseDPMFoam). Subsequently, the applicability of the numerical simulation method is verified by some typical test cases. The proposed numerical simulation method provides new ideas and methods for the mechanism investigation and engineering application of the two-phase flow with coarse particles.

[Download paper here](https://aip.scitation.org/doi/abs/10.1063/5.0067553)

Recommended citation: Y. Zhang, X.B. Lu, X.H. Zhang. (2020). &quot;An optimized Eulerian–Lagrangian method for two-phase flow with coarse particles: Implementation in open-source field operation and manipulation, verification, and validation.&quot; <i>Physics of Fluids</i>. 33: 113307. 