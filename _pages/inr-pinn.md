---
title: "Implicit Neural Representations & Physics-Informed Neural Networks"
permalink: /inr-pinn/
---

*Learning continuous neural function representations for complex signals and systems.*

---

## What are Implicit Neural Representations?

Implicit Neural Representations (INRs) model scientific data as continuous functions parameterized by neural networks. Rather than discretizing a field on a fixed mesh, an INR learns a mapping  
$x \mapsto u_\theta(x)$,  
allowing evaluation at arbitrary resolution while preserving differentiability with respect to inputs.

This function-space perspective enables resolution-independent modeling of high-dimensional physical fields, periodic signals, and parametric solution manifolds.

---

## What are Physics-Informed Neural Networks?

Physics-Informed Neural Networks (PINNs) incorporate governing equations directly into the learning objective. Given a differential equation  
$$
\mathcal{F}(u) = 0,
$$  
a PINN minimizes both data mismatch and the PDE residual computed via automatic differentiation.

This framework enables mesh-free solution of forward and inverse problems while integrating physical constraints into neural function approximation.

---

## Publications

### • DPM: A Novel Training Method for Physics-Informed Neural Networks in Extrapolation (AAAI 2021)

Demonstrated that standard Physics-Informed Neural Networks (PINNs) struggle to extrapolate time-dependent nonlinear PDE solutions beyond the training domain. To address this limitation, introduced DPM, a new training strategy that significantly improves temporal extrapolation performance. 

Authors: Jungeun Kim, KL, Dongeun Lee, Sheo Yon Jhin, and [Noseong Park](https://sites.google.com/view/noseong)  
Paper: [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16992/16799)

---

### • Hypernetwork-based Meta-Learning for Low-Rank Physics-Informed Neural Networks (NeurIPS 2023)

Introduced a hypernetwork-based meta-learning approach that generates low-rank physics-informed neural networks (PINNs) to efficiently solve parameterized PDEs. Improved computational efficiency and robustness while maintaining high accuracy across varying physical conditions.

Authors: Woojin Cho, KL, [Donsub Rim](https://dsrim.github.io/), and [Noseong Park](https://sites.google.com/view/noseong)  
Paper: [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/24f8dd1b8f154f1ee0d7a59e368eccf3-Paper-Conference.pdf)

---

### • Parameterized Physics-informed Neural Networks for Parameterized PDEs (ICML 2024)

Proposed Parameterized Physics-Informed Neural Networks (P²INNs), which incorporate latent parameter embeddings into PINNs to learn entire solution families of parameterized PDEs. Improved accuracy and generalization across varying parameter regimes compared to standard PINN approaches.

Authors: Woojin Cho, Minju Jo, Haksoo Lim, Kookjin Lee, Dongeun Lee, Sanghyun Hong, and [Noseong Park](https://sites.google.com/view/noseong)  
Paper: [[Paper]](https://proceedings.mlr.press/v235/cho24b.html)

---
