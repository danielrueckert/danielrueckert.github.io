---
title: "MSc Thesis: Adversarial attacks in collaborative machine learning"
date: 2022-01-11
authors: ["DmitriiUsynin"]
tags:
    - Federated Learning
    - Model Inversion Attack
    - Membership Inference Attack
    - Adversarial Machine Learning

---
Collaborative machine learning has became the new paradigm-of-choice when it comes to training deep learning models in many fields, including medical image analysis. Due to a number of data protection and governance regulations being introduced, direct data sharing for such training is rendered problematic. As a result implementations that rely on local training, such as federated learning (FL) have been widely adopted. However, a number of studies [1,2] have shown that such paradigms are deeply vulnerable to adversarial influence either in the form of privacy violation [3] or utility degradation [4]. Fortunately for the research community, such attacks are often very fragile and require a number of assumptions to hold in practise. The aim of this project is to explore the recent advances in adversarial machine learning in order to investigate how to adapt them to the real-world machine learning contexts in order to encourage the research community and policymakers to employ safe, robust and privacy-preserving systems when working with sensitive personally-identifying information. 

This project is deliberately very open-ended, as there is a large number of various attack vectors that could be pursued: attacks on membership, reconstruction of sensitive attributes or training samples, insertion of auxiliary learning tasks etc. Our lab has experience primarily with privacy-oriented attacks on machine learning, but we are otherwise happy to consider students with interest in any other attack formulation.

We additionally consider students interested in attacks on software systems outside of machine learning, but can offer limited guidance on such proposals.

<br/>

## Your qualifications:

- Basic familiarity with existing collaborative machine learning paradigms, preferably federated learning.
- Basic familiarity with attacks on machine learning models (all information can be found in the references). 
- Advanced knowledge of machine learning and computer vision. 
- Excellent programming skills in Python and PyTorch.

<br/>

## What we offer:

- Ability to perform cutting edge research in the field of adversarial and privacy-preserving machine learning. 
- Closely working and collaborating with a team of experts in privacy-preserving machine learning, deep learning and medical image analysis.
- This project is targeting publication at leading privacy and security conferences/journals (e.g. PETS)
<br/>

## References
[1] Usynin, Dmitrii, et al. "Adversarial interference and its mitigations in privacy-preserving collaborative machine learning." Nature Machine Intelligence 3.9 (2021): 749-758.

[2] Usynin, Dmitrii, et al. "Distributed Machine Learning and the Semblance of Trust." arXiv preprint arXiv:2112.11040 (2021).

[3] Shokri, Reza, et al. "Membership inference attacks against machine learning models." 2017 IEEE Symposium on Security and Privacy (SP). IEEE, 2017.

[4] Bagdasaryan, Eugene, et al. "How to backdoor federated learning." International Conference on Artificial Intelligence and Statistics. PMLR, 2020.