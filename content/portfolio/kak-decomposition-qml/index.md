---
title: KAK Decomposition for Quantum Circuits
date: 2025-04-10
type: porfolio
# external_link: https://github.com/brian-hepler-phd/kak-decomposition-qml
tags:
  - Quantum Computing
  - Lie Groups
  - SU(4)
  - Circuit Decomposition
  - Teaching
---

A Python notebook exploring the KAK decomposition of SU(4) as a tool for visualizing and optimizing two-qubit quantum gates. This project illustrates how Lie group structure can inform circuit simplification and variational ansatz design in quantum machine learning.

<!--more-->

The KAK decomposition expresses any element of SU(4) as a product of local SU(2) × SU(2) gates and a diagonal entangling gate, and plays a central role in understanding two-qubit gate equivalence classes. Also created as supplemental material for the *Lie Groups with Applications* course with Quantum Formalism. 

This notebook includes:

- A pedagogical walkthrough of SU(4) → KAK decomposition via Lie theory
- A variational QML approach via Pennylane automatic differentiation
- Numerical simulation and timing benchmarks using `scipy.linalg`, and `pennylane`

Use cases:

- Design of efficient two-qubit gates
- Benchmarking quantum compilation algorithms
- Educational demo for quantum circuits and Lie algebras

 GitHub:  
 [kak-decomposition-qml](https://github.com/brian-hepler-phd/kak-decomposition-qml)