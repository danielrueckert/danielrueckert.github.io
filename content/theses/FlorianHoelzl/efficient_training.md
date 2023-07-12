---
title: "MSc Thesis/Guided Research/IDP: Efficient Training under Differential Privacy"
date: 2022-12-21
authors: ["FlorianHoelzl"]
---

Differential privacy (DP) is the gold standard of privacy-preserving deep learning and has seen increasing interest in the last few years, especially in the medical domain, where the protection of sensitive data is of highest interest [1]. Privacy in deep learning, however, still comes at a high privacy-utility trade-off that restricts the practical usability of models trained under DP. We, as researchers, try to solve this issue by looking into learning theory and by developing novel approaches that allow DP networks to challenge non-private approaches in clinical application.

Two properties that affect all differentially private networks are model size and the chosen privacy parameters during training. In this work, we plan to analyze these two areas and introduce changes to the training regime, that improve not only the performance of the models but also reduce their computational overhead. The goal is to 1) build on top of research done on learning sparse neural networks and correspondingly adapt the model parameters during training [2]. And 2), we look at the amount of total noise added during training with DP and evaluate, how to adapt the corresponding privacy parameters without any knowledge about the model or dataset [3]. If successful, this research can be applied to any differential private model in a plug-and-play fashion during training to further reduce the privacy-utility trade-off.
<br/>

## Your qualifications:

We are looking for a highly motivated Master’s student in Computer Science, Physics, Engineering or Mathematics. You will establish a comprehensive pipeline in PyTorch or JAX to evaluate the model sparsity and changing privacy-parameters on different benchmark datasets for models trained under DP. You will be working at the institute for AI in Medicine, at the Privacy-Preserving and Trustworthy Machine Learning Group. Importantly, we aim to publish the results of this work, with you, in a follow up study at a high-impact deep learning conference or in an academic journal.

1. Strong motivation and interest in deep learning and learning theory.
2. Advanced programming skills in Python and a common DL framework (PyTorch, Tensorflow, JAX).
3. Independent working style with strong interest in teamwork and methodic research.


<br/>

## What we offer:

- An exciting state-of-the-art research project with many possibilities to bring in your own ideas.
- Close supervision and access to the necessary computer hardware.
- The chance to work in a team of highly qualified experts in image processing, computer vision and deep learning.

<br/>

## References

[1] Abadi et al. (2016). Deep Learning with Differential Privacy. ACM SIGSAC 2016. </br>
[2] Louizos et al. (2018). Learning sparse neural networks through L0 regularization. ICLR 2018. </br>
[3] Sander et al. (2022). TAN without a burn: Scaling Laws of DP-SGD. ArXiv, abs/2210.03403.