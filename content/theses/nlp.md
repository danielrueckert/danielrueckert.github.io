---
title: "MSc Thesis: Deep Natural Language Processing for Radiology Reports"
date: 2021-02-16
authors: ["PhilipMueller"]
---

In recent years deep learning has proven quite successful in the field of natural language processing (NLP). However, many of today’s NLP models require very large datasets for training, thus self-supervised pre-training (like BERT [1]) on large unlabeled datasets has become quite important.

We want to apply deep NLP models (like transformers) to radiology reports and do predictions on them. While there is a large variety of pre-trained models available which we could utilize for this task (like [2,3]), these models suffer from a language domain-shift when directly applied to German radiology reports as available models are typically not pre-trained on German medical language.
Thus, our goal is to pre-train a NLP model for the domain of German radiology reports such that the resulting model can be easily fine-tuned for prediction tasks.

We offer flexibility regarding the objectives of this MSc thesis.
Possible tasks may include but are not limited to:
-   Domain adaptation of pre-trained models
-   Adaption or development of a pre-training strategy for radiology reports
-   Development of a model architecture for radiology reports
-   Development of a data augmentation strategy
-   Utilization of additional data sources for pre-training (e.g. Wikipedia or books)

We can define the topic of your thesis, such that it matches your interests as good as possible.

## Requirements
1.  Strong background in deep learning
2.  Proficient in Python
3.  Experience with ML frameworks, preferable PyTorch

Prior experience or knowledge (e.g. lectures) in NLP is beneficial but not required.

## References
1.  J. Devlin et al. "Bert: Pre-training of deep bidirectional transformers for language understanding." arXiv preprint [arXiv:1810.04805](https://arxiv.org/abs/1810.04805) (2018).
2.  E. Alsentzer et al. “Publicly Available Clinical BERT Embeddings.” arXiv preprint [arXiv:1904.03323](https://arxiv.org/abs/1904.03323) (2019)
3.  B. Chan et al. “German’s Next Language Model.” arXiv preprint [arXiv:2010.10906](https://arxiv.org/abs/2010.10906) (2020)
