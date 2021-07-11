---
title: "Detecting adversarial examples using data manifolds"
date: 2018-10-29
publishDate: 2020-03-26T05:46:35.005743Z
authors: ["Somesh Susmit Jha", "Uyeong Jang", "Somesh Susmit Jha", "Brian Jalaian"]
publication_types: ["1"]
abstract: "Models produced by machine learning, particularly deep neural networks, are state-of-the-art for many machine learning tasks and demonstrate very high prediction accuracy. Unfortunately, these models are also very brittle and vulnerable to specially crafted adversarial examples. Recent results have shown that accuracy of these models can be reduced from close to hundred percent to below 5% using adversarial examples. This brittleness of deep neural networks makes it challenging to deploy these learning models in security-critical areas where adversarial activity is expected, and cannot be ignored. A number of methods have been recently proposed to craft more effective and generalizable attacks on neural networks along with competing efforts to improve robustness of these learning models. But the current approaches to make machine learning techniques more resilient fall short of their goal. Further, the succession of new adversarial attacks against proposed methods to increase neural network robustness raises doubts about a foolproof approach to robustify machine learning models against all possible adversarial attacks. In this paper, we consider the problem of detecting adversarial examples. This would help identify when the learning models cannot be trusted without attempting to repair the models or make them robust to adversarial attacks. This goal of finding limitations of the learning model presents a more tractable approach to protecting against adversarial attacks. Our approach is based on identifying a low dimensional manifold in which the training samples lie, and then using the distance of a new observation from this manifold to identify whether this data point is adversarial or not. Our empirical study demonstrates that adversarial examples not only lie farther away from the data manifold, but this distance from manifold of the adversarial examples increases with the attack confidence. Thus, adversarial examples that are likely to result into incorrect prediction by the machine learning model is also easier to detect by our approach. This is a first step towards formulating a novel approach based on computational geometry that can identify the limiting boundaries of a machine learning model, and detect adversarial attacks."
featured: True
publication: "*018 IEEE Military Communications Conference (MILCOM)*"
tags: ["Adversarial examples", "Manifolds", "Robustness", "Trusted machine learning"]
url_pdf: "http://susmitjha.github.io/papers/milcom18.pdf"
#doi: "10.1109/MILCOM.2018.8599691"
---

