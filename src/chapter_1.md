# Chapter 1 - Introduction

## Why Read This Book on CUDA?

In addition to covering the basics of how to program NVIDIA GPUs using CUDA through examples, this book focuses heavily on understanding how the software, compiler, and hardware work together, and how this all translates to end-to-end performance. That means we'll be looking at high-level CUDA and C++ code, low-level PTX and SASS assembly, and GPU performance counters.

In addition to implementing and optimizing algorithms in CUDA, we will construct microbenchmarks to demystify parts of the architecture. We will also look at how a kernel's performance can change with input size.

## What Does This Book Cover?

This book is primarily example-based, meaning we will introduce new topics through our examples. Some of the kernels we will be looking at in this book are for:

- Vector Addition
- Matrix Multiplication
- Histograms
- Sum Reduction
- Convolution
- Various Graph Algorithms

Through these kernels we will discuss topics like:

- Unified Memory + Prefetching
- Pinned Memory
- Shared Memory
- Tensor Cores
- Atomics
- Memory Barriers
- Global Synchronization
- Warp-level Intrinsics

## Background

Readers should have experience programming either C or C++. Like wise they are expected to have a background in computer architecture, and parallel programming.

## Setup

Linux O.S. (Ubuntu 20.04)
CUDA 10.0+
Turning Architecture GPU (7.0)
