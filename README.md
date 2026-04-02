Quantum Brain Network Demo (QBN v7) — Absolute° Stability Framework

Author: Kemar Armando Morrison, MBUT Architect
License: GPL-2.0


Overview

This repository demonstrates the Quantum Brain Network (QBN) v7 framework for Absolute° Stability in multi-dimensional AI and field-governed systems. The demos and scripts showcase:
	•	Governed system stability with reproducible metrics.
	•	Identity-preserving dynamics using the Multi-Invariant Field Topology (MIFT) framework.
	•	Non-Isotropic Resonance (NIR) stabilisation and constrained gradient flows (IDIG).
	•	Orthogonality of entropy and invariant-preserving identity, illustrating robust, controlled evolution of state spaces.

This is a proof-of-concept repository illustrating theoretical and practical aspects of QBN v7. All demos are reproducible and anchored to governance-compliant invariants.


Key Features

1. Multi-Invariant Field Topology (MIFT)
	•	Implements MIFT core system (M, F, G, I) for identity-preserving dynamics.
	•	Supports L2 Norm, Mean, Spectral Centroid, Winding Number, Topological Charge, and Entropy invariants.
	•	Provides distance metrics, admissible transform checks, and identity-preserving trajectory evaluation.

2. Identity-Constrained Gradient Flow (IDIG)
	•	Gradient descent constrained to identity manifolds.
	•	Preserves invariants exactly while minimising energy.
	•	Re-anchor steps maintain high fidelity to invariant manifolds.

3. Non-Isotropic Resonance Kernel (NIR)
	•	Directional, sparse RBF kernel for resonance stabilization.
	•	Integrated with IDIG to maintain MIFT invariants while reducing field irregularities.
	•	Demonstrates convergence of rough fields to resonance-smooth equilibrium.

4. Tri-Layer Lyapunov Functional
	•	Combines energy and resonance contributions for a composite Lyapunov function.
	•	Provides a certificate of stability along simulated trajectories.

5. Demo Experiments
	•	Winding Number: topological identity preservation under phase rotations.
	•	IDIG Flow: energy minimization with invariant preservation.
	•	NIR Stabilisation: resonance-driven smoothing of rough fields.
	•	Entropy vs Identity: shows independence of entropy evolution from invariant-preserving dynamics.


Getting Started

Prerequisites
	•	Python ≥ 3.10
	•	numpy, matplotlib

Install dependencies via:

pip install numpy matplotlib


Running the Demos

The main entry point is:

python mift.py

This script runs all demo experiments:
	1.	Winding Number Demo — Section 4
	2.	IDIG Gradient Flow Demo — Section 6
	3.	NIR Resonance Stabilisation — Section 7
	4.	Entropy vs Identity Demo — Section 5

Visualizations are displayed for energy descent, invariant drift, and Lyapunov stability metrics.


Repository Structure

Quantum-Brain-Network-Demo/
├── mift.py           # Main demo + POC implementation
├── README.md         # This document
├── LICENSE           # GPL-2.0 license
├── EXTENDED_README.md  # Detailed theoretical notes
├── FEATURES_README.md  # Summary of modules & invariants
└── LIVE_PROOF_README.md # Validation results & anchoring


Citation

If you use this code for research, please cite:

Morrison, K.A. (2025). Multi-Invariant Field Topology & Quantum Brain Network Framework (QBN v7) — Absolute° Stability Proof-of-Concept.


Notes
	•	This repository demonstrates reproducibility and theoretical proofs, not production-ready systems.
	•	Designed for researchers and engineers exploring stability, identity-preserving dynamics, and topological constraints in AI fields.
	•	Visualizations are color-coded for clarity and invariant tracking.

