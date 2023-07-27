---
title: "MSc Thesis: Multi-Organ Self-Supervised Learning for Efficient Exploitation of Large-Scale (1 million+) Real World Clinical Radiograph Dataset"
date: 2023-07-27
authors: ["PaulHager"]
---

## Description
As the availability of large clinical datasets continues to grow, the cost and effort associated with manual labeling of medical images become a significant bottleneck in leveraging the full potential of these data. In this research thesis, we aim to investigate the importance of self-supervised learning techniques in harnessing large clinical datasets, where labels are expensive and scarce. Specifically, we explore two prominent self-supervised deep learning approaches: contrastive learning and masked autoencoders.

Contrastive learning [1] has gained considerable attention due to its ability to learn useful representations without requiring labeled data. However, in the context of large clinical datasets comprising radiography images of multiple anatomical regions, several challenges arise. The need for downsampling to achieve viable batch sizes, coupled with the focus on global features, might limit the effectiveness of contrastive learning, particularly for capturing fine-grained features and retaining the high-resolution information of the images.

To overcome these limitations, we propose the utilization of masked autoencoders [2], an alternative self-supervised learning technique, for generating strong embeddings from our extensive in-house clinical dataset consisting of over 1 million radiography images across multiple anatomical regions. Masked autoencoders excel at capturing intricate details and preserving fine-grained features due to their ability to reconstruct input data by reconstructing masked portions. This characteristic makes them well-suited for large image sizes and enables them to emphasize local, region-specific information.

We will evaluate the strength of our embeddings through multiple downstream tasks such as foreign object identification, bone fracture classification, and fracture detection (bounding boxes). We will use a combination of NLP and expert annotations to develop a large enough training dataset for efficient finetuning using minimal labeled data.

## To accomplish this work successfully, we expect you to have:
- Strong coding skills and familiarity with Pytorch
- Basic knowledge of self-supervised methods such as contrastive learning or MAEs
- A strong spirit of independent work and desire to solve interesting, realworld research questions

## What we offer
- Access to a massive inhouse dataset of over 1 million medical images
- An exciting research project with many possibilities to bring in your own ideas.
- Close supervision and access to state-of-the-art computer hardware.
- The chance to work in a team of experts in image processing, deep learning, biomedical engineering and medicine.
- Support in bringing your finished project to publication

## References
[1] [A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/pdf/2002.05709.pdf)

[2] [Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/abs/2111.06377)

## How to apply:
Send an email to paul.hager@tum.de with your CV and transcript. We promise to get back to you within a couple of days.