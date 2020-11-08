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
  * [Generative/Predictive Methods](#generativepredictive-methods)
  * [Contrastive Methods](#contrastive-methods)
* [Blog Posts](#blog-posts)
* [Talks](#talks)

## Papers

### Survey

* X. Liu, F. Zhang, Z. Hou, Z. Wang, L. Mian, J. Zhang, and J. Tang, Self-supervised Learning: Generative or Contrastive, 2020. [[PDF](https://arxiv.org/abs/2006.08218)]

### Generative/Predictive Methods

* K. Sun, Z. Lin, and Z. Zhu, Multi-Stage Self-Supervised Learning for Graph Convolutional Networks on Graphs with Few Labeled Nodes, in AAAI, 2020. [[PDF](https://aaai.org/ojs/index.php/AAAI/article/view/6048/5904), [Code](https://github.com/datake/M3S)]
* W. Hu, B. Liu, J. Gomes, M. Zitnik, P. Liang, V. Pande, and J. Leskovec, Strategies for Pre-training Graph Neural Networks, in ICLR, 2020. [[PDF](https://openreview.net/forum?id=HJlWWJSFDH), [Code](https://github.com/snap-stanford/pretrain-gnns/)]
* Y. You, T. Chen, Z. Wang, and Y. Shen, When Does Self-Supervision Help Graph Convolutional Networks?, in ICML, 2020. [[PDF](http://arxiv.org/abs/2006.09136), [Code](https://github.com/Shen-Lab/SS-GCNs)]
* Z. Hu, Y. Dong, K. Wang, K.-W. Chang, and Y. Sun, GPT-GNN: Generative Pre-Training of Graph Neural Networks, in KDD, 2020. [[PDF](https://dl.acm.org/doi/10.1145/3394486.3403237), [Code](https://github.com/acbull/GPT-GNN)]
* Y. Zhu, Y. Xu, F. Yu, S. Wu, and L. Wang, CAGNN: Cluster-Aware Graph Neural Networks for Unsupervised Graph Representation Learning, 2020. [[PDF](https://arxiv.org/abs/2009.01674)]
* W. Jin, T. Derr, H. Liu, Y. Wang, S. Wang, Z. Liu, and J. Tang, Self-supervised Learning on Graphs: Deep Insights and New Direction, 2020. [[PDF](https://arxiv.org/abs/2006.10141), [Code](https://github.com/ChandlerBang/SelfTask-GNN)]

### Contrastive Methods

- P. Veličković, W. Fedus, W. L. Hamilton, P. Liò, Y. Bengio, and R. D. Hjelm, Deep Graph Infomax, in ICLR, 2019. [[PDF](https://openreview.net/forum?id=rklz9iAcKQ), [Code](https://github.com/PetarV-/DGI)]
- F. L. Opolka, A. Solomon, C. Cangea, P. Veličković, P. Liò, and R. D. Hjelm, Spatio-Temporal Deep Graph Infomax, in ICLR-W (RLGM), 2019. [[PDF](https://arxiv.org/abs/1904.06316)]
- Z. Peng, W. Huang, M. Luo, Q. Zheng, Y. Rong, T. Xu, and J. Huang, Graph Representation Learning via Graphical Mutual Information Maximization, in WWW, 2020. [[PDF](https://dl.acm.org/doi/10.1145/3366423.3380112), [Code](https://github.com/zpeng27/GMI)]
- T. N. Kipf, E. van der Pol, and M. Welling, Contrastive Learning of Structured World Models, in ICLR, 2020. [[PDF](https://openreview.net/forum?id=H1gax6VtDB), [Code](https://github.com/tkipf/c-swm)]
- K. Hassani and A. H. Khasahmadi, Contrastive Multi-View Representation Learning on Graphs, in ICML, 2020. [[PDF](https://arxiv.org/abs/2006.05582), [Code](https://github.com/kavehhassani/mvgrl)]
- Y. Zhu, Y. Xu, F. Yu, Q. Liu, S. Wu, and L. Wang, Deep Graph Contrastive Representation Learning, in ICML-W (GRL+), 2020. [[PDF](https://arxiv.org/abs/2006.04131), [Code](https://github.com/CRIPAC-DIG/GRACE/)]
- J. Qiu, Q. Chen, Y. Dong, J. Zhang, H. Yang, M. Ding, K. Wang, and J. Tang, GCC: Graph Contrastive Coding for Graph Neural Network Pre-Training, in KDD, 2020. [[PDF](https://dl.acm.org/doi/10.1145/3394486.3403168), [Code](https://github.com/THUDM/GCC)]
- Y. You, T. Chen, Y. Sui, T. Chen, Z. Wang, and Y. Shen, Pre-Training Graph Neural Networks: A Contrastive Learning Framework with Augmentations, in NeurIPS, 2020. [[PDF](http://arxiv.org/abs/2010.13902)]
- Y. Jiao, Y. Xiong, J. Zhang, Y. Zhang, T. Zhang, and Y. Zhu, Sub-graph Contrast for Scalable Self-Supervised Graph Representation Learning, in ICDM 2020. [[PDF](http://arxiv.org/abs/2009.10273)]
- L. Yu, S. Pei, C. Zhang, L. Ding, J. Zhou, L. Li, and X. Zhang, Self-supervised Smoothing Graph Neural Networks, 2020. [[PDF](https://arxiv.org/abs/2009.00934)]
- C. Mavromatis and G. Karypis, Graph InfoClust: Leveraging Cluster-Level Node Information for Unsupervised Graph Representation Learning, 2020. [[PDF](https://arxiv.org/abs/2009.06946)]
- Y. Zhu, Y. Xu, F. Yu, Q. Liu, S. Wu, and L. Wang, Graph Contrastive Learning with Adaptive Augmentation, 2020. [[PDF](http://arxiv.org/abs/2010.14945)]
- Y. Wang, Y. Min, X. Chen, and J. Wu, Multi-view Graph Contrastive Representation Learning for Drug-Drug Interaction Prediction, 2020. [[PDF](https://arxiv.org/abs/2010.11711)]

## Blog Posts

* Ankesh Anand, Contrastive Self-Supervised Learning, 2020. [[URL](https://ankeshanand.com/blog/2020/01/26/contrative-self-supervised-learning.html)]

## Talks

