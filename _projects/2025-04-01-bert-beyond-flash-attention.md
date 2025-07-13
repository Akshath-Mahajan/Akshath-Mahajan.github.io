---
title: "Optimizing BERT Beyond FlashAttention"
collection: projects
permalink: /projects/optimizing-bert-beyond-flashattention
excerpt: "GPU optimizations for BERT-like models using Kernel Fusion"
date: 2025-02-01
end_date: 2025-04-01
categories: [Deep Learning, NLP, CUDA, GPU, Architecture]
tags: [GPU, BERT, Deep Learning, CUDA]
---

- Accelerated BERT inference by 34% on NVIDIA T4 GPU by fusing the GEMM, bias-add, and GELU into a single kernel.
- Reduced training step time by 38% using the fused kernel in back-propagation, speeding up model iteration and lowering projected GPU cloud costs.
- Identified bottlenecks consuming ~83% of GPU time through profiler, ensuring maximum return on optimization effort.