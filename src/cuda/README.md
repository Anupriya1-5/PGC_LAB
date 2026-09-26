# CUDA Matrix Multiplication

## Overview

This project implements matrix multiplication using **CUDA (Compute Unified Device Architecture)** to perform parallel computation on an NVIDIA GPU.

The program multiplies two square matrices of size **4000 × 4000**. CUDA threads are used to calculate the elements of the result matrix in parallel.

The program also measures:

- CUDA kernel execution time
- Total CUDA phase time
- Grid size
- Block size
- Result verification

---

## Objective

The main objective of this project is to understand and implement **GPU-based parallel matrix multiplication using CUDA**.

Instead of performing the complete computation sequentially on the CPU, the matrix multiplication workload is distributed among CUDA threads running on the GPU.

---

## Technologies Used

- **C/C++**
- **CUDA**
- **NVIDIA GPU**
- **CUDA Runtime API**
- **NVCC Compiler**

---

## Matrix Multiplication

Matrix multiplication is performed as:

```text
C = A × B
