---
layout: page
title: Multi-GPU Scaling of VYOM (NSM Hackathon)
description: Achieving a 6.61x computational speedup using MPI and multi-GPU optimization.
img: assets/img/1.jpg
importance: 1
category: High-Performance Computing
---

During the National Supercomputing Mission (NSM) Open Hackathon in Goa, I worked on accelerating and optimizing **VYOM**, a heavy computational fluid dynamics code. The primary objective was to transition the code to effectively utilize modern supercomputing architectures.

### The Scaling Challenge
As computational grids grow in size and complexity, single-GPU or CPU-bound execution becomes a severe bottleneck. The challenge was to distribute the computational load of the VYOM code across multiple GPUs without losing efficiency to data-transfer latency between the nodes.

### MPI and Multi-GPU Optimization
To solve this, I implemented a robust Message Passing Interface (MPI) architecture to handle the communication between multiple GPUs. 

The optimization required deep profiling of the code to identify the latency bottlenecks. By carefully structuring the MPI calls and overlapping the compute operations with the communication phases, I was able to drastically reduce idle GPU time.

### Results
The multi-GPU implementation achieved a massive **6.61x speedup** compared to the baseline code. This optimization not only proved the scalability of the VYOM code but also demonstrated the ability to efficiently harness high-performance cluster resources.

*(Placeholder: Insert scaling graphs showing the performance improvements as the node count increased, or photos from the Hackathon presentation in Goa here.)*