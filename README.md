# VFL-Survey

This Github repository summarizes a curated list of Vertical Federated Learning resources. For more details and the categorization criteria, please refer to our survey.

什么是纵向联邦学习？
联邦学习（Federated Learning, FL）是一个机器学习框架，能有效帮助多个机构在满足数据隐私保护的要求下，利用各自的数据使用机器学习进行联合建模。FL旨在实现利用传输中间结果来实现学习目标，从而保证机构的原始数据都存储在本地，不进行任何的交换和传输。纵向联邦学习根据参与训练的机构的数据具有不同的特征分布，通常分为横向联邦学习（Horizontal FL, HFL）和纵向联邦学习（Vertical FL, VFL）。其中VFL适用于机构具有相同样本空间但不同特征空间的场景。近年来VFL被广泛应用于医疗健康、风险评估和广告推荐等领域。


 1. 纵向联邦学习算法
 - 1.1  基本模型
 - 1.2 通信效率
 - 1.3 数据对齐
 - 1.4 标签分布
 
 2. 纵向联邦学习的安全和隐私风险
  - 2.1 标签推断攻击
  - 2.2 属性推断攻击
  - 2.3 成员推断攻击
  - 2.4 数据重构攻击
  - 2.5 基于GAN的推断攻击
  - 2.6 后门攻击
  
 3. 纵向联邦学习的防御
   - 3.1 基于加密的防御
   - 3.2 基于扰动的防御
   - 3.3 基于对抗的防御
   
# 纵向联邦学习算法


## 基本模型

Parallel Distributed Logistic Regression for Vertical Federated Learning without Third-Party Coordinator  [pdf](https://arxiv.org/abs/1911.09824)

Privacy Preserving Vertical Federated Learning for Tree-based Models  [pdf](http://www.vldb.org/pvldb/vol13/p2090-wu.pdf)

SecureBoost: A Lossless Federated Learning Framework  [pdf](https://arxiv.org/abs/1901.08755)

Split learning for health:  Distributed deep learning without sharing raw patient data  [pdf](https://arxiv.org/pdf/1812.00564.pdf)

Multi-Participant Multi-Class Vertical Federated Learning  [pdf](https://arxiv.org/abs/2001.11154)

Learning Privately over Distributed Features:  An ADMM Sharing Approach  [pdf](https://arxiv.org/abs/1907.07735)

A Vertical Federated Learning Framework for Graph Convolutional Network  [pdf](https://arxiv.org/abs/2106.11593)

Federated Doubly Stochastic Kernel Learning for Vertically Partitioned Data  [pdf](https://arxiv.org/abs/2008.06197)


## 通信效率

A Communication-Efficient Collaborative Learning Framework for Distributed Features  [pdf](https://arxiv.org/abs/1912.11187)

Private federated learning on vertically partitioned data via entity resolution and additively homomorphic encryption  [pdf](https://arxiv.org/abs/1711.10677)

A Quasi-Newton Method Based Vertical Federated Learning Framework for Logistic Regression  [pdf](https://arxiv.org/abs/1912.00513)

AsySQN: Faster Vertical Federated Learning Algorithms with Better Computation Resource Utilization  [pdf](https://dl.acm.org/doi/abs/10.1145/3447548.3467169)

Communication and Computation Reduction for  Split Learning using Asynchronous Training  [pdf](https://arxiv.org/abs/2107.09786)

Privacy-Preserving Asynchronous Federated Learning Algorithms for Multi-Party Vertically Collaborative Learning  [pdf](https://arxiv.org/abs/2008.06233)

Model Optimization Method Based on Vertical  Federated Learning  [pdf](https://ieeexplore.ieee.org/document/9401521/)

VAFL: a Method of Vertical Asynchronous Federated Learning  [pdf](https://arxiv.org/abs/2007.06081)

Cross-Silo Federated Learning for Multi-Tier Networks with Vertical and Horizontal Data Partitioning  [pdf](https://arxiv.org/abs/2108.08930)

Efficient Asynchronous Vertical Federated Learning via Gradient Prediction and Double-End Sparse Compression  [pdf](https://ieeexplore.ieee.org/document/9305383)

A Vertical Federated Learning Method for Interpretable Scorecard and Its Application in Credit Scoring  [pdf](https://arxiv.org/abs/2009.06218)

Accelerating Intra-Party Communication in Vertical FederatedLearning with RDMA  [pdf](https://dl.acm.org/doi/10.1145/3426745.3431333)

## 对齐方式

Exploiting Record Similarity for Practical Vertical Federated Learning  [pdf](https://arxiv.org/abs/2106.06312)

FedMVT: Semi-supervised Vertical Federated Learning with MultiView Training  [pdf](https://arxiv.org/abs/2008.10838)

## 标签分布

Secure Bilevel Asynchronous Vertical Federated Learning with Backward Updating  [enter link description here](https://arxiv.org/abs/2103.00958)

Multi-VFL: A Vertical Federated Learning System for Multiple Data and Label Owners  [pdf](https://arxiv.org/abs/2106.05468)

A Vertical Federated Learning Framework for Horizontally Partitioned Labels  [enter link description here](https://arxiv.org/abs/2106.10056)
