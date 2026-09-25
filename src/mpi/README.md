# MPI Matrix Multiplication and Communication

## Overview

This project contains MPI-based programs for demonstrating parallel matrix multiplication and point-to-point communication using the Message Passing Interface (MPI).

## Programs

### 1. MPI Matrix Multiplication

The program performs parallel multiplication of two **4000 × 4000 matrices** using multiple MPI processes.

The matrix is distributed among processes using `MPI_Scatter`. Matrix B is shared with all processes using `MPI_Bcast`. Each process computes a portion of the result, and the results are combined using `MPI_Gather`.

### MPI Operations Used

- `MPI_Init()` – Initializes the MPI environment.
- `MPI_Comm_rank()` – Gets the rank of each process.
- `MPI_Comm_size()` – Gets the total number of processes.
- `MPI_Scatter()` – Distributes rows of matrix A.
- `MPI_Bcast()` – Broadcasts matrix B to all processes.
- `MPI_Gather()` – Collects the calculated matrix portions.
- `MPI_Barrier()` – Synchronizes the processes.
- `MPI_Wtime()` – Measures execution time.
- `MPI_Finalize()` – Terminates the MPI environment.

### Matrix Configuration

```text
Matrix A = 4000 × 4000
Matrix B = 4000 × 4000
Matrix C = 4000 × 4000
