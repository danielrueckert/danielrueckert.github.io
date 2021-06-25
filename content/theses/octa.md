---
title: "MSc Thesis: Unsupervised deep learning for vessel segmentation in optical coherence tomography angiographs"
date: 2021-06-23
authors: ["MartinMenten"]
---

Optical coherence tomography angiography (OCTA) is an imaging technique that visualizes blood vessels by detecting motion of red blood cells in sequential scans [1]. It has seen initial adoption for the diagnosis and monitoring of clinical conditions that affect the retinal vasculature, such as several different eye diseases or multiple sclerosis [2, 3]. However, its effective clinical use is often impeded by the occurrence of imaging artifacts and lack of tools that can extract the vessel maps from the images. Only few studies have explored the use of deep-learning-based segmentation to delineate vessels in two-dimensional OCTA images [4, 5]. The development of three-dimensional (3D) segmentation algorithms has proven difficult due to a lack of publicly available datasets with ground truth annotations, which are difficult and time-consuming to acquire for the large and complex OCTA images [5].

This project aims at tackling the problem of 3D vessel segmentation in OCTA images using unsupervised and weakly supervised deep learning. The prospective student will adopt existing deep-learning-based segmentation algorithms so that these can be trained using self-supervision and noisy annotations. All developed methods will be evaluated on a large dataset of OCTA images collected at the Klinikum rechts der Isar.

<br/>

## Your qualifications:

- Enthusiasm for deep learning and biomedical imaging.
- Advanced knowledge of machine learning and computer vision. Ideally, prior work experience using deep learning for image processing.
- Excellent programming skills in Python, PyTorch or Tensorflow. Familiarity with C++ is helpful.

<br/>

## What we offer:

- An exciting research project with many possibilities to bring in your own ideas.
- Close supervision and access to state-of-the-art computer hardware.
- The chance to work in a team of experts in image processing, deep learning, biomedical engineering and medicine.

<br/>

## References

[1] De Carlo, T. E., Romano, A., Waheed, N. K., & Duker, J. S. (2015). A review of optical coherence tomography angiography (OCTA). International journal of retina and vitreous, 1(1), 5. </br>
[2] Chalam, K. V., & Sambhav, K. (2016). Optical coherence tomography angiography in retinal diseases. Journal of ophthalmic & vision research, 11(1), 84. </br>
[3] Feucht, N., Maier, M., Lepennetier, G., Pettenkofer, M., Wetzlmair, C., Daltrozzo, T., ... & Knier, B. (2019). Optical coherence tomography angiography indicates associations of the retinal vascular network and disease activity in multiple sclerosis. Multiple Sclerosis Journal, 25(2), 224-234. </br>
[4] Mou, L., Zhao, Y., Chen, L., Cheng, J., Gu, Z., Hao, H., ... & Liu, J. (2019, October). CS-Net: channel and spatial attention network for curvilinear structure segmentation. In International Conference on Medical Image Computing and Computer-Assisted Intervention (pp. 721-730). Springer, Cham. </br>
[5] Ma, Y., Hao, H., Xie, J., Fu, H., Zhang, J., Yang, J., ... & Zhao, Y. (2020). ROSE: a retinal OCT-angiography vessel segmentation dataset and new model. IEEE transactions on medical imaging, 40(3), 928-939. </br>
[6] Schneider, M., Reichold, J., Weber, B., Székely, G., & Hirsch, S. (2012). Tissue metabolism driven arterial tree generation. Medical image analysis, 16(7), 1397-1414. </br>
[7] Kato, H., Beker, D., Morariu, M., Ando, T., Matsuoka, T., Kehl, W., & Gaidon, A. (2020). Differentiable rendering: A survey. arXiv preprint arXiv:2006.12057.