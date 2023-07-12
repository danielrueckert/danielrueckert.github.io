---
title: "MSc Thesis: Federated, privacy preserving deep learning for fetal MRI brain segmentation"
date: 2022-08-19
authors: ["MaikDannecker"]
---

In medical domain data protection and privacy preservation is highly relevant. Therefore, clinical data of patients is usually securely stored on clinic servers without access from outside.
Publication of clinical data is difficult and cumbersome as strict privacy and data protection laws must be obeyed. 
These involve anonymization of patient data, drafting of data sharing agreements, and the approval of the corresponding ethics commission. 
This complex publication process is one of the key reasons for data shortage in medical domain and is often preventing machine learning approaches to reach their full potential. 
Federated learning [1] paired with differential privacy [2,3] can circumvent the problem of data publication. 
Rather than gathering the data from clinical sites to centrally train a machine learning model, the model is distributed to the different sites, locally trained on the (partial) data, and finally, globally aggregated [2]. 
Thus, patient data is never seen by third parties.<br/>

We want to construct a proof of concept for a federated learning approach in the domain of fetal MRI segmentation. An existing baseline segmentation model must be modified and embedded in a federated learning environment. The model must then be trained on fetal MRI scans located on several international clinic servers. Furthermore, sufficient privacy standards (e.g. differential privacy [2]) must be discussed and ensured.
## Your qualifications:

1. advanced knowledge in machine learning and computer vision (experience in federated learning or differential privacy is helpful but not mandatory)
2. good programming skills in Python and a deep learning framework (previous work is based on
PyTorch).
3. good communication skills. The project will require you to cooperate with different clinics of various countries.


<br/>

## What we offer:

- insight to an international research project with real world medical data
- freedom to come up with-, and to pursue your own ideas
- hardware (sufficient GPU resources)
- an interdisciplinary team of high qualified experts in image processing, deep
learning, federated learning, and differential privacy

<br/>

## References

[1] Jakub Konečný et al. “Federated learning: Strategies for improving communication efficiency”.
In: arXiv preprint arXiv:1610.05492 (2016).<br/>
[2] Georgios Kaissis et al. “End-to-end privacy preserving deep learning on multi-institutional medical
imaging”. In: Nature Machine Intelligence 3.6 (2021), pp. 473–484.<br/>
[3] Alexander Ziller et al. “Differentially private federated deep learning for multi-site medical image
segmentation”. In: arXiv preprint arXiv:2107.02586 (2021).<br/>