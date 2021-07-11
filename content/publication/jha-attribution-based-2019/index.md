---
title: "Attribution-Based Confidence Metric For Deep Neural Networks"
date: 2019-12-01
publishDate: 2020-03-26T05:46:34.991671Z
authors: ["Sumit Jha", "Sunny Raj", "Steven Fernandes", "Sumit Jha", "Somesh Jha", "Brian Jalaian", "Gunjan Verma", "Ananthram Swami"]
publication_types: ["2"]
abstract: "We propose a novel confidence metric, namely, attribution-based confidence (ABC) for deep neural networks (DNNs). ABC metric characterizes whether the output of a DNN on an input can be trusted. DNNs are known to be brittle on inputs outside the training distribution and are, hence, susceptible to adversarial attacks. This fragility is compounded by a lack of effectively computable measures of model confidence that correlate well with the accuracy of DNNs. These factors have impeded the adoption of DNNs in high-assurance systems. The proposed ABC metric addresses these challenges. It does not require access to the training data, the use of ensembles, or the need to train a calibration model on a held-out validation set. Hence, the new metric is usable even when only a trained model is available for inference. We mathematically motivate the proposed metric and evaluate its effectiveness with two sets of experiments. First, we study the change in accuracy and the associated confidence over out-of-distribution inputs. Second, we consider several digital and physically realizable attacks such as FGSM, CW, DeepFool, PGD, and adversarial patch generation methods. The ABC metric is low on out-of-distribution data and adversarial examples, where the accuracy of the model is also low. These experiments demonstrate the effectiveness of the ABC metric towards creating more trustworthy and resilient DNNs."
featured: True
publication: "*Advances in Neural Information Processing Systems 32, NeurIPS*"
url_pdf: "https://papers.nips.cc/paper/9355-attribution-based-confidence-metric-for-deep-neural-networks.pdf"
---

