---
title: "How to compare adversarial robustness of classifiers from a global perspective"
date: 2020-10-01
publishDate: 2020-08-11T17:20:45.020611Z
authors: ["Niklas Risse", "Christina Göpfert", "Jan Philip Göpfert"]
publication_types: ["3"]
abstract: "We use recently proposed robustness curves to show that point-wise measures for adversarial robustness do not capture important global properties that are essential to reliably compare the robustness of different classifiers."
featured: true
publication: ""
url_pdf: "https://arxiv.org/pdf/2004.10882"
---

Adversarial robustness of machine learning models has attracted considerable attention over recent years. Adversarial attacks undermine the reliability of and trust in machine learning models, but the construction of more robust models hinges on a rigorous understanding of adversarial robustness as a property of a given model. Point-wise measures for specific threat models are currently the most popular tool for comparing the robustness of classifiers and are used in most recent publications on adversarial robustness. In this work, we use recently proposed robustness curves to show that point-wise measures fail to capture important global properties that are essential to reliably compare the robustness of different classifiers. We introduce new ways in which robustness curves can be used to systematically uncover these properties and provide concrete recommendations for researchers and practitioners when assessing and comparing the robustness of trained models. Furthermore, we characterize scale as a way to distinguish small and large perturbations, and relate it to inherent properties of data sets, demonstrating that robustness thresholds must be chosen accordingly. We release code to reproduce all experiments presented in this paper, which includes a Python module to calculate robustness curves for arbitrary data sets and classifiers, supporting a number of frameworks, including TensorFlow, PyTorch and JAX.
