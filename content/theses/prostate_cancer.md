---
title: "MSc Thesis: Non-invasive and accurate prediction of prostate cancer aggressiveness"
date: 2022-07-28
authors: ["FlorianHoelzl"]
---

With estimates of 1 600 000 cases and more than 350 000 deaths annually worldwide, prostate cancer is among the most common cancers in men [1]. Diagnosis of prostate cancer is typically done by using ultrasound-guided needle biopsies. An approach that not only involves risks, due to the invasive nature of the method, but also generally underestimates the aggressiveness of the tumor [2]. Standard positron emission tomography (PET) imaging with prostate cancer specific tracers and specifically PSMA-PET have shown to be advantageous for delineating suspicious lesions during biopsy [3, 4]. 

We want to use the information provided by these PET and multi-parametric MRI images to directly predict Gleason scores that accurately report the aggressiveness of the prostate cancers without the risks associated with an invasive biopsy. Recent research at our institution has produced promising results predicting Gleason scores from handcrafted radiomic features [5]. This work aims at building on top of this research and to develop an end-to-end deep learning pipeline for predicting tumor aggressiveness directly from different imaging modalities. We have exclusive access to a dataset which includes PSMA-11 PET/MRI scans, segmentation maps and the pathological information of the tumors. Additional public data is available through the [PI-CAI Challenge](https://pi-cai.grand-challenge.org). The focus of this work is to build a complete pipeline for analysing multi-modal medical imaging datasets. This includes research on understanding the diverse data available, exploring different approaches for dealing with the limited dataset size (data augmentation, pre-training etc.) and finding a suitable model and evaluation metric for this use case.
<br/>

## Your qualifications:

We are looking for a highly motivated Master’s student in Computer Science, Physics, Engineering or Mathematics. You will establish a comprehensive medical imaging pipeline in PyTorch to extract information from these images. You will be working together with me and under the supervision of Prof. Daniel Rückert. Importantly, we aim to publish the results of this work, with you, in a follow up study at a high-impact medical imaging conference or in an academic journal.

1. Strong motivation and interest in machine learning and medical imaging.
2. Advanced programming skills in Python and a common DL framework (PyTorch, Tensorflow).
3. Strong interest in teamwork and interdisciplinary research.


<br/>

## What we offer:

- An exciting research project with many possibilities to bring in your own ideas.
- Close supervision and access to state-of-the-art computer hardware.
- The chance to work in a team of highly qualified experts in image processing, computer vision and deep learning.

<br/>

## References

[1] 1. Global Burden of Disease Cancer Collaboration (2017). Global, Regional, and National Cancer Incidence, Mortality, Years of Life Lost, Years Lived With Disability, and Disability-Adjusted Life-years for 32 Cancer Groups, 1990 to 2015: A Systematic Analysis for the Global Burden of Disease Study. JAMA Oncol. 2017;3(4):524. </br>
[2] Cohen et al. (2008). Comparing the Gleason prostate biopsy and Gleason prostatectomy grading system: the Lahey Clinic Medical Center experience and an international meta-analysis. EurUrol. 2008;54(2):371-81. </br>
[3] Fendler et al. (2017). Joint EANM and SNMMI procedure guideline for prostate cancer imaging: version 1.0. Eur J Nucl Med Mol Imaging. 2017;44(6):1014–24. </br>
[4] Maurer et al. (2016). Current use of PSMA-PET in prostate cancer management. Nat Rev Urol. 2016;13(4):226–35. </br>
[5] Solari et al. (2021). The added value of PSMA PET/MR radiomics for prostate cancer staging. Eur J Nucl Med Mol Imaging. 2022;49:527–538.