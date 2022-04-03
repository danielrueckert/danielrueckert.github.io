---
title: "MSc Thesis: Out-of-distribution detection using contrastive training for medical imaging"
date: 2020-11-14
authors: ["VeronikaZimmer"]
---

Deep learning has revolutionized the field of medical imaging. However, the performance of a model drops when the distribution of the test data is different from the distribution of the training data. This is especially critical in a medical setting, where the amount of labelled training data is often limited, and in particular for the application in clinical routine, where the distribution of the test data cannot be controlled. The automatic detection of such Out-of-Distribution (OoD) samples at inference is important for the design of reliable models, but also to identify poor quality images and pathologies not seen during training.

Recently, contrastive learning has shown to provide state-of-the-art results for OoD in image classification benchmarks [1]. Contrastive learning is an approach to formulate the task of finding similar and dissimilar samples during training. One advantage of the proposed method is that no OoD data is required during training.
The aim of this project is to explore OoD detection in deep learning in general, and in particular the use of contrastive training. The student will develop and implement (novel) methods for image classification, segmentation, and/or registration in a medical application.

## Requirements

1. Prior experience and good understanding in machine learning and statistics. 
2. Very good programming skills in python (and pytorch).

## References

1. J. Winkens et al.: Contrastive Training for Improved Out-of-Distribution Detection. arXiv preprint arXiv:2007.05566 (2020)