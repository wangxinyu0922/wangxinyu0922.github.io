---
title: "Named Entity and Relation Extraction with Multi-Modal Retrieval"
collection: publications
permalink: /publication/emnlp-2022-mkb
excerpt: '**Xinyu Wang**<sup>\*</sup>, Jiong Cai<sup>\*</sup>, Yong Jiang, Pengjun Xie, Kewei Tu, and Wei Lu.'
date: 2022-10-06
venue: 'Findings of EMNLP'
---

<!-- [pdf](https://arxiv.org/pdf/1906.07880.pdf)
[code](https://github.com/wangxinyu0922/Second_Order_SDP)
[bibtex](https://www.aclweb.org/anthology/P19-1454.bib) -->
<!-- [pdf](http://faculty.sist.shanghaitech.edu.cn/faculty/tukw/emnlp_f20emb.pdf) -->

Multi-modal named entity recognition (NER) and relation extraction (RE) aim to leverage relevant image information to improve the performance of NER and RE. 
Most existing efforts largely focused on directly extracting potentially useful information from images (such as pixel-level features, identified objects, and associated captions). However, such extraction processes may not be knowledge aware, resulting in information that may not be highly relevant.
In this paper, we propose a novel \underline{M}ulti-m\underline{o}dal \underline{Re}trieval based framework (MoRe). MoRe contains a text retrieval module and an image-based retrieval module, which retrieve related knowledge of the input text and image in the knowledge corpus respectively. Next, the retrieval results are sent to the textual and visual models respectively for predictions. Finally, a Mixture of Experts (MoE) module combines the predictions from the two models to make the final decision. Our experiments show that both our textual model and visual model can achieve state-of-the-art performance on four multi-modal NER datasets and one multi-modal RE dataset. With MoE, the model performance can be further improved and our analysis demonstrates the benefits of integrating both textual and visual cues for such tasks.