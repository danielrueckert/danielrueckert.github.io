---
title: "MSc Thesis: Region-guided Chest X-Ray Report Generation"
date: 2022-01-26
authors: ["PhilipMueller"]
---

In clinical practice, medical experts like radiologists routinely write radiology reports for chest X-rays. Report generation models [1, 2, 3] try to generate such reports automatically given only the chest X-ray images without the need for human intervention. While such generation models are an interesting research topic, their practical use is limited as they often lack factual completeness and consistency [2] and are typically unable to include additional information not contained in the image.
Instead of generating reports fully automatically, we plan to keep the medical expert in the loop but try to assist during the creation of reports by providing sentence proposals or autocomplete for pre-defined regions (of the chest X-ray) selected by the user.

The goal of this project is to create a deep learning model that predicts report sentences for regions in chest X-rays. You use a model with a CNN-based image encoder and a transformer-based language model (e.g. a conditioned GPT-2 as in [4]).

## What we offer
- Close supervision and access to state-of-the-art computer hardware
- A strong research group with lots of practical experience
- Cutting-edge research in Medical NLP with the opportunity to publish your work

## Requirements
1. Advanced programming skills in Python and deep learning frameworks like PyTorch, JAX, or Tensorflow
2. Strong background in deep learning, preferable with experience in computer vision or NLP
3. Basic familiarity with transformer-based language models and/or text generation is preferable but not required

## References
- [1] J. Lovelace & B. Mortazavi "Learning to Generate Clinically Coherent Chest X-Ray Reports." EMNLP [[link]](https://aclanthology.org/2020.findings-emnlp.110.pdf) (2020)
- [2] Y. Miura et al. "Improving Factual Completeness and Consistency of Image-to-Text Radiology Report Generation." NAACL [[link]](https://aclanthology.org/2021.naacl-main.416.pdf) (2021)
- [3] G. Liu et al. "Clinically Accurate Chest X-Ray Report Generation." Machine Learning for Healthcare Conference [[link]](http://proceedings.mlr.press/v106/liu19a/liu19a.pdf) (2019)
- [4] O. Alfarghaly et al. "Automated radiology report generation using conditioned transformers." Informatics in Medicine Unlocked 24 [[link]](https://www.sciencedirect.com/science/article/pii/S2352914821000472) (2021)
