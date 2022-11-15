
---
title: "MSc Thesis: Cardiac Fat Segmenation"
date: 2022-11-03
authors: ["TamaraMueller"]
draft: true
tags:
    - Deep Learning
    - Medical Segmentation
    - UK BioBank
---

Healthy cardiac adipose tissues can modulate cardiovascular functions and enery partitioning and function therefore in a protective manner. However, if this cardiac tissue changes it can contribute to the development of cardiovasuclar disorders. It is therefore of high relevance to segment different types of cardiac fat tissue and investigate its implication on the health of subjects.

This work will be investigated on a dataset of about 30,000 cardiac MR images from the UK Biobank [2] from which 200 will be selected and labelled by clinicians. The focus of this thesis is to implement a segmentation algorithm that detects and labels two different types of fat in the cardiac images. Given the comparably small size of the labelled dataset and the large amount of unlabelled data, we target the implementation of a semi-supervised approach. Works like [3] have e.g. explored contrastive learning for medical image segmentation, which could be extended for our task.

<b>About the dataset</b>: The [UK BioBank](https://www.ukbiobank.ac.uk/) is a large medical dataset, containing data of about 50,000 participants. It holds images (brain MRI, abdominal MRI) as well as several thousand clinical parameters of the participants (demographic data, lifestyle data, clinical diagnoses,…). The lack of available data is a big challenge in medical applications of artificial intelligence. Therefore, the UK Biobank holds great potential to explore ML techniques on a large standardised dataset.


## Your qualifications:

We are looking for a highly motivated Master's student in Computer Science or a closely related programme. You should bring:

- interest in medical image processing;

- prior knowledge in machine learning and a commonly used DL framework (PyTorch, Tensorflow)

- a background in computer vision (e.g. from one of the CV courses)

## What we offer:

- an exciting project on real world medical data

- a large dataset with annotations from medical experts

- an interdisciplinary team of high qualified experts in image processing, computer vision, deep learning, and medicine.


[1] Lu Z, Jiang Z, Tang J, Lin CP, Zhang H. Functions and origins of cardiac fat. FEBS J. 2022 Feb 3. doi: 10.1111/febs.16388. Epub ahead of print. PMID: 35114069.

[2] https://www.ukbiobank.ac.uk/

[3] Chaitanya, Krishna, et al. "Contrastive learning of global and local features for medical image segmentation with limited annotations." Advances in Neural Information Processing Systems 33 (2020): 12546-12558.