---
title: "B.Sc. Thesis/Guided Research/IDP: Influence of slice thickness of pulmonary CTs on Semantic Segmentation Algorithms "
date: 2022-11-16
draft: false
authors: ["LeonhardFeiner"]
---

## Description

Covid-19 can cause various types of pathologies within the lung. Deep learning is widely used to segment affected areas of the lung using computed tomography images as input. However, these images can be acquired using a large variety of imaging parameters. These parameters include the resolution in Z axis usually given as slice thickness of the longitudinal plane in millimeter. The goal of this project is to assess the implications of the slice thickness on common imaging metrics for semantic segmentation.

Hence, we created an in-house dataset containing 50 patients and 2 scans per patent for slice thickness of 1mm and 5mm. Furthermore, we have semantic labels for all 100 volumes. Those could be used to compare single thickness of 1mm, single thickness of 5mm and mixed thickness. To achieve a fair comparison, we also want to mitigate the effect of an unequal number of total slices for the subsets containing different slice thicknesses.

## Your task include

- Defining an appropriate dataset split and selection to get a fair comparison
- Implementation and training of a semantic segmentation deep learning model
- Hyperparameter tuning
- Evaluation using appropriate metrics

## Your requirements

- Interest in medical image processing
- Prior knowledge in machine learning and a commonly used DL framework (PyTorch, TensorFlow, …)
