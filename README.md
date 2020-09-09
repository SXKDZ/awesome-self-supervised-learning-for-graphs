# Awesome Self-Supervised Learning for Graphs  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list for awesome self-supervised graph representation learning resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), and [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning).

## Background

> Self-supervised learning is the future! — Yann LeCun

Recently self-supervised learning (SSL) techniques have gained success in many domains, e.g., visual, natural language processing, and robotics, where SSL methods even outperform their supervised counterparts. However, the development of SSL in the graph domain is still at a nascent stage. Can SSL graph representation achieve similar or even better performance than its supervised opponents? This repository provides you with a curated list of awesome self-supervised graph representation learning resources. Following [[Ankesh Anand 2020](https://ankeshanand.com/blog/2020/01/26/contrative-self-supervised-learning.html)], we roughly divide papers into two lines: generative/predictive (i.e. optimizing in the output space) and contrastive methods (i.e. optimizing in the latent space). Along with papers, we also list several must-read blog posts and talks.

## Contribution

Feel free to send [pull requests](pulls) to add more links!

## Table of Contents

* [Papers](#papers)
  * [Survey](#survey)
  * [Generative/Predictive Methods](#generative/predictive-methods)
  * [Contrastive Methods](#contrastive-methods)
* [Blog Posts](#blog-posts)
* [Talks](#talks)

## Papers

### Survey

* X. Liu, F. Zhang, Z. Hou, Z. Wang, L. Mian, J. Zhang, and J. Tang, Self-supervised Learning: Generative or Contrastive, 2020. [[PDF](http://arxiv.org/abs/2006.08218)]

### Generative/Predictive Methods

* K. Sun, Z. Lin, and Z. Zhu, Multi-Stage Self-Supervised Learning for Graph Convolutional Networks on Graphs with Few Labeled Nodes, in AAAI, 2020. [[PDF](https://aaai.org/ojs/index.php/AAAI/article/view/6048/5904)]
* W. Hu, B. Liu, J. Gomes, M. Zitnik, P. Liang, V. Pande, and J. Leskovec, Strategies for Pre-training Graph Neural Networks, in ICLR, 2020. [[PDF](https://openreview.net/forum?id=HJlWWJSFDH)]
* Z. Hu, Y. Dong, K. Wang, K.-W. Chang, and Y. Sun, GPT-GNN: Generative Pre-Training of Graph Neural Networks, in KDD, 2020. [[PDF]](https://dl.acm.org/doi/10.1145/3394486.3403237), [Code]()]

### Contrastive Methods

* P. Veličković, W. Fedus, W. L. Hamilton, P. Liò, Y. Bengio, and R. D. Hjelm, Deep Graph Infomax, in ICLR, 2019. [[PDF](https://openreview.net/forum?id=rklz9iAcKQ), [Code](https://github.com/PetarV-/DGI)]
* F. L. Opolka, A. Solomon, C. Cangea, P. Veličković, P. Liò, and R. D. Hjelm, Spatio-Temporal Deep Graph Infomax, in ICLR-W (RLGM), 2019. [[PDF](https://arxiv.org/abs/1904.06316)]
* K. Hassani and A. H. Khasahmadi, Contrastive Multi-View Representation Learning on Graphs, in ICML, 2020. [[PDF](http://arxiv.org/abs/2006.05582)]
* Y. Zhu, Y. Xu, F. Yu, Q. Liu, S. Wu, and L. Wang, Deep Graph Contrastive Representation Learning, in ICML-W (GRL+), 2020. [[PDF](http://arxiv.org/abs/2006.04131)]
* J. Qiu, Q. Chen, Y. Dong, J. Zhang, H. Yang, M. Ding, K. Wang, and J. Tang, GCC: Graph Contrastive Coding for Graph Neural Network Pre-Training, in KDD, 2020. [[PDF](https://dl.acm.org/doi/10.1145/3394486.3403168)]

## Blog Posts

## Talks

