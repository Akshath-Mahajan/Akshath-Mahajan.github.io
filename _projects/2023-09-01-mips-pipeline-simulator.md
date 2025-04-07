---
title: "MIPS 5-Stage Pipeline Simulator with Tomasulo"
collection: projects
permalink: /projects/mips-pipeline-simulator
excerpt: "Built a cycle-accurate MIPS simulator in C++ with Tomasulo's algorithm and advanced branch prediction."
date: 2023-09-01
end_date: 2023-11-30
categories: [Computer Architecture, Software Development]
tags: [mips, simulator, pipelining, tomasulo]
---

- Developed a **cycle-accurate simulator** for a 5-stage pipelined **MIPS processor** in C++, ensuring correct architectural state at every clock cycle  
- Designed mechanisms to address **control hazards** using **forwarding**, **stalling**, and **branch prediction**  
- Boosted efficiency with **2-level branch prediction**, improving performance by **20%** over baseline implementations  
- Implemented **Tomasulo's algorithm** with hazard handling for **out-of-order execution**, reducing cycle count by ~**27%** for compute-intensive workloads
