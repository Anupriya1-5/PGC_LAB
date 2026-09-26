# OpenMP Matrix Multiplication

## Overview

This program implements parallel matrix multiplication using **OpenMP**.

It multiplies two **4000 × 4000 matrices** using multiple CPU threads. The `#pragma omp parallel for` directive divides the outer loop iterations among available OpenMP threads.

## Objective

The objective is to perform matrix multiplication using **CPU-based parallel processing with OpenMP** and measure the execution time.

## Technologies Used

- C
- OpenMP
- GCC Compiler
- Multicore CPU

## Matrix Configuration

```text
Matrix A = 4000 × 4000
Matrix B = 4000 × 4000
Matrix C = 4000 × 4000
