GPU-Accelerated Secp256k1 Batch Verification
This repository contains the C++ and compute shader implementation for offloading Bitcoin block signature verification (secp256k1) from the CPU to the GPU.

Architecture Overview
By utilizing low-level hardware APIs, this project batches ECC (Elliptic Curve Cryptography) signature data and processes the mathematical verification concurrently on consumer-grade GPUs, minimizing CPU bottlenecks during Initial Block Download.

Current Status

Phase 1 (Active): Scaffolding the CPU-to-GPU memory transfer pipeline and compute shader integration.

Phase 2: Compute shader implementation for batched verification.

Phase 3: Node integration and performance benchmarking.
