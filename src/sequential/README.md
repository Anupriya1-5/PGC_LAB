# Sequential Matrix Multiplication

## Overview

This program implements **sequential matrix multiplication** using the C programming language.

It multiplies two **4000 × 4000 matrices** using a traditional triple-nested loop. Unlike OpenMP, MPI, or CUDA implementations, the computation is performed sequentially by the CPU.

## Objective

The objective is to implement matrix multiplication using a sequential approach and measure its execution time.

This implementation can be used as a **baseline** for comparing the performance of parallel approaches such as OpenMP, MPI, and CUDA.

## Technologies Used

- C
- Standard C Library
- CPU

## Matrix Configuration

The program uses:

```text
Matrix A = 4000 × 4000
Matrix B = 4000 × 4000
Matrix C = 4000 × 4000
