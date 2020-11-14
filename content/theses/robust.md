---
title: "MSc Thesis: Distributionally robust neural networks in medical imaging"
date: 2020-11-14
authors: ["VeronikaZimmer"]
---

Deep learning has revolutionized the field of medical imaging. However, the performance of a model drops when the distribution of the test data is different from the distribution of the training data. This is especially critical in a medical setting, where the amount of labelled training data is often limited, and in particular for the application in clinical routine, where the distribution of the test data cannot be controlled. Typical problems are here domain shift, bias in the training data and out-of-distribution samples (e.g., pathologies, image artefacts).
In this project, we will explore distributionally robust optimization (DRO) [1,2] for deep learning in medical imaging. Instead of minimizing the average loss of a training set, DRO minimizes the worst-case risk and with this optimizes the performances on ”hard” examples. The student will adapt and develop novel methods using DRO for medical imaging applications (classification, segmentation and/or registration.

## Requirements
1. Prior experience and good understanding in machine learning and statistics. 
2. Very good programming skills in python (and pytorch).

## References
1. J. Duchi and H. Namkoong: Learning models with uniform performance via distributionally robust optimization. arXiv preprint arXiv:1810.08750 (2018)
2. S. Sagawa et al.: Distributionally Robust Neural Networks, In Proc. ICLR (2020)