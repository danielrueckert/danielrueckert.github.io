
---
title: "MSc Thesis: Vertebrae detection and labelling in MR images"
date: 2022-08-09
authors: ["TamaraMueller"]
draft: false
tags:
    - Deep Learning
    - Medical Imaging

---
The spine of a patient can indicate their health state or frailty. E.g. the localised vertebrae can be used for detecting fractures, surgical planning or treatment analyses [1]. Image landmark detection has the goal of automatically identify the locations of points of interest in an image [2]. Recent studies have investigated the identification and localisation of vertebrae for automated spline analysis on CT scans [1,3]. However, spline detection and analysis holds several challenges, including its difficulty in MR images compared to CT scans.

This work will be investigated on a dataset of about 30,000 MR images from the

UK Biobank [4] from which 200 were selected and labelled by clinicians. The focus of this work is to implement a landmark detection algorithm that detects and labels all vertebrae in the MR images. Given the comparably small size of the labelled dataset and the large amount of unlabelled data, we target the implementation of a semi-supervised approach. Works like [5] have e.g. explored contrastive learning for medical image segmentation, which could be extended for landmark detection in this project.

## Your qualifications:

We are looking for a highly motivated Master's student in Computer Science or a closely related programme. You should bring:

- Interest in medical image processing;

- Prior knowledge in machine learning and a commonly used DL framework (PyTorch, Tensorflow)

- a background in computer vision (e.g. from one of the CV courses)

## What we offer:

- An exciting project on real world medical data

- a large dataset with annotations from medical experts

- an interdisciplinary team of high qualified experts in image processing, computer vision, deep learning, and medicine.

[1] Sekuboyina, Anjany, et al. "Btrfly net: Vertebrae labelling with energy-based adversarial learning of local spine prior." International Conference on Medical Image Computing and Computer-Assisted Intervention. Springer, Cham, 2018.

[2] Li, Weijian, et al. "Structured landmark detection via topology-adapting deep graph learning." European Conference on Computer Vision. Springer, Cham, 2020.

[3] Sekuboyina, Anjany, et al. "VerSe: A Vertebrae labelling and segmentation benchmark for multi-detector CT images." Medical image analysis 73 (2021): 102166.

[4] https://www.ukbiobank.ac.uk/

[5] Chaitanya, Krishna, et al. "Contrastive learning of global and local features for medical image segmentation with limited annotations." Advances in Neural Information Processing Systems 33 (2020): 12546-12558.