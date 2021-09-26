# 纵向联邦学习调研综述

这个 Github 存储库总结了垂直联合学习资源的精选列表。 有关更多详细信息和分类标准，请参阅我们的调查。

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
  - 2.5 后门攻击
  
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

Vertically Federated Graph Neural Network for privacy-preserving node classification  [pdf](https://arxiv.org/abs/2005.11903)

Federated Doubly Stochastic Kernel Learning for Vertically Partitioned Data  [pdf](https://arxiv.org/abs/2008.06197)


## 通信效率

A Communication-Efficient Collaborative Learning Framework for Distributed Features  [pdf](https://arxiv.org/abs/1912.11187)

Private federated learning on vertically partitioned data via entity resolution and additively homomorphic encryption  [pdf](https://arxiv.org/abs/1711.10677)

A Quasi-Newton Method Based Vertical Federated Learning Framework for Logistic Regression  [pdf](https://arxiv.org/abs/1912.00513)

AsySQN: Faster Vertical Federated Learning Algorithms with Better Computation Resource Utilization  [pdf](https://dl.acm.org/doi/abs/10.1145/3447548.3467169)

Communication and Computation Reduction for Split Learning using Asynchronous Training  [pdf](https://arxiv.org/abs/2107.09786)

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

Asymmetrical Vertical Federated Learning  [pdf](https://arxiv.org/abs/2004.07427)

## 标签分布

Secure Bilevel Asynchronous Vertical Federated Learning with Backward Updating  [pdf](https://arxiv.org/abs/2103.00958)

Multi-VFL: A Vertical Federated Learning System for Multiple Data and Label Owners  [pdf](https://arxiv.org/abs/2106.05468)

A Vertical Federated Learning Framework for Horizontally Partitioned Labels  [pdf](https://arxiv.org/abs/2106.10056)



# 纵向联邦学习的安全和隐私风险


## 标签推断攻击

Label Inference Attacks Against Vertical Federated Learning  [pdf](https://nesa.zju.edu.cn/download/fc_pdf_label_infer.pdf)

Label Leakage and Protection in Two-party Split Learning  [pdf]  (https://arxiv.org/abs/2102.08504)  [code](https://github.com/bytedance/fedlearner/tree/master/example/privacy/label_protection)


## 属性推断攻击

Feature Inference Attack on Model Predictions in Vertical Federated Learning  [pdf](https://arxiv.org/abs/2010.10152)  [code](https://github.com/xj231/featureinference-vfl)

Privacy-Preserving Federated Learning on Partitioned Attributes  [pdf](https://arxiv.org/abs/2104.14383)

Defending against Reconstruction Attack in Vertical Federated Learning  [pdf](https://arxiv.org/abs/2107.09898)

## 成员推断攻击
Vertical Federated Learning without Revealing Intersection Membership  [pdf](https://arxiv.org/abs/2106.05508)

Asymmetric Private Set Intersection with Applications to Contact Tracing and Private Vertical Federated Machine Learning  [pdf](https://arxiv.org/abs/2011.09350)  [code](https://github.com/OpenMined/PSI)

## 数据重构攻击

Unleashing the Tiger: Inference Attacks on Split Learning  [pdf](https://arxiv.org/abs/2012.02670)  [code](https://github.com/pasquini-dario/SplitNN_FSHA)

Understanding Deep Image Representations by Inverting Them  [pdf](https://arxiv.org/abs/1412.0035)  [code](https://github.com/novice03/timm-vis)

Inverting Gradients - How easy is it to break privacy in federated learning?  [pdf](https://arxiv.org/abs/2003.14053)  [code](https://github.com/JonasGeiping/invertinggradients)

See through Gradients: Image Batch Recovery via GradInversion  [pdf](https://arxiv.org/abs/2104.07586)

## 后门攻击

Backdoor attacks and defenses in feature-partitioned collaborative learning  [pdf](https://arxiv.org/abs/2007.03608)


# 纵向联邦学习的防御


## 基于加密的防御

A homomorphic-encryption-based vertical federated learning scheme for rick management  [pdf](http://www.doiserbia.nb.rs/Article.aspx?id=1820-02142000022O#.YU_uuqh7rIU)

Private federated learning on vertically partitioned data via entity resolution and additively homomorphic encryption  [pdf](https://arxiv.org/abs/1711.10677)

A Vertical Federated Learning Framework for Graph Convolutional Network  [pdf](https://arxiv.org/abs/2106.11593)

Vertically Federated Graph Neural Network for privacy-preserving node classification  [pdf](https://arxiv.org/abs/2005.11903)


## 基于扰动的防御
Label Leakage and Protection in Two-party Split Learning  [pdf]  (https://arxiv.org/abs/2102.08504)  [code](https://github.com/bytedance/fedlearner/tree/master/example/privacy/label_protection)

Hybrid Differentially Private Federated Learning on Vertically Partitioned Data  [pdf](https://arxiv.org/abs/2009.02763)


## 基于对抗训练的防御

Defending against Reconstruction Attack in Vertical Federated Learning  [pdf](https://arxiv.org/abs/2107.09898)

Privacy-Preserving Federated Learning on Partitioned Attributes  [pdf](https://arxiv.org/abs/2104.14383)
