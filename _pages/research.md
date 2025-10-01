---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  area {
    cursor: pointer;
  }
</style>

## Research Overview

I am an applied and computational mathematician with research interests in establishing the mathematical foundations of machine learning (ML) methods and their application in scientific computing. My research program offers new frameworks for **understanding** ML methods through established mathematical disciplines, **enhancing and innovating** methods based on those insights, and **principled application** to scientific computing problems.

My recent work centers **generative artificial intelligence** (AI) through **partial differential equations** (PDEs) arising from **mathematical control theory** and **optimal transport**. This perspective extends from deep learning architectures to scientific computing applications, leading to methodological improvements and analysis that yield a deeper understanding of state-of-the-art generative flow algorithms. Simultaneously, my study of generative AI produces algorithms for **trustworthy scientific machine learning**. In particular, my ideas for robust generative modeling enable probabilistic foundations for **operator learning**, grounding foundation models for differential equations in this framework and providing **uncertainty quantification** (UQ). UQ is a recurring theme in my research program, which provides tools for obtaining statistical guarantees, understanding stability of algorithms, and confidence in generative algorithms.

## Research Tree

Click on any area of the tree below to explore different aspects of my research:

<img src="/images/tree_website.png" alt="Research Tree" usemap="#research-tree" style="max-width: 100%; height: auto;">

<map name="research-tree">
  <area shape="rect" coords="580,295,1020,380" alt="Principled Generative AI">

  <area shape="rect" coords="590,395,980,490" alt="Mathematical Foundations">
  <area shape="rect" coords="100,515,390,595" alt="Mean-Field Games">
  <area shape="rect" coords="450,515,790,595" alt="Wasserstein Proximals">
  <area shape="rect" coords="860,515,1085,595" alt="PDE Analysis">
  <area shape="rect" coords="1190,515,1490,595" alt="Neural Architectures">

  <area shape="rect" coords="220,195,600,285" alt="Theory-informed Models">
  <area shape="rect" coords="35,110,400,190" alt="Manifold-learning Flows">
  <area shape="rect" coords="420,110,790,190" alt="Structure-informed Flows">
  <area shape="rect" coords="200,30,610,110" alt="Enhanced Diffusion Models">

  <area shape="rect" coords="1065,195,1325,285" alt="Scientific ML">
  <area shape="rect" coords="890,110,1200,190" alt="Operator Learning">
  <area shape="rect" coords="1210,110,1520,190" alt="Monte Carlo Methods">
  <area shape="rect" coords="1060,30,1320,110" alt="Optimal Control">
</map>

## Research Program

### Mathematical Principles of Generative AI: Foundations and Analysis

State-of-the-art generative models learn to evolve samples from a simple reference to complex target distributions through differential equations trained on finite example datasets (e.g., images, molecules). Understanding their mathematical foundations is critical for *reliable* downstream scientific applications. In my work *A mean-field games laboratory for generative modeling*, I show how **mean-field games** (MFGs) provide foundational mathematical principles for major classes of generative flows through PDEs. This mathematical foundation enables PDE-based analysis, yielding insights on data efficiency, training behavior, and approximation guarantees. My recent work on **Wasserstein proximal operators** reveals a deeper principle: robust generative flows compute so-called *proximal optimal transport divergences* — measures of discrepancy between probability distributions that interpolate between classical divergences and transport distances. The MFG provides a computable instantiation of this broader framework.

**Related publications:**
- **B.J. Zhang** and M.A. Katsoulakis. "A mean-field games laboratory for generative modeling." arXiv preprint arXiv:2304.13534, 2023. [[arXiv](https://arxiv.org/abs/2304.13534)]
- N. Mimikos-Stamatopoulos, **B.J. Zhang**, and M.A. Katsoulakis. "Score-based generative models are provably robust: an uncertainty quantification perspective." *Advances in Neural Information Processing Systems*, 37:63154-63183, 2024.
- Z. Chen, M.A. Katsoulakis, and **B.J. Zhang**. "Equivariant score-based generative models provably learn distributions with symmetries efficiently." arXiv preprint arXiv:2410.01244, 2024. [[arXiv](https://arxiv.org/abs/2410.01244)]
- R. Baptista, P. Birmpa, M.A. Katsoulakis, L. Rey-Bellet, and **B.J. Zhang**. "Proximal optimal transport divergences." arXiv preprint arXiv:2505.12097, 2025. [[arXiv](https://arxiv.org/abs/2505.12097)]
- **B.J. Zhang**, S. Liu, W. Li, M.A. Katsoulakis, and S.J. Osher. "Wasserstein proximal operators describe score-based generative models and resolve memorization." arXiv preprint arXiv:2402.06162, 2024. [[arXiv](https://arxiv.org/abs/2402.06162)]

### Mathematically-Informed Generative Modeling Methodology

The analyses provided by mean-field games, optimal transport, and information theory reveal mathematical *structure* which I have used to develop new mathematically-informed generative flows. These flows can be trained faster, more robustly, and with less data. My work demonstrates that well-posed formulations lead to robust generative models for learning distributions on low-dimensional manifolds, overcoming issues in training stability that arise from low-dimensional data and choices in model parametrization. Additionally, I have developed structure-preserving generative models that incorporate symmetries and prior knowledge, which enable more efficient learning of structured distributions. This theory-driven approach shows how understanding mathematical principles translates to practical improvements in generative modeling performance.

**Related publications:**
- H. Gu, M.A. Katsoulakis, L. Rey-Bellet, and **B.J. Zhang**. "Combining Wasserstein-1 and Wasserstein-2 proximals: robust manifold learning via well-posed generative flows." arXiv preprint arXiv:2407.11901, 2024. [[arXiv](https://arxiv.org/abs/2407.11901)]
- J. Birrell, M.A. Katsoulakis, L. Rey-Bellet, **B.J. Zhang**, and W. Zhu. "Nonlinear denoising score matching for enhanced learning of structured distributions." *Computer Methods in Applied Mechanics and Engineering*, 446:118226, 2025.
- K. Kan, X. Li, **B.J. Zhang**, T. Sahai, S.J. Osher, and M.A. Katsoulakis. "Optimal Control for Transformer Architectures: Enhancing Generalization, Robustness and Efficiency." To appear, NeurIPS 2025.

### Principled Generative Approaches to Scientific Machine Learning

My mathematically principled generative approaches enable new solutions to problems in scientific computing. One recent focus is a **generative perspective for operator learning**. Operator learning involves training statistical models to approximate solution operators of ordinary and partial differential equations, forming the basis for their *foundation models*. A major gap in ML-based operator learning methods is their *lack of trustworthiness* compared to traditional model-order reduction methods. My research addresses this by establishing a probabilistic framework for operator learning that provides uncertainty quantification for these methods. Additionally, I use connections between generative AI and control theory to address the curse of dimensionality in high-dimensional scientific computing problems, developing generative approaches for rare event simulation, sampling methods for Bayesian inference, and optimal control.

**Related publications:**
- **B.J. Zhang**, S. Liu, S.J. Osher, and M.A. Katsoulakis. "Probabilistic operator learning: generative modeling and uncertainty quantification for foundation models of differential equations." arXiv preprint arXiv:2509.05186, 2025. [[arXiv](https://arxiv.org/abs/2509.05186)]
- **B.J. Zhang**, T. Sahai, and Y.M. Marzouk. "A Koopman framework for rare event simulation in stochastic differential equations." *Journal of Computational Physics*, 456:111025, 2022.
- **B.J. Zhang**, Y.M. Marzouk, and K. Spiliopoulos. "Transport map unadjusted Langevin algorithms: Learning and discretizing perturbed samplers." *Foundations of Data Science*, 7(3):705-736, 2025.
- **B.J. Zhang**, Y.M. Marzouk, and K. Spiliopoulos. "Geometry-informed irreversible perturbations for accelerated convergence of Langevin dynamics." *Statistics and Computing*, 32(5):78, 2022.
- **B.J. Zhang**, T. Sahai, and Y. Marzouk. "Sampling via controlled stochastic dynamical systems." I (Still) Can't Believe It's Not Better! NeurIPS 2021 Workshop.
- P. Dupuis and **B.J. Zhang**. "Particle exchange Monte Carlo methods for eigenfunction and related nonlinear problems." arXiv preprint arXiv:2505.23456, 2025. [[arXiv](https://arxiv.org/abs/2505.23456)]


---

<div style="text-align: center; margin-top: 40px;">
<p style="font-size: 1.1em;">For a complete list of my publications, please visit my <a href="/publications/" style="color: #2b6cb0; font-weight: bold;">Publications page</a>.</p>
</div>