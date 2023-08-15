---
title: "BSc / Guided Research: Prediction of long-term cognitive outcome in Stroke patients using machine learning"
date: 2023-05-22
authors: ["VeronikaZimmer"]
draft: true

---

Machine learning, in particular deep learning, has reformed the research in the field of medical imaging, and the focus of this project will be on its use for the prediction of disease progression/ neurological outcome in stroke patients. Stroke patients have a high risk of developing dementia (incidence around 20\%) within a few months after the event, but so far the reasons and mechanisms are poorly understood [1]. Clinical parameters, such as age, smoking habit and previous health conditions have an influence, but are not sufficient to reliably predict the cognitive outcome. Imaging, for example magnetic resonance imaging (MRI), becomes increasingly important. Recently, we have developed a novel method to predict cognitive outcome after a stroke with a balanced accuracy of 80\% [2].  One drawback of the current model is that is relies on a complex preprocessing pipeline, including image registration and semi-automatic segmentation, which hinders its usefullness in clinical routine. 

The objective of this project is to develop a fully automatic end-to-end pipeline for cognitive outcome prediction in stroke patients. This will include (i) automating the segmentations using state-of-the-art learning-based segmentation methods, (ii) identifying the most influential preprocessing steps, and (iii) development of a functioning fully automatic pipeline for easy usability by clinicians and neurologists.

## Requirements

1. Prior experience and good understanding in machine learning and statistics. 
2. Good programming skills in python (and pytorch).
3. Interest in medical imaging

## Contacts
- Shuting Liu (shuting.liu@tum.de)
- Dr. Veronika Zimmer (veronika.zimmer@tum.de)

## References

1. F. A. Wollenweber et al.: The Determinants of Dementia After Stroke (DEDEMAS) Study: protocol and pilot data. International Journal of Stroke 9(3) (2014): 387-392.
2. S. Liu, R. Fang, D. Rueckert, V.A. Zimmer: Dynamic Graph Neural Representation Based Multi-modal Fusion 
Model for Cognitive Outcome Prediction in Stroke Cases. Under review.
