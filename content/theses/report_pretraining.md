---
title: "MSc Thesis: Contrastive Pre-Training for Radiology Reports"
date: 2022-01-26
authors: ["PhilipMueller"]
---

In recent years transformer-based language models have proven quite successful in the field of natural language processing (NLP). 
These models require huge amounts of training data and are therefore typically pre-trained on unlabelled datasets using self-supervised objectives
like masked language modelling (MLM) as proposed in BERT [1]. 
While models like BioBERT [2] are pre-trained on the medical domain, the used pre-training objectives like MLM treat text as independent sentences and do not utilise the structure of medical documents.
In this project we instead make use of the semi-structured nature of radiology reports and apply contrastive methods on the sections of these reports. 
Your task is the adaptation of such contrastive methods (e.g. SimCLR [3], BYOL [4], DINO [5], …) to be used effectively on language models. 

## What we offer
- Close supervision and access to state-of-the-art computer hardware
- A strong research group with lots of practical experience
- Cutting-edge research in Medical NLP with the opportunity to publish your work

## Requirements
1. Advanced programming skills in Python and deep learning frameworks like PyTorch, JAX, or Tensorflow
2. Strong background in deep learning, preferable (but not required) with experience in NLP
3. Basic familiarity with self-supervised methods like SimCLR is preferable but not required

## References
- [1] J. Devlin et al. “Bert: Pre-training of deep bidirectional transformers for language understanding.”  arXiv preprint [[arXiv:1810.04805]](https://arxiv.org/abs/1810.04805) (2018).
- [2] J. Lee et al. “BioBERT: a pre-trained biomedical language representation model for biomedical text mining.” Bioinformatics 4.36 [[link]](https://academic.oup.com/bioinformatics/article/36/4/1234/5566506) (2020)
- [3] T. Chen et al. “Big Self-Supervised Models are Strong Semi-Supervised Learners.” NeurIPS [[arXiv:2006.10029]](https://arxiv.org/abs/2006.10029) (2020)
- [4] J. Grill et al. “Bootstrap Your Own Latent A New Approach to Self-Supervised Learning.” NIPS [[link]](https://papers.nips.cc/paper/2020/file/f3ada80d5c4ee70142b17b8192b2958e-Paper.pdf) (2020)
- [5] M. Caron et al. "Emerging Properties in Self-Supervised Vision Transformers." ICCV [[arXiv:2104.14294]](https://arxiv.org/abs/2104.14294) (2021)


