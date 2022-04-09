---
title: "ITA: Image-Text Alignments for Multi-Modal Named Entity Recognition"
collection: publications
permalink: /publication/naacl-2022-multimodal
excerpt: '**Xinyu Wang**, Min Gui, Yong Jiang, Zixia Jia, Nguyen Bach, Tao Wang, Zhongqiang Huang, Fei Huang, Kewei Tu.'
date: 2021-12-14
venue: 'NAACL Main Conference'
---

<!-- [pdf](https://arxiv.org/pdf/1906.07880.pdf)
[code](https://github.com/wangxinyu0922/Second_Order_SDP)
[bibtex](https://www.aclweb.org/anthology/P19-1454.bib) -->
[pdf](https://arxiv.org/abs/2112.06482)


Recently, Multi-modal Named Entity Recognition (MNER) has attracted a lot of attention. Most of the work utilizes image information through region-level visual representations obtained from a pretrained object detector and relies on an attention mechanism to model the interactions between image and text representations. However, it is difficult to model such interactions as image and text representations are trained separately on the data of their respective modality and are not aligned in the same space. As text representations take the most important role in MNER, in this paper, we propose {\bf I}mage-{\bf t}ext {\bf A}lignments (ITA) to align image features into the textual space, so that the attention mechanism in transformer-based pretrained textual embeddings can be better utilized. ITA first locally and globally aligns regional object tags and image-level captions as visual contexts, concatenates them with the input texts as a new cross-modal input, and then feeds it into a pretrained textual embedding model. This makes it easier for the attention module of a pretrained textual embedding model to model the interaction between the two modalities since they are both represented in the textual space. ITA further aligns the output distributions predicted from the cross-modal input and textual input views so that the MNER model can be more practical and robust to noises from images. In our experiments, we show that ITA models can achieve state-of-the-art accuracy on multi-modal Named Entity Recognition datasets, even without image information.
