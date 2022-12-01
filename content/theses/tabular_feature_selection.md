---
title: "MSc Thesis: Tabular Feature Selection and Shared Latent Space Explainability in Self-Supervised Multimodal Deep Learning"
date: 2022-12-01
authors: ["PaulHager"]
---

## Description
Medical datasets and especially biobanks, often contain extensive tabular data with rich clinical information in addition to images. In practice, clinicians typically have less data, both in terms of diversity and scale, but still, wish to deploy deep learning solutions. Combined with increasing medical dataset sizes and expensive annotation costs, the necessity for unsupervised methods that can be pretrain multimodally and predict unimodally has risen.

We have developed a self-supervised framework that incorporates both tabular and imaging data during pretraining but requires only images during testing. So far, during pretraining we have used all possibly relevant features but have indications that there exists an optimal subset. Furthermore, the shared latent space should hold keys to the increased performance of the multimodal pretraining process.

The goal of this thesis will be to develop a framework for optimal subset selection of tabular features for pretraining. Your target is to improve the downstream performance of the imaging encoder across all tasks. Theoretically, you will explore concepts such as mutual information and collinearity. Experimentally, you will use our network architecture and the UK Biobank dataset of cardiac MR data to test your hypotheses. As an extension, you will use explainability methods such as Guided GradCAM and integrated gradients to investigate how the learned features change with different subsets of tabular features and why perfomance increases.

## To accomplish this work successfully, we expect you to have:

- Strong coding skills and familiarity with Pytorch and Numpy
- Basic knowledge of contrastive self-supervised learning, especially SimCLR
- Basic knowledge of deep-learning explainability methods
- A strong spirit of independent work and desire to solve interesting research questions

## What we offer

- An exciting research project with many possibilities to bring in your own ideas.
- Close supervision and access to state-of-the-art computer hardware.
- The chance to work in a team of experts in image processing, deep learning, biomedical engineering and medicine.
- Support in bringing your finished project to publication


## How to apply:

Send an email to paul.hager@tum.de with your CV and transcript. We promise to get back to you within a couple of days. 

