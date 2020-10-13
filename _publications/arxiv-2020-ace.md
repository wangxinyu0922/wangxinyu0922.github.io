---
title: "Automated Concatenation of Embeddings for Structured Prediction"
collection: publications
permalink: /publication/arxiv-2020-ace
excerpt: '**Xinyu Wang**, Yong Jiang, Nguyen Bach, Tao Wang, Zhongqiang Huang, Fei Huang, Kewei Tu.'
date: 2020-10-13
venue: 'Arxiv'
---

<!-- [pdf](https://arxiv.org/pdf/1906.07880.pdf)
[code](https://github.com/wangxinyu0922/Second_Order_SDP)
[bibtex](https://www.aclweb.org/anthology/P19-1454.bib) -->
[pdf](http://arxiv.org/abs/2010.05006)
[code](https://github.com/Alibaba-NLP/ACE)


Pretrained contextualized embeddings are powerful word representations for structured prediction tasks. Recent work found that better word representations can be obtained by concatenating different types of embeddings. However, the selection of embeddings to form the best concatenated representation usually varies depending on the task and the collection of candidate embeddings, and the ever-increasing number of embedding types makes it a more difficult problem. In this paper, we propose Automated Concatenation of Embeddings (ACE) to automate the process of finding better concatenations of embeddings for structured prediction tasks, based on a formulation inspired by recent progress on neural architecture search. Specifically, a controller alternately samples a concatenation of embeddings, according to its current belief of the effectiveness of individual embedding types in consideration for a task, and updates the belief based on a reward. We follow strategies in reinforcement learning to optimize the parameters of the controller and compute the reward based on the accuracy of a task model, which is fed with the sampled concatenation as input and trained on a task dataset. Empirical results on 6 tasks and 23 datasets show that our approach outperforms strong baselines and achieves state-of-the-art performance with fine-tuned embeddings in the vast majority of evaluations.