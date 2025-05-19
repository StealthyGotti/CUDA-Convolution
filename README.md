# University Project - 2D Convolution in CUDA

## Overview

This project aims to implement an efficient 2D convolution algorithm using CUDA. The implementation includes:
- **Parametric Mask Size:** The convolution mask size is configurable to provide flexibility.
- **Two Versions of the Algorithm:**
  - **Without Tiling:** A baseline implementation that does not use shared memory.
  - **With Tiling:** An optimized implementation using tiling to enhance performance.
- **Performance Analysis:** Detailed comparison between the two implementations, evaluating the impact of various tiling sizes on a specific GPU (Google Colab).

## Project Requirements

- **CUDA Implementation:** Develop the 2D convolution algorithm using CUDA.
- **Parametric Mask Size:** The mask size should be configurable as a parameter.
- **Tiling vs. Non-Tiling Comparison:** Demonstrate performance differences between:
  - The **non-tiling** implementation.
  - The **tiling** implementation.
- **Optimization for Google Colab GPU:** Analyze and optimize performance by experimenting with different tiling sizes on the provided GPU.
- **Google Colab File (.pynb):** Submit a Google Colab notebook that showcases the implementations and analysis.
  - *Note:* Submitting a file other than .pynb requires prior discussion.
- **Short Report (max 2 pages):** Provide a brief report that includes:
  - Experimental setup
  - Performance measurements
  - Explanation of design choices



