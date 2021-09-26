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
  * [Surveys](#surveys)
  * [Generative/Predictive Methods](#generativepredictive-methods)
  * [Contrastive Methods](#contrastive-methods)
* [Blog Posts](#blog-posts)
* [Talks](#talks)

## Papers

### Surveys

* Self-supervised Learning: Generative or Contrastive, arXiv 2020  [[PDF](https://arxiv.org/abs/2006.08218)]
* Self-Supervised Learning of Graph Neural Networks: A Unified Review, arXiv 2021  [[PDF](https://arxiv.org/abs/2102.10757)]
* Graph Self-Supervised Learning: A Survey, arXiv 2021  [[PDF](https://arxiv.org/abs/2103.00111)]
* Self-supervised on Graphs: Contrastive, Generative, or Predictive, arXiv 2021  [[PDF](https://arxiv.org/abs/2105.07342)]

### Generative/Predictive Methods

#### Year 2020
* Multi-Stage Self-Supervised Learning for Graph Convolutional Networks on Graphs with Few Labeled Nodes, AAAI 2020  [[PDF](https://aaai.org/ojs/index.php/AAAI/article/view/6048/5904), [Code](https://github.com/datake/M3S)]

  ▷*Node representation learning*
* Strategies for Pre-training Graph Neural Networks, ICLR 2020  [[PDF](https://openreview.net/forum?id=HJlWWJSFDH), [Code](https://github.com/snap-stanford/pretrain-gnns/)]

  ▷*Pretraining graphs*
* When Does Self-Supervision Help Graph Convolutional Networks?, ICML 2020  [[PDF](https://arxiv.org/abs/2006.09136), [Code](https://github.com/Shen-Lab/SS-GCNs)]

  ▷*Node representation learning*
* GPT-GNN: Generative Pre-Training of Graph Neural Networks, KDD 2020  [[PDF](https://dl.acm.org/doi/10.1145/3394486.3403237), [Code](https://github.com/acbull/GPT-GNN)]

  ▷*Pretraining graphs*
* Self-supervised Auxiliary Learning with Meta-paths for Heterogeneous Graphs, NeurIPS 2020 [[PDF](https://proceedings.neurips.cc/paper/2020/hash/74de5f915765ea59816e770a8e686f38-Abstract.html)]
  
  ▷*Heterogeneous graphs*
* CAGNN: Cluster-Aware Graph Neural Networks for Unsupervised Graph Representation Learning, arXiv 2020  [[PDF](https://arxiv.org/abs/2009.01674)]

  ▷*Node representation learning*
* Self-supervised Learning on Graphs: Deep Insights and New Direction, arXiv 2020  [[PDF](https://arxiv.org/abs/2006.10141), [Code](https://github.com/ChandlerBang/SelfTask-GNN)]

  ▷*Node representation learning*
* Self-Supervised Graph Representation Learning via Global Context Prediction, arXiv 2020  [[PDF](https://arxiv.org/abs/2003.01604)]
  
  ▷*Node representation learning*

### Contrastive Methods
#### Year 2021
* Bipartite Graph Embedding via Mutual Information Maximization, WSDM 2021  [[PDF](https://arxiv.org/abs/2012.05442), [Code](https://github.com/caojiangxia/BiGI)]

  ▷*Bipartite graph representation learning*
* Contrastive Self-supervised Learning for Graph Classification, AAAI 2021  [[PDF](https://arxiv.org/abs/2009.05923)]

  ▷*Graph representation learning*
* Contrastive and Generative Graph Convolutional Networks for Graph-Based Semi-Supervised Learning, AAAI 2021  [[PDF](https://arxiv.org/abs/2009.07111)]

  ▷*Semi-supervised node representation learning*
* Graph Contrastive Learning with Adaptive Augmentation, WWW 2021  [[PDF](https://arxiv.org/abs/2010.14945), [Code](https://github.com/CRIPAC-DIG/GCA)]

  ▷*Node representation learning*
* SUGAR: Subgraph Neural Network with Reinforcement Pooling and Self-Supervised Mutual Information Mechanism, WWW 2021 [[PDF](https://arxiv.org/abs/2101.08170)]
  
  ▷*Graph representation learning*
* HDMI: High-order Deep Multiplex Infomax, WWW 2021 [[PDF](https://arxiv.org/abs/2102.07810)]
  
  ▷*Multiplex graph representation learning*
* Self-Supervised Graph Neural Networks Without Explicit Negative Sampling, SSL@WWW 2021  [[PDF](https://arxiv.org/abs/2103.14958)]

  ▷*Node representation learning*
* Motif-Driven Contrastive Learning of Graph Representations, SSL@WWW 2021  [[PDF](https://arxiv.org/abs/2012.12533)]

  ▷*Pretraining graphs*
* Iterative Graph Self-Distillation, SSL@WWW 2021  [[PDF](https://arxiv.org/abs/2010.12609)]

  ▷*Graph representation learning*
* Towards Robust Graph Contrastive Learning, SSL@WWW 2021  [[PDF](https://arxiv.org/abs/2102.13085)]

  ▷*Node representation learning*
* Contrastive Learning with Hard Negative Samples, ICLR 2021  [[PDF](https://arxiv.org/abs/2010.04592)]

  ▷*Graph representation learning*
* Multi-Scale Contrastive Siamese Networks for Self-Supervised Graph Representation Learning, IJCAI 2021  [[PDF](https://arxiv.org/abs/2105.05682)]
  
  ▷*Node representation learning*
* Graph InfoClust: Maximizing Coarse-Grain Mutual Information in Graphs, PAKDD 2021  [[PDF](https://link.springer.com/chapter/10.1007%2F978-3-030-75762-5_43)]
  
  ▷*Node representation learning*
* Self-supervised Graph-level Representation Learning with Local and Global Structure, CML 2021  [[PDF](https://arxiv.org/abs/2106.04113)]
  
  ▷*Pretraining graphs*
* Graph Contrastive Learning Automated, ICML 2021  [[PDF](https://arxiv.org/abs/2106.07594), [Code](https://github.com/Shen-Lab/GraphCL_Automated)]
  
  ▷*Graph representation learning*
* Multi-View Self-Supervised Heterogeneous Graph Embedding, ECML PKDD 2021  [[PDF](https://2021.ecmlpkdd.org/wp-content/uploads/2021/07/sub_408.pdf)]
  
  ▷*Heterogeneous graph representation learning*
* GCCAD: Graph Contrastive Coding for Anomaly Detection, arXiv 2021 [[PDF](https://arxiv.org/abs/2108.07516v1)]
  
  ▷*Anomaly detection*
* Bootstrapped Representation Learning on Graphs, arXiv 2021  [[PDF](https://arxiv.org/abs/2102.06514)]

  ▷*Node representation learning*
* Improving Graph Representation Learning by Contrastive Regularization, arXiv 2021  [[PDF](https://arxiv.org/abs/2101.11525)]
  
  ▷*Graph/node representation learning*
* Adversarial Graph Augmentation to Improve Graph Contrastive Learning, arXiv 2021  [[PDF](https://arxiv.org/abs/2106.05819)]
  
  ▷*Graph representation learning*
* Automated Self-Supervised Learning for Graphs, arXiv 2021  [[PDF](https://arxiv.org/abs/2106.05470)]
  
  ▷*Node representation learning*
* Self-Supervised Graph Learning with Proximity-based Views and Channel Contrast, arXiv 2021  [[PDF](https://arxiv.org/abs/2106.03723)]
  
  ▷*Node representation learning*
* Fairness-Aware Node Representation Learning, arXiv 2021  [[PDF](https://arxiv.org/abs/2106.05391)]
  
  ▷*Node representation learning*
* Group Contrastive Self-Supervised Learning on Graphs, arXiv 2021  [[PDF](https://arxiv.org/abs/2107.09787)]
  
  ▷*Graph/node representation learning*
* AutoGCL: Automated Graph Contrastive Learning via Learnable View Generators, arXiv  [[PDF](https://arxiv.org/abs/2109.10259)]
  
  ▷*Graph representation learning*
  
#### Year 2020

* Unsupervised Attributed Multiplex Network Embedding, AAAI 2020  [[PDF](https://aaai.org/ojs/index.php/AAAI/article/view/5985)]

  ▷*Multiplex graph representation learning*
* Graph Representation Learning via Graphical Mutual Information Maximization, WWW 2020  [[PDF](https://dl.acm.org/doi/10.1145/3366423.3380112), [Code](https://github.com/zpeng27/GMI)]

  ▷*Node representation learning*
* Contrastive Learning of Structured World Models, ICLR 2020  [[PDF](https://openreview.net/forum?id=H1gax6VtDB), [Code](https://github.com/tkipf/c-swm)]

  ▷*Relational inference*
* Contrastive Multi-View Representation Learning on Graphs, ICML 2020  [[PDF](https://arxiv.org/abs/2006.05582), [Code](https://github.com/kavehhassani/mvgrl)]

  ▷*Node/graph representation learning*
* Deep Graph Contrastive Representation Learning, GRL+@ICML 2020  [[PDF](https://arxiv.org/abs/2006.04131), [Code](https://github.com/CRIPAC-DIG/GRACE/)]

  ▷*Node representation learning*
* GCC: Graph Contrastive Coding for Graph Neural Network Pre-Training, KDD 2020  [[PDF](https://dl.acm.org/doi/10.1145/3394486.3403168), [Code](https://github.com/THUDM/GCC)]

  ▷*Pretraining graphs*
* Graph Contrastive Learning with Augmentations, NeurIPS 2020  [[PDF](https://arxiv.org/abs/2010.13902), [Code](https://github.com/Shen-Lab/GraphCL)]

  ▷*Node representation learning, pretraining graphs*
* Sub-graph Contrast for Scalable Self-Supervised Graph Representation Learning, ICDM 2020  [[PDF](https://arxiv.org/abs/2009.10273)]

  ▷*Sub-graph representation learning*
* Self-supervised Smoothing Graph Neural Networks,  arXiv 2020  [[PDF](https://arxiv.org/abs/2009.00934)]

  ▷*Node representation learning*
* Towards Domain-Agnostic Contrastive Learning, arXiv 2020  [[PDF](https://arxiv.org/abs/2011.04419)]

  ▷*Graph representation learning*

#### Year 2019
* Deep Graph Infomax, ICLR 2019  [[PDF](https://openreview.net/forum?id=rklz9iAcKQ), [Code](https://github.com/PetarV-/DGI)]

  ▷*Node representation learning*
* Spatio-Temporal Deep Graph Infomax, RLGM@ICLR 2019  [[PDF](https://arxiv.org/abs/1904.06316)]

  ▷*Node representation learning*

### Applications

* Self-Supervised Hypergraph Convolutional Networks for Session-based Recommendation, AAAI 2021 [[PDF](https://arxiv.org/abs/2012.06852), [Code](https://github.com/xiaxin1998/DHCN)]

  ▷*Session-based recommendation*
* Multi-view Graph Contrastive Representation Learning for Drug-Drug Interaction Prediction, WWW 2021 [[PDF](https://arxiv.org/abs/2010.11711)]

  ▷*Drug-drug interaction prediction*
* Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation, WWW 2021  [[PDF](https://arxiv.org/abs/2101.06448)]
  
  ▷*Social recommendation*
* Self-supervised Graph Learning for Recommendation, SIGIR 2021  [[PDF](https://arxiv.org/abs/2010.10783)]

  ▷*Collaborative filtering*
  
* CCGL: Contrastive Cascade Graph Learning, arXiv 2021 [[PDF](https://arxiv.org/abs/2107.12576)]

  ▷*Information cascade prediction*


## Blog Posts

* Contrastive Self-Supervised Learning,  [[URL](https://ankeshanand.com/blog/2020/01/26/contrative-self-supervised-learning.html)]
* Graph Contrastive Learning,  [[URL](https://sxkdz.github.io/research/GraphCL/)]

## Talks

* Unsupervised Learning with Graph Neural Networks, ACDL 2019 Satellite Workshop on Graph Neural Networks  [[URL](https://petar-v.com/talks/ACDL-UnsupGraph.pdf)]
