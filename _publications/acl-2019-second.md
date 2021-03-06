---
title: "Second-Order Semantic Dependency Parsing with End-to-End Neural Networks"
collection: publications
permalink: /publication/acl-2019-second
excerpt: '**Xinyu Wang**, Jingxian Huang and Kewei Tu.'
date: 2019-07-28
venue: 'Proceedings of ACL'
---

[pdf](https://arxiv.org/pdf/1906.07880.pdf)
[code](https://github.com/wangxinyu0922/Second_Order_SDP)
[bibtex](https://www.aclweb.org/anthology/P19-1454.bib)

Semantic dependency parsing aims to identify semantic relationships between words in a sentence that form a graph. In this paper, we propose a second-order semantic dependency parser, which takes into consideration not only individual dependency edges but also interactions between pairs of edges. We show that second-order parsing can be approximated using mean field (MF) variational inference or loopy belief propagation (LBP). We can unfold both algorithms as recurrent layers of a neural network and therefore can train the parser in an end-to-end manner. Our experiments show that our approach achieves state-of-the-art performance.