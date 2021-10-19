---
title: "MSc Thesis: A Patch-Wise Discriminator for Semi-Supervised Anomaly Segmentation"
date: 2021-10-04
authors: ["FelixMeissen"]
---

## Introduction

The medical domain is characterized by large amounts of available data, but obtaining labels usually requires expert radiologists. The recent surge of unsupervised learning spawned valuable techniques to handle data without the necessity of these labels.
Anomaly Detection tries to find data points that deviate from a statistical norm. This is especially useful in the medical domain as anomalies here are often indicators for diseases.

## Description

Currently, most anomaly detection and segmentation methods train a generative model (Autoencoder or GAN) on healthy images only and use the reconstruction error of unseen samples to detect anomalies [1].
However, the reconstruction error is suboptimal and can only detect certain anomaly types.

That's why you will develop a new scoring method.
Generative models are a natural fit for anomaly detection, since they can assess the
likelihood of a region appearing in an image. The discriminator of a GAN trained on normal
data only is a natural anomaly detector as its only purpose is to decide whether a presented
sample comes from the learned distribution or not.
You will build a GAN with a patch-wise discriminator to localize anomalies in the images.

## What we offer

- Cutting edge research in an active field of medical imaging
- A strong research group with lots of practical experience
- The opportunity to publish your work at a renown conference

## What we expect

- Advanced skills in Python and deep learning frameworks such as PyTorch, Tensorflow or JAX
- Strong background in deep learning, especially in the image domain
- A good feeling for behavior of neural networks

If you are interested in this work and ready for a new challenge, please feel free to contact me

## References

[1] Christoph Baur, Stefan Denner, Benedikt Wiestler, Nassir Navab, Shadi Albarqouni. Autoencoders for unsupervised anomaly segmentation in brain MR images: A comparative study. In Medical Image Analysis, 2021.
