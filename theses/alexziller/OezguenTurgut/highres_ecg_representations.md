---
title: "MSc Thesis: Learning High-Resolution ECG Representations for Cardiac Health Analysis"
date: 2023-11-08
authors: ["OezguenTurgut"]
---
Examinations with expensive cardiac magnetic resonance (CMR) imaging provide detailed structural information of the heart as it cycles at least one heartbeat. Since the dynamics of the heart are important for analysing cardiac health, CMR imaging is the gold-standard for evidence-based diagnosis of cardiovascular diseases (leading causes of death globvally [1]). However, long scan times and high costs limit its use in clinical practice. In this project, we aim to adress this issue by enabling cardiac health analysis using cost-effective and widely available electrocardiograms (ECG) only. The objective is to learn cardiac representations with high temporal resolution from ECG, with a focus on capturing the dynamics of a single heartbeat. 

Similar to previous works [2], we propose the integration of spatiotemporal information from CMR imaging into the representation learning process, enhancing the interpretation of ECG data. Contrastive learning techniques [3] should be leveraged to transfer information from CMR imaging to high-resolution ECG representations of a single heartbeat. To this end, strategies to extract a representative heartbeat from ECG recordings have to be investigated, considering the variation in heartbeat length within a recording. Furthermore, techniques to synchronise cardiac cycles between ECG and CMR imaging data have to be developed, accounting for the temporal offset in data acquisition.

We will evaluate the strength of our approach on multiple downstream tasks, including the classification of various cardiovascular diseases and regression of cardiac phenotypes solely from ECG data. Experiments on paired ECG and CMR imaging data of 40k subjects provided by the UK Biobank population study are conducted within this work. 
<br/><br/> 
 
## Your qualifications:
- Advanced programming skills in Python and PyTorch.
- Strong analytical and problem-solving skills, particularly in working with complex and multimodal datasets.
- Excellent communication skills to document and present research findings effectively.
<br/><br/>

## What we offer:
- The chance to work with an experienced team of data scientists and medical experts. 
- Close supervision with regular meetings to provide guidance and feedback.
- An opportunity to collaborate on challenging aspects of a clinical research project.
<br/><br/>

## How to apply:
Please send an e-mail with your CV and grade report to oezguen.turgut@tum.de. 
<br/><br/>

## References
[1] [The top 10 causes of death (World Health Organization)](https://www.who.int/news-room/fact-sheets/detail/the-top-10-causes-of-death) <br/>
[2] [Unlocking the Diagnostic Potential of ECG through Knowledge Transfer from Cardiac MRI](https://arxiv.org/abs/2308.05764) <br/>
[3] [A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/abs/2002.05709)
