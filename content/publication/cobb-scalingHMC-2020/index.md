---
title: "Scaling Hamiltonian Monte Carlo Inference for Bayesian Neural Networks with Symmetric Splitting"
date: 2021-07-11T22:17:50-04:00
publishDate: 2021-07-11 
authors: ["Adam D. Cobb", "Brian Jalaian"]
publication_types: ["1"]
abstract: "Hamiltonian Monte Carlo (HMC) is a Markov chain Monte Carlo (MCMC) approach that exhibits favourable exploration properties in high-dimensional models such as neural networks. Unfortunately, HMC has limited use in large-data regimes and little work has explored suitable approaches that aim to preserve the entire Hamiltonian. In our work, we introduce a new symmetric integration scheme for split HMC that does not rely on stochastic gradients. We show that our new formulation is more efficient than previous approaches and is easy to implement with a single GPU. As a result, we are able to perform full HMC over common deep learning architectures using entire data sets. In addition, when we compare with stochastic gradient MCMC, we show that our method achieves better performance in both accuracy and uncertainty quantification. Our approach demonstrates HMC as a feasible option when considering inference schemes for large-scale machine learning problems."
featured: true
publication: "*Accepted for the 37th Conference on Uncertainty in Artificial Intelligence (UAI 2021)*"
tags: ["Uncertainty Quantification", "Deep Learning", "MCMC", "HMC", "Hamiltonian Monte-Carlo", "Bayesian Machine Learning"]
url_pdf: "https://auai.org/uai2021/pdf/uai2021.274.preliminary.pdf"
---

