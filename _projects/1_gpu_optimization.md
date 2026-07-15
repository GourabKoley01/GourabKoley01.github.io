---
layout: page
title: GPU Optimization of an Euler Solver
description: Achieving maximum TFLOPs throughput using Python, NVIDIA Warp, and memory restructuring.
img: assets/img/project1_preview.jpg # You can replace this with a real image later
importance: 1
category: High-Performance Computing
---

This project focuses on optimizing a 2D Euler CFD solver built in Python. The goal was to maximize computational throughput on RTX hardware by refactoring the core loops and memory architecture.

### The Challenge
Standard Python implementations of CFD solvers often suffer from severe performance bottlenecks due to the Global Interpreter Lock (GIL) and inefficient memory access patterns.

### The Solution: Memory Architecture & NVIDIA Warp
To achieve significant speedups, I transitioned the code from a standard CPU-bound execution to GPU acceleration using **NVIDIA Warp** and **CuPy**. 

A critical component of this optimization was addressing memory bottlenecks. I refactored the underlying data structures from an **Array of Structures (AoS)** to a **Structure of Arrays (SoA)**. This transition allowed for highly efficient memory coalescing and significantly improved cache hit rates on the GPU.

### Profiling and Results
Using **NVIDIA Nsight Systems**, I profiled the execution timelines to identify and eliminate latency. By ensuring densely packed computation and overlapping memory transfers, the final iteration (version `opti8`) demonstrated massive performance gains over the baseline serial code.

*(Placeholder: Include a bar chart comparing baseline CPU execution time vs. `opti8` GPU execution time, or a screenshot of the densely packed Nsight Systems timeline here.)*
