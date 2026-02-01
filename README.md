# **RISC‑V Vector Processor Primer**
*A Modern Guide to the RISC‑V Vector Extension (RVV)*
Published by **Simplex Micro**

Welcome to the online edition of the **RISC‑V Vector Processor Primer**, a comprehensive guide to understanding, implementing, and applying the RISC‑V Vector Extension (RVV). This site hosts the full book in chapter‑based form, published openly for engineers, architects, students, and practitioners who want a clear and practical understanding of modern vector computation.

The primer explains RVV from first principles through real hardware design, performance analysis, and the architectural path toward matrix acceleration. It is grounded in decades of industry experience and written to be both accessible and technically rigorous.

---

## **Authors**

### **Dr. Thang Tran — Founder, CEO & CTO**
A microprocessor architect with over 40 years of experience across x86, Arm, PowerPC, ARC, and RISC‑V. Dr. Tran led the design of the AndesCore NX27V—the first commercial RISC‑V vector processor—and has held senior roles at AMD, Texas Instruments, Andes Technology, and Condor Computing.

### **Paul Miller — Senior Fellow of Architecture and Design**
A senior microprocessor designer with 35+ years of experience in RISC, x86, ARM, DSP, and GPU architectures. Paul has designed floating‑point units, SIMD engines, and AI accelerators, and now contributes to Simplex Micro’s RISC‑V Vector and Matrix processor development.

### **Jonah McLeod — Editor**
An award‑winning editor with 30+ years of Silicon Valley experience. Jonah has led major high‑tech publications and held senior communications roles at Virage Logic, Denali Software, Kilopass Technology, and Andes Technology.

---

## **Chapters**

- **Chapter 1 — RISC‑V Vector Extension Demystified**  
  A conceptual foundation: vector vs SIMD, time–space duality, chaining, strip mining, and the mental models needed to understand RVV.

- **Chapter 2 — From Concept to Core: A RISC‑V Vector Processor in Silicon**  
  How RVV maps into real hardware: lanes, VRF design, port pressure, micro‑ops, and a concrete 512‑bit implementation.

- **Chapter 3 — RISC‑V Vector Extension Fundamentals**  
  SEW, LMUL, VLEN, VLMAX, masking, vtype, vsetvl, register grouping, functional units, memory behavior, and CSR semantics.

- **Chapter 4 — Vector Instructions**  
  Memory operations, compute operations, widening/narrowing, fixed‑point and floating‑point arithmetic, reductions, masks, permutations, and register movement.

- **Chapter 5 — Matrix Computation and Performance Analysis**  
  Single‑precision GEMM, low‑precision MAC pipelines, chaining, memory bandwidth, tiling, and deterministic execution for AI workloads.

- **Chapter 6 — From Vectors to Matrices**  
  Why matrix workloads expose structural limits of 1‑D vectors, the architectural rationale for matrix tiles, PE arrays, tile geometry, and the emerging RISC‑V Matrix Extension.

---

## **About This Publication**

This primer is published by **Simplex Micro** as part of its mission to advance open, accessible technical education in RISC‑V vector and matrix processing. The content is released incrementally and updated as the book evolves.

**Source repository:**  
https://github.com/simplex-micro/riscv-vector-primer

**Online edition:**  
https://simplex-micro.github.io/riscv-vector-primer/

---

## **License**

© 2025 Dr. Thang Minh Tran. All rights reserved.  
No part of this book may be reproduced without permission.

This work is licensed under the Creative Commons
Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0).
See the LICENSE file for details.
