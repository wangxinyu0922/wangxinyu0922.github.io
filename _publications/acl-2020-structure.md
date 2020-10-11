---
title: "Structure-Level Knowledge Distillation For Multilingual Sequence Labeling"
collection: publications
permalink: /publication/acl-2020-structure
excerpt: '**Xinyu Wang**, Yong Jiang, Nguyen Bach, Tao Wang, Fei Huang,  Kewei Tu.'
date: 2020-07-05
venue: 'Proceedings of ACL'
---

<!-- [pdf](https://arxiv.org/pdf/1906.07880.pdf)
[code](https://github.com/wangxinyu0922/Second_Order_SDP)
[bibtex](https://www.aclweb.org/anthology/P19-1454.bib) -->
[pdf](https://arxiv.org/pdf/2004.03846.pdf)
[code](https://github.com/Alibaba-NLP/MultilangStructureKD)
[bibtex](https://www.aclweb.org/anthology/2020.acl-main.304.bib)

Multilingual sequence labeling is a task of predicting label sequences using a single unified model for multiple languages. Compared with relying on multiple monolingual models, using a multilingual model has the benefit of a smaller model size, easier in online serving, and generalizability to low-resource languages. However, current multilingual models still underperform individual monolingual models significantly due to model capacity limitations. In this paper, we propose to reduce the gap between monolingual models and the unified multilingual model by distilling the structural knowledge of several monolingual models (teachers) to the unified multilingual model (student). We propose two novel KD methods based on structure-level information: (1) approximately minimizes the distance between the student's and the teachers' structure-level probability distributions, (2) aggregates the structure-level knowledge to local distributions and minimizes the distance between two local probability distributions. Our experiments on 4 multilingual tasks with 25 datasets show that our approaches outperform several strong baselines and have stronger zero-shot generalizability than both the baseline model and teacher models.