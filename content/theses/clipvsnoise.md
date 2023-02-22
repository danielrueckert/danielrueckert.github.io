---
title: "Application Project/Guided Research/etc: Separating the influence of noising and clipping in differentially private training."
date: 2023-02-22
authors: ["AlexZiller"]
draft: false
tags:
    - Deep Learning
    - PPML

---
Privacy-Preserving Machine Learning enables the training of neural networks, while bounding the information about data subjects [1,2]. Hence, especially in sensitive contexts where plausible deniability is crucial it is an important mean to give mathematical guarantees about worst case guarantees. However, due to these constraints in most cases it introduces a drop in utility compared to non-private training. This drop can be explained from two factors compared to normal training: 1) gradients are clipped to a maximum norm and 2) noise is added. In this project we want to evaluate the effect of both seperately on different architectures and settings. 


<br/>

## Your qualifications:

- Enthusiasm for deep learning.
- Advanced knowledge of machine learning and computer vision. 
- Excellent programming skills in Python and at least one deep learning frame work (optimally PyTorch or Jax)
- Prior knowledge on PPML or medical imaging is helpful but no requirement

<br/>

## What we offer:

- Experience with several top-tier publications in privacy-preserving machine learning.
- Working in an interdisciplinary team of experts in PPML, image processing, deep learning, biomedical engineering and medicine.
- Enough freedom to pursue your own project while providing the guidance you need.
- Thesis is strongly aimed to be published in a peer-reviewed venue.

<br/>

## References
- [[1] Secure, privacy-preserving and federated machine learning in medical imaging](https://www.nature.com/articles/s42256-020-0186-1)
- [[2] End-to-end privacy preserving deep learning on multi-institutional medical imaging](https://www.nature.com/articles/s42256-021-00337-8)