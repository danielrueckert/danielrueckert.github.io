---
title: "MSc Thesis: Combining longitudinal volumetric imaging and tabular data for depression prediction"
date: 2022-09-27
authors: ["VasilikiSideri-Lampretsa"]
---

The objective of this project is to combine volumetric imaging and non-imaging longitudinal data to accurately analyze individual patients and provide automated decisions regarding diagnosis and disease prognosis. Physicians consider various medical biomarkers and meta-data to reach a clinical decision. Thus, creating computer-assisted diagnostic systems that operate in a similar manner could be highly beneficial.
 

The aim is to align imaging and other medical information, such as medical history, blood values, sleep habits, genetic information, and more, in the feature space using a contrastive loss. The approach will integrate multiple modalities of each patient from various time points in the same model in an end-to-end fashion. The method can be fully supervised or be used in a self-supervision scheme, in which our model can learn the aligned embedding space of imaging and non-imaging data using a proxy task from the data itself. Afterward, the learned embeddings can be finetuned for downstream tasks, such as depression prediction [1].

The project will be completed under the supervision of Dr. Magdalini Paschali (Stanford University) and Vasiliki Sideri-Lampretsa (TUM). Computational resources and datasets [1] will be provided.
<br/>

## Your qualifications:

- Aadvanced knowledge in machine learning and computer vision – ability to understand and reproduce state-of-the-art publications
- Good programming skills in Python (numpy, pandas, seaborn, scikit-learn) and PyTorch
- Excellent communication skills and ability to work remotely

<br/>

## What we offer:

- An exciting, international research project with real world medical data
- Freedom to come up with and propose your own ideas
- GPU resources
- An interdisciplinary team of high qualified experts in deep learning, statistics, medical imaging, and neuroscience
- Opportunity to participate in lab meetings as well as a workspace in TranslaTUM

<br/>

## References

[1] Paschali, M., Kiss, O., Zhao, Q., Adeli, E., Podhajsky, S., Müller-Oehring, E.M., Gotlib, I.H., Pohl, K.M. and Baker, F.C., 2022. Detecting negative valence symptoms in adolescents based on longitudinal self-reports and behavioral assessments. Journal of Affective Disorders.
 
[2] Brown, S.A., Brumback, T.Y., Tomlinson, K., Cummins, K., Thompson, W.K., Nagel, B.J., De Bellis, M.D., Hooper, S.R., Clark, D.B., Chung, T. and Hasler, B.P., 2015. The National Consortium on Alcohol and NeuroDevelopment in Adolescence (NCANDA): a multisite study of adolescent development and substance use. Journal of studies on alcohol and drugs, 76(6), pp.895-908.
