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

<div style="display: flex; gap: 30px; align-items: start;">
<div style="flex: 2;">
State-of-the-art generative models learn to evolve samples from a simple reference to complex target distributions through differential equations trained on finite example datasets (e.g., images, molecules). Understanding their mathematical foundations is critical for <em>reliable</em> downstream scientific applications. In my work <em>A mean-field games laboratory for generative modeling</em>, I show how <strong>mean-field games</strong> (MFGs) provide foundational mathematical principles for major classes of generative flows through PDEs. This mathematical foundation enables PDE-based analysis, yielding insights on data efficiency, training behavior, and approximation guarantees. My recent work on <strong>Wasserstein proximal operators</strong> reveals a deeper principle: robust generative flows compute so-called <em>proximal optimal transport divergences</em> — measures of discrepancy between probability distributions that interpolate between classical divergences and transport distances. The MFG provides a computable instantiation of this broader framework.
</div>
<div style="flex: 1; padding-left: 20px;">
<p style="font-size: 0.9em; color: #555; margin-top: 0; margin-bottom: 10px;"><strong>Related publications:</strong></p>
<ul style="font-size: 0.85em; line-height: 1.5; list-style: none; padding: 0; margin: 0; color: #555;">
<li style="margin-bottom: 10px;">• <strong>B.J. Zhang</strong> and M.A. Katsoulakis (2023). "A mean-field games laboratory for generative modeling." <a href="https://arxiv.org/abs/2304.13534" target="_blank">[arXiv]</a></li>
<li style="margin-bottom: 10px;">• N. Mimikos-Stamatopoulos, <strong>B.J. Zhang</strong>, and M.A. Katsoulakis (2024). "Score-based generative models are provably robust." <em>NeurIPS</em>.</li>
<li style="margin-bottom: 10px;">• Z. Chen et al. (2024). "Equivariant score-based generative models." <a href="https://arxiv.org/abs/2410.01244" target="_blank">[arXiv]</a></li>
<li style="margin-bottom: 10px;">• R. Baptista et al. (2025). "Proximal optimal transport divergences." <a href="https://arxiv.org/abs/2505.12097" target="_blank">[arXiv]</a></li>
<li>• <strong>B.J. Zhang</strong> et al. (2024). "Wasserstein proximal operators." <a href="https://arxiv.org/abs/2402.06162" target="_blank">[arXiv]</a></li>
</ul>
</div>
</div>

### Mathematically-Informed Generative Modeling Methodology

<div style="display: flex; gap: 30px; align-items: start;">
<div style="flex: 2;">
The analyses provided by mean-field games, optimal transport, and information theory reveal mathematical <em>structure</em> which I have used to develop new mathematically-informed generative flows. These flows can be trained faster, more robustly, and with less data. My work demonstrates that well-posed formulations lead to robust generative models for learning distributions on low-dimensional manifolds, overcoming issues in training stability that arise from low-dimensional data and choices in model parametrization. Additionally, I have developed structure-preserving generative models that incorporate symmetries and prior knowledge, which enable more efficient learning of structured distributions. This theory-driven approach shows how understanding mathematical principles translates to practical improvements in generative modeling performance.
</div>
<div style="flex: 1; padding-left: 20px;">
<p style="font-size: 0.9em; color: #555; margin-top: 0; margin-bottom: 10px;"><strong>Related publications:</strong></p>
<ul style="font-size: 0.85em; line-height: 1.5; list-style: none; padding: 0; margin: 0; color: #555;">
<li style="margin-bottom: 10px;">• H. Gu et al. (2024). "Combining Wasserstein-1 and Wasserstein-2 proximals." <a href="https://arxiv.org/abs/2407.11901" target="_blank">[arXiv]</a></li>
<li style="margin-bottom: 10px;">• J. Birrell et al. (2025). "Nonlinear denoising score matching." <em>CMAME</em>.</li>
<li>• K. Kan et al. (2025). "Optimal Control for Transformer Architectures." <em>NeurIPS 2025</em>.</li>
</ul>
</div>
</div>

### Principled Generative Approaches to Scientific Machine Learning

<div style="display: flex; gap: 30px; align-items: start;">
<div style="flex: 2;">
My mathematically principled generative approaches enable new solutions to problems in scientific computing. One recent focus is a <strong>generative perspective for operator learning</strong>. Operator learning involves training statistical models to approximate solution operators of ordinary and partial differential equations, forming the basis for their <em>foundation models</em>. A major gap in ML-based operator learning methods is their <em>lack of trustworthiness</em> compared to traditional model-order reduction methods. My research addresses this by establishing a probabilistic framework for operator learning that provides uncertainty quantification for these methods. Additionally, I use connections between generative AI and control theory to address the curse of dimensionality in high-dimensional scientific computing problems, developing generative approaches for rare event simulation, sampling methods for Bayesian inference, and optimal control.
</div>
<div style="flex: 1; padding-left: 20px;">
<p style="font-size: 0.9em; color: #555; margin-top: 0; margin-bottom: 10px;"><strong>Related publications:</strong></p>
<ul style="font-size: 0.85em; line-height: 1.5; list-style: none; padding: 0; margin: 0; color: #555;">
<li style="margin-bottom: 10px;">• <strong>B.J. Zhang</strong> et al. (2025). "Probabilistic operator learning." <a href="https://arxiv.org/abs/2509.05186" target="_blank">[arXiv]</a></li>
<li style="margin-bottom: 10px;">• <strong>B.J. Zhang</strong> et al. (2022). "Koopman framework for rare event simulation." <em>JCP</em>.</li>
<li style="margin-bottom: 10px;">• <strong>B.J. Zhang</strong> et al. (2025). "Transport map unadjusted Langevin algorithms." <em>FoDS</em>.</li>
<li style="margin-bottom: 10px;">• <strong>B.J. Zhang</strong> et al. (2022). "Geometry-informed irreversible perturbations." <em>Stat. Comput.</em></li>
<li style="margin-bottom: 10px;">• <strong>B.J. Zhang</strong> et al. (2021). "Sampling via controlled stochastic dynamical systems." <em>NeurIPS Workshop</em>.</li>
<li>• P. Dupuis and <strong>B.J. Zhang</strong> (2025). "Particle exchange Monte Carlo methods." <a href="https://arxiv.org/abs/2505.23456" target="_blank">[arXiv]</a></li>
</ul>
</div>
</div>


---

<div style="text-align: center; margin-top: 40px;">
<p style="font-size: 1.1em;">For a complete list of my publications, please visit my <a href="/publications/" style="color: #2b6cb0; font-weight: bold;">Publications page</a>.</p>
</div>