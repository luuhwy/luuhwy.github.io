---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

**EDUCATION BACKGROUND**

* Ph.D. in Computer Science and Technology, School of Computer Science, Peking University, 08/2024 - Present. Advisor: Prof. Yifeng Chen

* M. S. in Computer Technology, Institute of Computing Technology (ICT), Chinese Academy of Sciences, 09/2021 - 06/2024. Advisor: Prof. Haipeng Jia

* B. S. in Computer Science and Technology, School of Information Science and Engineering, Yunnan University, 09/2017 - 06/2021

<br>

**RESEARCH INTERESTS**

* High-performance computing
* Heterogeneous parallel software
* Sparse linear algebra and GPU acceleration

<br>

**RESEARCH PROJECTS**

* _**OpenGraphBLAS Algorithm Library**_, 09/2022 - 06/2024

  * Optimized sparse matrix-vector multiplication, PageRank, BFS, and related GraphBLAS kernels. The resulting implementations achieved up to 2.56x speedup over ArmPL on ARM processors and up to 2.31x speedup over Intel MKL on x86 processors.

* _**High-Performance Algorithm Library for OPPO Mobile Heterogeneous Platforms**_, 02/2022 - 09/2022

  * Proposed four general-purpose GLES optimization chains for embedded-GPU image processing, and designed an accelerated image processing library that achieved 19x, 88x, and 3x speedups over OpenCV across three representative algorithms.

* _**Microsoft Research Asia, Heterogeneous Computing Group**_, 06/2024 - 12/2024

  * Proposed MatXtract, a sparsity-aware matrix transformation method that accelerates SpMV by reordering sparse matrices and extracting dense subcomputations for Tensor Cores and CUDA Cores. On an NVIDIA A100 GPU, MatXtract outperformed cuSPARSE on 96.64% of 2,059 real-world sparse matrices, with a 1.98x average speedup and up to 8.83x maximum speedup.

* _**HMPP High-Performance Media Library**_, 10/2020 - 10/2021

  * Implemented HMPP, a high-performance ARM-based library for fundamental image geometric transformations. With numerical precision aligned against Intel IPP, HMPP improved performance by 108.08% to 435.5% over OpenCV.

<br>

**PUBLICATIONS**

- **Luhan Wang**, Haipeng Jia, Kun Li, Zongyuan He, Shengguo Li, Ting Cao, Yunxin Liu, Yunquan Zhang, Yifeng Chen. SPIKe: Generating Practical SpMV Kernels for Sparse Iterative Methods on GPUs. In Proceedings of the International Conference for High Performance Computing, Networking, Storage, and Analysis (SC '26).
- **Luhan Wang**, Kun Li, Yifeng Chen, Haipeng Jia, Yunquan Zhang, Ting Cao, Yunxin Liu. MatXtract: Sparsity-Aware Matrix Transformation via Cascaded Compute Density Extraction for TCU-Accelerated SpMV. In *ACM Transactions on Architecture and Code Optimization* (ACM TACO '25).
- **L. Wang**, H. Jia, L. Xu, C. Wei, K. Li, X. Jiang and Y. Zhang. 2024. VNEC: A Vectorized Non-Empty Column Format for SpMV on CPUs. In International Parallel \& Distributed Processing Symposium (IPDPS 2024).
- **L. Wang**, H. Jia, Y. Zhang, K. Li and C. Wei, "EgpuIP: An Embedded GPU Accelerated Library for Image Processing," 2022 IEEE 24th Int Conf on High Performance Computing \& Communications (HPCC 2022).
- **WANG Lu-han**, JIA Hai-peng, ZHANG Yun-quan, ZHANG Guang-ting. Study on Implementation and Optimization of ARM-based Image Geometric Transformation Library[J]. Computer Science, 2022, 49(10): 10-17.
- L. Xu, H. Jia, Y. Zhang, **L. Wang** and X. Jiang, "HAM-SpMSpV: an Optimized Parallel Algorithm for Masked Sparse Matrix-Sparse Vector Multiplications on multi-core CPUs," In the International ACM Symposium on High-Performance Parallel and Distributed Computing (HPDC 2024).
- Cunyang Wei, Haipeng Jia, Yunquan Zhang, Kun Li, **Luhan Wang**. 2022. *LBBGEMM: A Load-Balanced Batch GEMM Framework on ARM CPUs*. The 24th IEEE International Conference on High Performance Computing & Communications (**HPCC**), 2022.

<br>

**HONORS AND AWARDS**

- 2023 Merit Student, University of Chinese Academy of Sciences
- 2023 IEEE Access Reviewer
- 2022 Merit Student, University of Chinese Academy of Sciences
- 2020 National Scholarship for Postgraduates, Ministry of Education of the People's Republic of China
- 2020 Provincial Government Scholarship, Yunnan Provincial Government
- 2019 First Prize Scholarship, Yunnan University
