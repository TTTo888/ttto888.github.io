---
title: "Stochastic Variational Inference for Bayesian Sparse Gaussian Process Regression"
collection: publications
permalink: /publication/ijcnn19
excerpt: 'Haibin Yu, Trong Nghia Hoang, Kian Hsiang Low and Patrick Jaillet'
date: 2019-07-14
venue: 'International Joint Conference on Neural Networks (IJCNN)'
---
Abstract: This paper presents a novel variational inference framework for deriving a family of Bayesian sparse Gaussian process regression (SGPR) models whose approximations are variationally optimal with respect to the full-rank GPR model enriched with various corresponding correlation structures of the observation noises. Our variational Bayesian SGPR (VBSGPR) models jointly treat both the distributions of the inducing variables and hyperparameters as variational parameters, which enables the decomposability of the variational lower bound that in turn can be exploited for stochastic optimization. Such a stochastic optimization involves iteratively following the stochastic gradient of the variational lower bound to improve its estimates of the optimal variational distributions of the inducing variables and hyperparameters (and hence the predictive distribution) of our VBSGPR models and is guaranteed to achieve asymptotic convergence to them. We show that the stochastic gradient is an unbiased estimator of the exact gradient and can be computed in constant time per iteration, hence achieving scalability to big data. We empirically evaluate the performance of our proposed framework on two real-world, massive datasets.

[Paper](http://htnghia87.github.io/files/ijcnn19.pdf)
[Supplementary](http://htnghia87.github.io/files/ijcnn19-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/ijcnn19.bib)