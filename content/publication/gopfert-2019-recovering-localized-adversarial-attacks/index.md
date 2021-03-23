---
title: "Recovering Localized Adversarial Attacks"
date: 2019-01-01
publishDate: 2020-08-11T17:20:45.020178Z
authors: ["Jan Philip Göpfert", "Heiko Wersing", "Barbara Hammer"]
publication_types: ["1"]
abstract: "We quantitatively and qualitatively investigate the capability of three popular explainers of classifications – classic salience, guided backpropagation, and LIME – with respect to their ability to identify regions of attack as the explanatory regions for the (incorrect) prediction in representative examples from image classification."
featured: true
publication: "*International Conference on Artificial Neural Networks*"
url_pdf: "https://arxiv.org/pdf/1910.09239"
---

Deep convolutional neural networks have achieved great successes over recent years, particularly in the domain of computer vision. They are fast, convenient, and – thanks to mature frameworks – relatively easy to implement and deploy. However, their reasoning is hidden inside a black box, in spite of a number of proposed approaches that try to provide human-understandable explanations for the predictions of neural networks. It is still a matter of debate which of these explainers are best suited for which situations, and how to quantitatively evaluate and compare them [1]. In this contribution, we focus on the capabilities of explainers for convolutional deep neural networks in an extreme situation: a setting in which humans and networks fundamentally disagree. Deep neural networks are susceptible to adversarial attacks that deliberately modify input samples to mislead a neural network’s classification, without affecting how a human observer interprets the input. Our goal with this contribution is to evaluate explainers by investigating whether they can identify adversarially attacked regions of an image. In particular, we quantitatively and qualitatively investigate the capability of three popular explainers of classifications – classic salience, guided backpropagation, and LIME – with respect to their ability to identify regions of attack as the explanatory regions for the (incorrect) prediction in representative examples from image classification. We find that LIME outperforms the other explainers.
