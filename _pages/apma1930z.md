---
layout: archive
title: "APMA 1930Z: Introduction to Mathematical Machine Learning"
permalink: /apma1930z/
author_profile: false
---

<!-- {% include base_path %}-->
 
 
 <!-- <span style="color:red"> ***As of 08 November 2023, enrollment for the class is full. However, if you are still interested in signing up for the course, please email us at bjzhang@umass.edu and ziyuchen@umass.edu.***  </span> -->

 [<img align="right" width="400" src="https://benjzhang.github.io/files/ma590sta_poster.png" />](https://benjzhang.github.io/files/ma590sta_poster.png)

A final syllabus and course schedule has been posted to [Canvas](https://canvas.brown.edu/courses/1096947)

## Fall 2024
MWF 2:00-2:50 PM in Rockefeller Library 205

## Instructors and contact
[Paul Dupuis](https://appliedmath.brown.edu/people/paul-dupuis), Paul_Dupuis@Brown.edu

Benjamin Zhang, Benjamin_Zhang@Brown.edu


## Course description

This course will provide an introduction to machine learning from a mathematical perspective. The primary objective of this course is to cultivate in students a sense of mathematical curiosity and equip them with the skills to ask mathematical questions when studying machine learning algorithms. Classical supervised learning methods will be presented and studied using the tools from information theory, statistical learning theory, optimization, and basic functional analysis. The course will cover three categories of machine learning approaches: linear methods, kernel-based methods, and deep learning methods, each applied to regression, classification, and dimension reduction. Coding exercises will be an essential part of the course to empirically study strengths and weaknesses of methods. 

## Prerequisites
This class is intended for an advanced undergraduate or a first year Master's student. We expect a strong command of probability, multivariable calculus, and linear algebra at the level of MATH 0520/0540, APMA 1650/1655, and APMA 1690/MATH 1610, or permission of instructor. *Recommended*: Familiarity of numerical methods. Basic programming experience is assumed. You may program in any language, but most instructional scripts will be provided in Python.  


## Textbook 
No required textbook. We will be reading selections from 
- [Probabilistic Machine Learning: An Introduction](https://probml.github.io/pml-book/book1.html) by Kevin P. Murphy
- [Gaussian processes for Machine Learning](https://gaussianprocess.org/gpml/) by Carl Edward Rasmussen and Christopher K. I. Williams
- [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/) by Trevor Hastie, Robert Tibshirani, and Jerome Friedman.

Supplementary readings will be provided for topics not covered in the textbooks. 



## Homework & Grading (subject to change!)
Your grade will be determined by **8** problems sets and a **final project**. 
- Homework: 30%
- Quiz: 30%
- Project proposal: 10%
- Project report: 30% 

Each homework assignment equally weighted. Each problem set will consist of derivations, proof--based questions, and numerical exploration and experimentation of machine learning algorithms. 

<!-- APMA 1930Z is an experimental course, meaning that feedback will be invaluable for future iterations of this course. Therefore, the instructors ask that students complete short reflections after each class on what they learned and how effectively lectures and homework contributed to their learning. Attendance of lectures will be crucial for receiving credit for minute papers.  -->


An individual final project is required to pass the class. A project proposal will be due in the middle of the semester. Poster sessions showcasing each students' work will take place on the last week of class. The final project report (7-10 pages) will be due at the end of the semester. A list of suggested projects as well as guidelines for the proposal, final report, and poster session will be released early in the semester.  Students are also encouraged to choose their own project with approval from the instructors. 



## Subject outline

### Part 0: Introduction to machine learning and linear algebra review
-  Introduction and motivation; Tour of machine learning topics and methods. Supervised versus unsupervised learning, regression, classification, dimension reduction. 
-  Review of linear algebra; vector and matrix norms, singular value decomposition, Moore-Penrose pseudoinverse, Eckhart-Young theorem, low rank approximations, condition numbers

### Part 1: Regression

- Linear least squares regression; normal equations, SVD, conditioning
- Maximum likelihood estimation and information theory; entropy, Kullback-Leibler divergence, minimum--variance unbiased estimators, Cram\'er-Rao bound, best linear unbiased estimators, Gauss--Markov theorem
- Bayesian inference; \emph{Maximum a posteriori} estimators, conjugate priors
- Regularization; underdetermined least squares, rank-deficient least squares, Tikhonov regularization, ridge and LASSO regression, compressed sensing, sparsity, Gauss and Laplace priors
- Bayesian linear regression
- Model selection and generalization; bias--variance tradeoff, cross validation
     



### Part 2: Deep learning and optimization

- Optimization methods; gradient descent, stochastic gradient descent, Newton's method, constrained optimization, KKT conditions
- Introduction to neural networks;  neural network architectures, activation functions, backpropagation
- Regularization; double descent phenomena, model complexity, model selection 
- Theory of deep learning; universal approximation theorems

### Part 3: Classification

 - Linear discriminant analysis, Logistic regression, perceptrons, separating hyperplanes
- Support vector machines; linear SVMs, kernel SVMs    
- Deep learning for classification; multilayer perceptrons


### Part 4: Dimension reduction

 - Linear dimension reduction; principal components analysis, Johnson-Lindenstrauss lemma
- Nonlinear dimension reduction; kernel PCA, autoencoders
- Variational autoencoders; generative modeling


### Part 5: Kernel methods

- Reproducing kernel Hilbert spaces; Hilbert spaces, Mercer's theorem, Mercer kernels
- Nonparametric regression; kernel ridge regression, representer theorem, Derivative regularization
-  Gaussian processes regression; Gaussian processes, model selection, marginal likelihood

### Part 6: Advanced topics

- Learning theory; model complexity, Vapnike-Chervonenkis-dimension, generalization, PAC learning
- Neural tangent kernel
<!-- \item \textbf{Lecture 22:} Theory of deep learning II; connections to kernel methods, neural tangent kernel

\item \textbf{Lecture 23:} Theory of deep learning III; implicit regularization, double descent phenomenon -->

<!-- ### Part 4: Student presentations -->









<!-- {% for post in site.teaching reversed %}
  {% include archive-single.html %} -->
<!-- {% endfor %}
 -->