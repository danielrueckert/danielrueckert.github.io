---
title: "MSc Thesis: Multimodal Representation Learning Dynamics and its Implications on Tabular Feature Selection"
date: 2023-02-14
authors: ["PaulHager"]
---

## Description
Medical datasets and especially biobanks, often contain extensive tabular data with rich clinical information in addition to images. In practice, clinicians typically have less data, both in terms of diversity and scale, but still, wish to deploy deep learning solutions. Combined with increasing medical dataset sizes and expensive annotation costs, the necessity for unsupervised methods that can be pretrain multimodally and predict unimodally has risen.

We have developed a self-supervised representation learning framework that incorporates both tabular and imaging data during pretraining but requires only images during testing. So far, during pretraining we have used all possibly relevant features but have indications in the literature and through our experiments that there exists an optimal subset. Furthermore, the shared latent space should hold keys to the increased performance of the multimodal pretraining process.

The goal of this thesis will be to develop a framework for optimal subset selection of tabular features for pretraining. Your target is to improve the downstream performance of the imaging encoder across all tasks. At the end, we wish to understand how information is encoded between modalities when training in a multimodal fashion and how to maximize our learning signal. 

Theoretically, you will explore concepts such as mutual information, collinearity and latent space explainability. Experimentally, you will start with our network architecture and the UK Biobank dataset of over 40k cardiac MR scans to test your hypotheses. As an extension, you will use explainability methods such as Guided GradCAM and integrated gradients to investigate how the learned features change with different subsets of tabular features and why perfomance increases.

## To accomplish this work successfully, we expect you to have:

- Strong mathematical background
- Decent coding skills and familiarity with Pytorch
- Basic knowledge of representation learning
- Basic knowledge of deep-learning explainability methods
- A strong spirit of independent work and desire to solve interesting research questions

## What we offer

- An exciting research project with many possibilities to bring in your own ideas.
- Close supervision and access to state-of-the-art computer hardware.
- The chance to work in a team of experts in image processing, deep learning, biomedical engineering and medicine.
- Support in bringing your finished project to publication

## References
[1] [A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/pdf/2002.05709.pdf)

[2] [SCARF: Self-Supervised Contrastive Learning using Random Feature Corruption](https://arxiv.org/pdf/2106.15147.pdf)

[3] [Why do tree-based models still outperform deep learning on typical tabular data](https://openreview.net/pdf?id=Fp7__phQszn)

[4] [What Makes for Good Views for Contrastive Learning?](https://proceedings.neurips.cc/paper/2020/file/4c2e5eaae9152079b9e95845750bb9ab-Paper.pdf)

## How to apply:

Send an email to paul.hager@tum.de with your CV and transcript. We promise to get back to you within a couple of days. 

