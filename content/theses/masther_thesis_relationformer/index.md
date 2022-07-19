---
title: "MSc Thesis: Transformer based Graph Extraction"
date: 2022-07-13
authors: ["JohannesPaetzold"]
---

In this Master thesis we aim to address the graph extraction problem using a new powerful class of neural networks - Transformers [2][3]. A comprehensive representation of an image requires understanding objects and their mutual relationship, especially in image-to-graph generation, e.g., road network extraction, blood-vessel network extraction, or scene graph generation. 
Traditionally, image-to-graph generation is addressed with a two-stage approach consisting of object detection followed by a separate relation prediction, which prevents simultaneous object-relation interaction. In our recent ECCV paper, we proposed a unified one-stage transformer-based framework, namely *Relationformer* that jointly predicts objects and their relations [1]. 

In a next step we aim to apply the *Relationformer* to large scale biological applications for example the whole brain vasculature [4] or neurons. We plan to explore concepts of domain-adaptation and transfer learning. Please see exemplary images of the whole brain vasculature and the *Relationformer* model below.

<br/>

![image transformer](./relationformer.png)

<br/>

## Your qualifications:

We are looking for a highly motivated Master’s student in Computer Science, Physics, Engineering or Mathematics. Your goal is to extend the existing Pytorch codebase and apply it to novel datasets. You will be working together with Suprosanna and Johannes, two senior computater scientist at TU Munich and Imperial College London under the supervision of Prof. Daniel Rückert. Importantly, we aim to publish the results of this work, with you, in a follow up study at a high-impact machine learning conference or in an academic journal. 

1. Strong motivation and interest in machine learning. 
2. Advanced programming skills in C++, Python or C.  
3. Strong interest in teamwork and interdisciplinary research. 

<br/>

## What we offer:

- An exciting research project with many possibilities to bring in your own ideas.
- Close supervision and access to state-of-the-art computer hardware.
- The chance to work in a team of highly qualified experts in machine learning, computer vision and deep learning.

<br/>

## How to apply:

Just send an email to suprosanna.shit@tum.de and j.paetzold@ic.ac.uk, with a short CV and your grade report. We promise to get back to you within days. 

<br/>

![image vessel](./vessels.png)

<br/>

## References:

[1] Shit, Suprosanna, et al. "Relationformer: A Unified Framework for Image-to-Graph Generation." arXiv preprint arXiv:2203.10202 (2022).

[2] Dosovitskiy, Alexey, et al. "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale." International Conference on Learning Representations. 2020.

[3] Carion, Nicolas, et al. "End-to-end object detection with transformers." European conference on computer vision. Springer, Cham, 2020.

[4] Paetzold, Johannes C., et al. "Whole Brain Vessel Graphs: A Dataset and Benchmark for Graph Learning and Neuroscience." Thirty-fifth Conference on Neural Information Processing Systems Datasets and Benchmarks Track (Round 2). 2021.
<br/>