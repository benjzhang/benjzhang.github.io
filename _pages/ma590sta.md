---
layout: archive
title: "MATH 590STA: Introduction to Mathematical Machine Learning"
permalink: /ma590sta/
author_profile: false
---

<!-- {% include base_path %}
 -->
 
 
 <!-- <span style="color:red"> ***As of 08 November 2023, enrollment for the class is full. However, if you are still interested in signing up for the course, please email us at bjzhang@umass.edu and ziyuchen@umass.edu.***  </span> -->

 [<img align="right" width="400" src="https://benjzhang.github.io/files/ma590sta_poster.png" />](https://benjzhang.github.io/files/ma590sta_poster.png)
## Spring 2024
MWF 1:25-2:15PM in LGRT 141

## Instructors and contact
Benjamin Zhang, LGRT 1632, bjzhang@umass.edu

[Ziyu Chen](https://sites.google.com/view/ziyu-chen), LGRT 1630, ziyuchen@umass.edu



## Course description

This course will provide an introduction to machine learning from a mathematical perspective. The primary objective of this course is to cultivate in students a sense of mathematical curiosity and equip them with the skills to ask mathematical questions when studying machine learning algorithms. Classical supervised learning methods will be presented and studied using the tools from information theory, statistical learning theory, optimization, and basic functional analysis. The course will cover three categories of machine learning approaches: linear methods, kernel-based methods, and deep learning methods, each applied to regression, classification, and dimension reduction. Coding exercises will be an essential part of the course to empirically study  strengths and weakness of methods. 

## Prerequisites
This class is intended for advanced undergraduate and early graduate students. We expect a strong command of probability, multivariable calculus, and linear algebra at the level of STAT 515, MATH 233, and MATH 545, or permission of instructor. Basic programming experience is assumed. *Recommended*: Familiarity of numerical methods at the level of MATH 551. Some recommended references will be posted before the beginning of the semester. 

## Textbook 
No required textbook. We will assign selected readings from *Probabilistic Machine Learning* by Murphy and *The Elements of Statistical Learning* by Hastie, Tibshirani, and Friedman. 

## Homework & Grading (subject to change!)
Your grade will be determined by **8** problems sets and a **final project**. 
- Homework: 50 points
- Student reflections: 10 points
- Project proposal (due in the middle of the semester): 10 points
- Project report: 20 points
- Project presentation: 10 points

Students can earn up to 8 points in each homework assignment, with a cap of 50 points over all assignments. A list of suggested projects as well as guidelines for the proposal, final report, and presentation will be released early in the semester. Students are also encouraged to choose their own project with approval from the instructors.

This is an experimental course, meaning that feedback from the students will be valuable for future iterations of this course. Therefore, the instructors ask that students complete weekly reflections on what they learned each week and how effectively lectures and homework contribute to their learning. This will be worth 10 points through the semester. 



## Tentative list of lectures (subject to change!)

### Part 0: Introduction and linear algebra review
- Tour of machine learning topics; supervised & unsupervised learning, regression, classification, dimension reduction
- Vector and matrix norms, eigenvalue decompositions
- Singular value decomposition, Moore-Penrose pseudoinverse, Eckhart-Young theorem, low-rank approximations

### Part 1: Linear methods

- Linear least-squares regression; normal equations, applications of SVD, conditioning
- Maximum likelihood estimation and information theory; entropy, Kullback-Leibler divergence. Least-squares regression from an MLE perspective. 
- Regularization; ridge and LASSO regression, compressed sensing, sparsity
- Bayesian inference; *maximum a posteriori* estimators; regularization from a Bayesian perspective; Gaussian and Laplace priors. 
- Model selection; overfitting, generalization
- Principal components analysis; linear dimension reduction, applications to least-squares regression
- Logistic regression; maximum likelihood estimation for linear classifiers
- Linear discriminant analysis; Bayesian approaches to classification
     



### Part 2: Kernel methods

- Introduction to kernels; nonparametric regression, the kernel trick, introduction to reproducing kernel Hilbert spaces (RKHS), Mercer's theorem
- Regularization from a RKHS perspective
- Nonlinear dimension reduction; kernel PCA
- Gaussian processes; Karhunen-Loève expansion, exponential and Ornstein-Uhlenbeck kernels
- Gaussian process regression, kernel methods for large datasets, random features
- Support vector machines; perceptrons, separating hyperplanes, KKT conditions, kernels for classification
- Regularization of SVMs from a RKHS perspective

### Part 3: Deep learning methods

 - Introduction to neural networks; multilayer perceptrons, neural network architecture, activation functions
- Applying and training neural networks I; regression, classification, stochastic gradient descent, backpropagation, regularization, overfitting, model selection      
- Theory of deep learning; universal approximation theorems, connections to kernel methods, implicit regularization, double descent phenomenon

<!-- \item \textbf{Lecture 22:} Theory of deep learning II; connections to kernel methods, neural tangent kernel

\item \textbf{Lecture 23:} Theory of deep learning III; implicit regularization, double descent phenomenon -->

### Part 4: Student presentations









<!-- {% for post in site.teaching reversed %}
  {% include archive-single.html %} -->
<!-- {% endfor %}
 -->