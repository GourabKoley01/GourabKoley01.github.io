---
layout: page
title: Aerothermodynamics of Scramjet Combustors
description: Bridging hardware testing and advanced numerical simulations for Mach 2 supersonic combustion at IIT Kharagpur.
img: assets/img/1.jpg
importance: 1
category: Computational Fluid Dynamics
---

### Project Overview & Acknowledgements
From January to May 2024, I had the privilege of working as a Research Intern at the Department of Aerospace Engineering, IIT Kharagpur. This research was conducted under the expert guidance of **Dr. Amardip Ghosh**, working closely alongside senior graduate student **Mr. Rajesh Kumar**[cite: 1]. 

This project was a unique opportunity to bridge the gap between physical hardware testing and advanced numerical simulations for high-speed propulsion systems, specifically focusing on cold-flow supersonic mixing and initial scramjet testing[cite: 1].

---

### The Physical Rig: Experimental Aerothermodynamics
Simulating supersonic flow on a computer is one thing; controlling it in a physical lab is another. Working directly on the supersonic combustion rig, I was deeply involved in the physical setup and data acquisition processes. 

To visualize the invisible complexities of the supersonic flow fields, we set up and calibrated precision **Schlieren and Shadowgraph imaging systems**[cite: 1]. We also characterized an inline, high-flow-rate vitiated air heater, which was critical for increasing the enthalpy of the flow before it entered the scramjet combustor[cite: 1]. 

Beyond the optics, I gained heavy hands-on experience by configuring a LabVIEW and Arduino-based Data Acquisition (DAQ) and Actuator Control system, assembling high-pressure fuel and oxidizer delivery lines, performing rigorous leak tests, and fitting high-temperature gaskets for the visualization windows[cite: 1].

> *[Placeholder: Insert your lab photos, rig setup, and Schlieren/Shadowgraph flow visualization videos here]*

---

### The Digital Twin: Computational Fluid Dynamics
In parallel with the experimental tests, I conducted rigorous numerical analysis to model the exact flow physics we were observing in the lab. 

Using **Pointwise**, I built complex 3D meshes of various scramjet combustor configurations, carefully iterating on different flame holders and expansion sections[cite: 1]. Once the grids were finalized, I executed cold-flow and reacting flow simulations using **ANSYS Fluent**[cite: 1]. 

To accurately capture the highly chaotic Hydrogen-Air combustion dynamics within the cavity-stabilized Mach 2 supersonic flow, I ran advanced **URANS, LES, and DES (Detached Eddy Simulations)** turbulence models[cite: 1]. Combining these high-fidelity simulations with our experimental lab data provided a comprehensive understanding of the combustor's performance capabilities.

> *[Placeholder: Insert Pointwise mesh wireframes, ANSYS Fluent reacting flow contour plots, and simulation videos here]*