# Awesome Self-Supervised Learning for Graphs

 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![GitHub stars](https://img.shields.io/github/stars/SXKDZ/awesome-self-supervised-learning-for-graphs?color=yellow)  ![GitHub forks](https://img.shields.io/github/forks/SXKDZ/awesome-self-supervised-learning-for-graphs?color=green&label=Fork)  ![visitors](https://visitor-badge.glitch.me/badge?page_id=SXKDZ.awesome-self-supervised-learning-for-graphs)

A curated list for awesome self-supervised graph representation learning resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), and [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning).

## Background

> Self-supervised learning is the future! — Yann LeCun

Recently self-supervised learning (SSL) techniques have gained success in many domains, e.g., visual, natural language processing, and robotics, where SSL methods even outperform their supervised counterparts. However, the development of SSL in the graph domain is still at a nascent stage. Can SSL graph representation achieve similar or even better performance than its supervised opponents? This repository provides you with a curated list of awesome self-supervised graph representation learning resources. Following [[Ankesh Anand 2020](https://ankeshanand.com/blog/2020/01/26/contrative-self-supervised-learning.html)], we roughly divide papers into two lines: generative/predictive (i.e. optimizing in the output space) and contrastive methods (i.e. optimizing in the latent space). Along with papers, we also list several must-read blog posts and talks.

## Contribution

Feel free to send [pull requests](pulls) to add more links!

## Table of Contents

* [Papers](#papers)
  * [Survey](#survey)
  * [Generative/Predictive Methods](#generativepredictive-methods)
  * [Contrastive Methods](#contrastive-methods)
* [Blog Posts](#blog-posts)
* [Talks](#talks)

## Papers

### Survey

* Self-supervised Learning: Generative or Contrastive

  X. Liu, F. Zhang, Z. Hou, Z. Wang, L. Mian, J. Zhang, and J. Tang

  arXiv 2020  [[PDF](https://arxiv.org/abs/2006.08218)]

### Generative/Predictive Methods

* Multi-Stage Self-Supervised Learning for Graph Convolutional Networks on Graphs with Few Labeled Nodes

  K. Sun, Z. Lin, and Z. Zhu

  AAAI 2020  [[PDF](https://aaai.org/ojs/index.php/AAAI/article/view/6048/5904), [Code](https://github.com/datake/M3S)]

  ▷*Node representation learning*

* Strategies for Pre-training Graph Neural Networks

  W. Hu, B. Liu, J. Gomes, M. Zitnik, P. Liang, V. Pande, and J. Leskovec

  ICLR 2020  [[PDF](https://openreview.net/forum?id=HJlWWJSFDH), [Code](https://github.com/snap-stanford/pretrain-gnns/)]

  ▷*Pretraining graphs*

* When Does Self-Supervision Help Graph Convolutional Networks?

  Y. You, T. Chen, Z. Wang, and Y. Shen

  ICML 2020  [[PDF](http://arxiv.org/abs/2006.09136), [Code](https://github.com/Shen-Lab/SS-GCNs)]

  ▷*Node representation learning*

* GPT-GNN: Generative Pre-Training of Graph Neural Networks

  Z. Hu, Y. Dong, K. Wang, K.-W. Chang, and Y. Sun

  KDD 2020  [[PDF](https://dl.acm.org/doi/10.1145/3394486.3403237), [Code](https://github.com/acbull/GPT-GNN)]

  ▷*Pretraining graphs*

* CAGNN: Cluster-Aware Graph Neural Networks for Unsupervised Graph Representation Learning

  Y. Zhu, Y. Xu, F. Yu, S. Wu, and L. Wang

  arXiv 2020  [[PDF](https://arxiv.org/abs/2009.01674)]

  ▷*Node representation learning*

* Self-supervised Learning on Graphs: Deep Insights and New Direction

  W. Jin, T. Derr, H. Liu, Y. Wang, S. Wang, Z. Liu, and J. Tang

  arXiv 2020  [[PDF](https://arxiv.org/abs/2006.10141), [Code](https://github.com/ChandlerBang/SelfTask-GNN)]

  ▷*Node representation learning*

### Contrastive Methods

- Deep Graph Infomax

  P. Veličković, W. Fedus, W. L. Hamilton, P. Liò, Y. Bengio, and R. D. Hjelm

  ICLR 2019  [[PDF](https://openreview.net/forum?id=rklz9iAcKQ), [Code](https://github.com/PetarV-/DGI)]

  ▷*Node representation learning*

- Spatio-Temporal Deep Graph Infomax

  F. L. Opolka, A. Solomon, C. Cangea, P. Veličković, P. Liò, and R. D. Hjelm

  ICLR-W (RLGM) 2019  [[PDF](https://arxiv.org/abs/1904.06316)]

  ▷*Node representation learning*

- Graph Representation Learning via Graphical Mutual Information Maximization

  Z. Peng, W. Huang, M. Luo, Q. Zheng, Y. Rong, T. Xu, and J. Huang

  WWW 2020  [[PDF](https://dl.acm.org/doi/10.1145/3366423.3380112), [Code](https://github.com/zpeng27/GMI)]

  ▷*Node representation learning*

- Contrastive Learning of Structured World Models

  T. N. Kipf, E. van der Pol, and M. Welling

  ICLR 2020  [[PDF](https://openreview.net/forum?id=H1gax6VtDB), [Code](https://github.com/tkipf/c-swm)]

  ▷*Relational inference*

- Contrastive Multi-View Representation Learning on Graphs

  K. Hassani and A. H. Khasahmadi

  ICML 2020  [[PDF](https://arxiv.org/abs/2006.05582), [Code](https://github.com/kavehhassani/mvgrl)]

  ▷*Node/graph representation learning*

- Deep Graph Contrastive Representation Learning

  Y. Zhu, Y. Xu, F. Yu, Q. Liu, S. Wu, and L. Wang

  ICML-W (GRL+) 2020  [[PDF](https://arxiv.org/abs/2006.04131), [Code](https://github.com/CRIPAC-DIG/GRACE/)]

  ▷*Node representation learning*

- GCC: Graph Contrastive Coding for Graph Neural Network Pre-Training

  J. Qiu, Q. Chen, Y. Dong, J. Zhang, H. Yang, M. Ding, K. Wang, and J. Tang

  KDD 2020  [[PDF](https://dl.acm.org/doi/10.1145/3394486.3403168), [Code](https://github.com/THUDM/GCC)]

  ▷*Pretraining graphs*

- Graph Contrastive Learning with Augmentations

  Y. You, T. Chen, Y. Sui, T. Chen, Z. Wang, and Y. Shen

  NeurIPS 2020  [[PDF](http://arxiv.org/abs/2010.13902), [Code](https://github.com/Shen-Lab/GraphCL)]

  ▷*Node representation learning, pretraining graphs*

- Sub-graph Contrast for Scalable Self-Supervised Graph Representation Learning

  Y. Jiao, Y. Xiong, J. Zhang, Y. Zhang, T. Zhang, and Y. Zhu

  ICDM 2020  [[PDF](http://arxiv.org/abs/2009.10273)]

  ▷*Sub-graph representation learning*

- Bipartite Graph Embedding via Mutual Information Maximization

  J. Cao, X. Lin, S. Guo, L. Liu, T. Liu, and B. Wang

  WSDM 2021  [[PDF](https://arxiv.org/abs/2012.05442v1), [Code](https://github.com/caojiangxia/BiGI)]

  ▷*Bipartite graph representation learning*

- Self-supervised Smoothing Graph Neural Networks

  L. Yu, S. Pei, C. Zhang, L. Ding, J. Zhou, L. Li, and X. Zhang

  arXiv 2020  [[PDF](https://arxiv.org/abs/2009.00934)]

  ▷*Node representation learning*

- Graph InfoClust: Leveraging Cluster-Level Node Information for Unsupervised Graph Representation Learning

  C. Mavromatis and G. Karypis

  arXiv 2020  [[PDF](https://arxiv.org/abs/2009.06946)]

  ▷*Node representation learning*

- Graph Contrastive Learning with Adaptive Augmentation

  Y. Zhu, Y. Xu, F. Yu, Q. Liu, S. Wu, and L. Wang

  arXiv 2020  [[PDF](http://arxiv.org/abs/2010.14945)]

  ▷*Node representation learning*

- Towards Domain-Agnostic Contrastive Learning

  V. Verma, M.-T. Luong, K. Kawaguchi, H. Pham, and Q. V. Le

  arXiv 2020  [[PDF](https://arxiv.org/abs/2011.04419)]

  ▷*Graph representation learning*

- Contrastive Learning with Hard Negative Samples

  J. Robinson, C.-Y. Chuang, S. Sra, and S. Jegelka

  arXiv 2020  [[PDF](http://arxiv.org/abs/2010.04592v1)]

  ▷*Graph representation learning*

- Motif-Driven Contrastive Learning of Graph Representations

  S. Zhang, Z. Hu, A. Subramonian, and Y. Sun

  arXiv 2020  [[PDF](http://arxiv.org/abs/2012.12533)]

  ▷*Pretraining graphs*

- Iterative Graph Self-Distillation

  H. Zhang, S. Lin, W. Liu, P. Zhou, J. Tang, X. Liang, and E. P. Xing

  arXiv 2020  [[PDF](http://arxiv.org/abs/2010.12609)]

  ▷*Graph representation learning*

### Applications

- Self-Supervised Hypergraph Convolutional Networks for Session-based Recommendation

  X. Xia, H. Yin, J. Yu, Q. Wang, L. Cui, and X. Zhang

  AAAI 2021 [[PDF](https://arxiv.org/abs/2012.06852), [Code](https://github.com/xiaxin1998/DHCN)]

  ▷*Session-based recommendation*

- Multi-view Graph Contrastive Representation Learning for Drug-Drug Interaction Prediction

  Y. Wang, Y. Min, X. Chen, and J. Wu

  arXiv 2020 [[PDF](https://arxiv.org/abs/2010.11711)]

  ▷*Drug-drug interaction prediction*

## Blog Posts

* Contrastive Self-Supervised Learning

  Ankesh Anand

  2020  [[URL](https://ankeshanand.com/blog/2020/01/26/contrative-self-supervised-learning.html)]

## Talks

* Unsupervised Learning with Graph Neural Networks

  Petar Veličković

  ACDL 2019 Satellite Workshop on Graph Neural Networks  [[URL](https://petar-v.com/talks/ACDL-UnsupGraph.pdf)]