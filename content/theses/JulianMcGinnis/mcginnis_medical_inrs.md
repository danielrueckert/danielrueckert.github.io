---
title: "MSc Thesis: Implicit Neural Representations for Medical Applications"
date: 2023-06-16
authors: ["JulianMcGinnis"]
---
 
Implicit Neural Representations (INR) have emerged as powerful and compact representations for audio, shapes and images, and have recently been translated into medical applications [1].
Our recent work has shown that INRs can be used in multi-contrast MRI super-resolution, reconstructing high-resolution images from low-resolution scans, while preserving anatomical details and pathological findings, such as lesions and tumors. Notably, these methods require only training data of a single patient, allowing to use these models in the context of patient-specific super-resolution, making them attractive for clinical settings.

Built upon our recent findings, we are interested in incorporating novel concepts such as modulated periodic activation functions [2] and meta-learning [3], to scale INRs to cohorts of patients by incorporating priors learned over a dataset. Once incorporated, we aim to solve various medical downstream tasks in brain and spinal cord imaging, enabling our clinical partners to work on exciting scientific questions.
<br/><br/> 
 
## Your qualifications:
We are looking for a highly motivated Master’s student in Computer Science, Physics, Engineering or Mathematics. Your goal is to extend the existing Pytorch codebase by incorporating novel algorithms and methods. Importantly, we aim to publish the results of this work, with you, in a follow up study at a high-impact machine learning conference or in an academic journal.

1. Strong motivation and interest in machine learning.
2. Advanced programming skills in C++, Python or C.
3. Strong interest in teamwork and interdisciplinary research.
<br/><br/>

## What we offer:
- An exciting research project with many possibilities to bring in your own ideas.
- Close supervision and access to state-of-the-art computer hardware.
- The chance to work in a team of highly qualified experts in machine learning, computer vision and deep learning.
<br/><br/>

## How to apply:
Please send us a short e-mail with your CV and grade report to julian.mcginnis@tum.de and suprosanna.shit@tum.de. 
<br/><br/>

## References
[1] McGinnis J, Shit S, Li HB, Sideri-Lampretsa V, Graf R, Dannecker M, Pan J, Ansó NS, Mühlau M, Kirschke JS, Rueckert D. Multi-contrast MRI Super-resolution via Implicit Neural Representations. https://arxiv.org/pdf/2303.15065.pdf </br>
[2] Mehta, Ishit, Michaël Gharbi, Connelly Barnes, Eli Shechtman, Ravi Ramamoorthi, and Manmohan Chandraker. "Modulated periodic activations for generalizable local functional representations." In *Proceedings of the IEEE/CVF International Conference on Computer Vision*, pp. 14214-14223. 2021. https://openaccess.thecvf.com/content/ICCV2021/papers/Mehta_Modulated_Periodic_Activations_for_Generalizable_Local_Functional_Representations_ICCV_2021_paper.pdf </br>
[3]  Sitzmann, Vincent, Eric Chan, Richard Tucker, Noah Snavely, and Gordon Wetzstein. "Metasdf: Meta-learning signed distance functions." Advances in Neural Information Processing Systems 33 (2020): 10136-10147.21. https://papers.nips.cc/paper/2020/file/731c83db8d2ff01bdc000083fd3c3740-Paper.pdf </br>