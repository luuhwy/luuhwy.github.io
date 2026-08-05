---
layout: archive
permalink: /projects/
title: "Research Projects"
author_profile: false
redirect_from:
  - /projects
---

* _**OpenGraphBLAS Algorithm Library**_

  09/2022 - 06/2024

  * GraphBLAS represents graphs as sparse adjacency matrices and expresses graph algorithms in the language of linear algebra. I optimized sparse matrix-vector multiplication, PageRank, BFS, and related kernels. On ARM processors, these optimizations achieved up to 2.56x speedup over ArmPL, with a 1.76x average speedup; on x86 processors, they achieved up to 2.31x speedup over Intel MKL, with a 1.54x average speedup.

---

* _**High-Performance Algorithm Library for OPPO Mobile Heterogeneous Platforms**_

  02/2022 - 09/2022

  * GLES, with its low hardware overhead, is a strong fit for high-performance image processing on embedded GPUs. I proposed four general-purpose optimization chains to guide GLES-based image processing, and designed an embedded GPU-accelerated image processing library around them. Across three representative algorithms, the library achieved 19x, 88x, and 3x speedups over OpenCV.

---

* _**HMPP High-Performance Media Library**_

  10/2020 - 10/2021

  * OpenCV can obtain substantial acceleration on Intel platforms by using the low-level IPP library. I focused on fundamental image geometric transformation algorithms and implemented HMPP, a high-performance algorithm library for ARM platforms. With numerical precision aligned against Intel IPP, HMPP improved performance by 108.08% to 435.5% over OpenCV.

---

* _**Microsoft Research Asia**_

  06/2024 - 12/2024

  * Research intern, Heterogeneous Computing Group. I used heterogeneous on-GPU compute resources, including Tensor Cores and CUDA Cores, to accelerate scientific computing workloads. I proposed MatXtract, which perceives matrix sparsity, reorders sparse matrices, and extracts dense subcomputations to optimize sparse matrix-vector multiplication (SpMV). Evaluated on an NVIDIA A100 GPU across 2,059 real-world sparse matrices, MatXtract outperformed cuSPARSE on 96.64% of test cases, with a 1.98x average speedup and up to 8.83x maximum speedup.
