---
layout: page
title: Immersed Boundary Method (IBM) Implementation
description: Developing and validating an IBM module for the DHARA fluid dynamics solver.
img: assets/img/3.jpg
importance: 3
category: Computational Fluid Dynamics
---

This collaborative project focuses on extending the capabilities of DHARA, a specialized computational fluid dynamics code, by integrating an Immersed Boundary Method (IBM) module.

### Implementation Strategy
The IBM approach allows for the simulation of complex solid boundaries within a standard Cartesian grid without requiring body-fitted meshing. This involved carefully designing the algorithm to ensure seamless interaction between the new forcing module and the existing DHARA solver architecture.

### Validation
To prove the numerical accuracy of the implementation, the module is validated against canonical CFD problems, such as flow past a stationary cylinder. The resulting drag/lift coefficients and wake structures are then benchmarked against established literature.

*(Placeholder: Insert standard validation case visualizations and the module interaction block diagram here.)*