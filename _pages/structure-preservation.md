---
title: "Structure-Preserving Dynamics"
permalink: /sp/
---

# Structure-Preserving Dynamics Modeling  
*Learning dynamical systems that obey thermodynamics by construction.*

---

## What is Structure-Preservation?

Structure-preserving dynamics modeling builds machine learning models that respect the geometric and thermodynamic laws governing physical systems. Rather than learning arbitrary dynamics  
\[
\dot{x} = f_\theta(x),
\]
we parameterize models so that invariants such as energy conservation or entropy production hold exactly by construction. This ensures physically realizable trajectories and improved extrapolation beyond the training regime.

These approaches sit between black-box neural ODEs and fully specified physics models. Without assuming known governing equations, we enforce universal principles such as the first and second laws of thermodynamics through algebraic constraints (e.g., skew-symmetry, positive semidefiniteness, degeneracy conditions). The result is improved stability, robustness, and interpretability compared to penalty-based methods.

---

## What is GENERIC?

The GENERIC (General Equation for Non-Equilibrium Reversible–Irreversible Coupling) formalism separates reversible and irreversible dynamics:

\[
\dot{x} = L(x)\nabla E(x) + M(x)\nabla S(x),
\]

where \(L\) is skew-symmetric (reversible structure), \(M\) is symmetric positive semidefinite (dissipative structure), \(E\) is energy, and \(S\) is entropy. The degeneracy conditions  
\[
L\nabla S = 0, \quad M\nabla E = 0
\]
guarantee energy conservation and non-decreasing entropy.

By learning \(L\), \(M\), \(E\), and \(S\) from data while preserving these algebraic properties, we obtain models that are thermodynamically consistent by construction.

---

## Selected Publications

### • Machine Learning Structure-Preserving Brackets for Forecasting Irreversible Processes (NeurIPS 2021)

Introduced a learnable parameterization of dissipative brackets for irreversible systems within the metriplectic/GENERIC framework. The method guarantees energy conservation and entropy production while outperforming black-box and penalty-based models in long-term forecasting.

Authors: KL, Nat Trask, and Panos Stinis 

---

### • Structure-Preserving Sparse Identification of Nonlinear Dynamics (MSML 2022)

Unified SINDy with neural ODE training to enable sparse discovery of black-box and bracket-based dynamics. The framework produces interpretable models while preserving Hamiltonian or GENERIC structure, improving stability and forecasting for chaotic systems.


---

### • Reversible and Irreversible Bracket-Based Dynamics for Deep Graph Neural Networks (NeurIPS 2023)

Extended bracket-based dynamics to graph neural networks using exterior calculus. Developed Hamiltonian, gradient, double-bracket, and metriplectic architectures, clarifying the role of reversibility and dissipation in deep GNN performance.


---

### • Efficiently Parameterized Neural Metriplectic Systems (ICLR 2025)

Developed a scalable parameterization of metriplectic systems with quadratic complexity in state dimension and dissipation rank. The approach preserves energy and entropy by construction while improving efficiency and generalization.


---

### • Thermodynamically Consistent Latent Dynamics Identification for Parametric Systems (2025)

Integrated autoencoders with parametric GENERIC neural networks for reduced-order modeling. The method preserves free energy conservation and entropy production across parameter space, achieving significant speedups with physically interpretable latent dynamics.


---

### • Meta-Learning Structure-Preserving Dynamics (2025)

Introduced a modulation-based meta-learning framework for conservative and dissipative systems. The model adapts across parametric families without retraining while preserving physical structure exactly.


---

