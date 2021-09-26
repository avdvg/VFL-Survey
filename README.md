# 纵向联邦学习算法及其隐私安全性综述 


这个 Github 存储库总结了垂直联合学习资源的精选列表。 有关更多详细信息和分类标准，请参阅我们的综述论文。

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

Parallel Distributed Logistic Regression for Vertical Federated Learning without Third-Party Coordinator  [[pdf]](https://arxiv.org/abs/1911.09824)

Privacy Preserving Vertical Federated Learning for Tree-based Models  [[pdf]](http://www.vldb.org/pvldb/vol13/p2090-wu.pdf)

SecureBoost: A Lossless Federated Learning Framework  [[pdf]](https://arxiv.org/abs/1901.08755)

Split learning for health:  Distributed deep learning without sharing raw patient data  [[pdf]](https://arxiv.org/pdf/1812.00564.pdf)

Multi-Participant Multi-Class Vertical Federated Learning  [[pdf]](https://arxiv.org/abs/2001.11154)

Learning Privately over Distributed Features:  An ADMM Sharing Approach  [[pdf]](https://arxiv.org/abs/1907.07735)

A Vertical Federated Learning Framework for Graph Convolutional Network  [[pdf]](https://arxiv.org/abs/2106.11593)

Vertically Federated Graph Neural Network for privacy-preserving node classification  [[pdf]](https://arxiv.org/abs/2005.11903)

Federated Doubly Stochastic Kernel Learning for Vertically Partitioned Data  [[pdf]](https://arxiv.org/abs/2008.06197)


## 通信效率

A Communication-Efficient Collaborative Learning Framework for Distributed Features  [[pdf]](https://arxiv.org/abs/1912.11187)

Private federated learning on vertically partitioned data via entity resolution and additively homomorphic encryption  [[pdf]](https://arxiv.org/abs/1711.10677)

A Quasi-Newton Method Based Vertical Federated Learning Framework for Logistic Regression  [[pdf]](https://arxiv.org/abs/1912.00513)

AsySQN: Faster Vertical Federated Learning Algorithms with Better Computation Resource Utilization  [[pdf]](https://dl.acm.org/doi/abs/10.1145/3447548.3467169)

Communication and Computation Reduction for Split Learning using Asynchronous Training  [[pdf]](https://arxiv.org/abs/2107.09786)

Privacy-Preserving Asynchronous Federated Learning Algorithms for Multi-Party Vertically Collaborative Learning  [[pdf]](https://arxiv.org/abs/2008.06233)

Model Optimization Method Based on Vertical  Federated Learning  [[pdf]](https://ieeexplore.ieee.org/document/9401521/)

VAFL: a Method of Vertical Asynchronous Federated Learning  [[pdf]](https://arxiv.org/abs/2007.06081)

Cross-Silo Federated Learning for Multi-Tier Networks with Vertical and Horizontal Data Partitioning  [[pdf]](https://arxiv.org/abs/2108.08930)

Efficient Asynchronous Vertical Federated Learning via Gradient Prediction and Double-End Sparse Compression  [[pdf]](https://ieeexplore.ieee.org/document/9305383)

A Vertical Federated Learning Method for Interpretable Scorecard and Its Application in Credit Scoring  [[pdf]](https://arxiv.org/abs/2009.06218)

Accelerating Intra-Party Communication in Vertical FederatedLearning with RDMA  [[pdf]](https://dl.acm.org/doi/10.1145/3426745.3431333)

## 对齐方式

Exploiting Record Similarity for Practical Vertical Federated Learning  [[pdf]](https://arxiv.org/abs/2106.06312)

FedMVT: Semi-supervised Vertical Federated Learning with MultiView Training  [[pdf]](https://arxiv.org/abs/2008.10838)

Asymmetrical Vertical Federated Learning  [[pdf]](https://arxiv.org/abs/2004.07427)

## 标签分布

Secure Bilevel Asynchronous Vertical Federated Learning with Backward Updating  [[pdf]](https://arxiv.org/abs/2103.00958)

Multi-VFL: A Vertical Federated Learning System for Multiple Data and Label Owners  [[pdf]](https://arxiv.org/abs/2106.05468)

A Vertical Federated Learning Framework for Horizontally Partitioned Labels  [[pdf]](https://arxiv.org/abs/2106.10056)



# 纵向联邦学习的安全和隐私风险


## 标签推断攻击

Label Inference Attacks Against Vertical Federated Learning  [[pdf]](https://nesa.zju.edu.cn/download/fc_pdf_label_infer.pdf)

Label Leakage and Protection in Two-party Split Learning  [[pdf]](https://arxiv.org/abs/2102.08504)  [[code]](https://github.com/bytedance/fedlearner/tree/master/example/privacy/label_protection)


## 属性推断攻击

Feature Inference Attack on Model Predictions in Vertical Federated Learning  [[pdf]](https://arxiv.org/abs/2010.10152)  [[code]](https://github.com/xj231/featureinference-vfl)

Privacy-Preserving Federated Learning on Partitioned Attributes  [[pdf]](https://arxiv.org/abs/2104.14383)

Defending against Reconstruction Attack in Vertical Federated Learning  [[pdf]](https://arxiv.org/abs/2107.09898)

## 成员推断攻击
Vertical Federated Learning without Revealing Intersection Membership  [[pdf]](https://arxiv.org/abs/2106.05508)

Asymmetric Private Set Intersection with Applications to Contact Tracing and Private Vertical Federated Machine Learning  [[pdf]](https://arxiv.org/abs/2011.09350)  [[code]](https://github.com/OpenMined/PSI)

## 数据重构攻击

Unleashing the Tiger: Inference Attacks on Split Learning  [[pdf]](https://arxiv.org/abs/2012.02670)  [[code]](https://github.com/pasquini-dario/SplitNN_FSHA)

Understanding Deep Image Representations by Inverting Them  [[pdf]](https://arxiv.org/abs/1412.0035)  [[code]](https://github.com/novice03/timm-vis)

Inverting Gradients - How easy is it to break privacy in federated learning?  [[pdf]](https://arxiv.org/abs/2003.14053)  [[code]](https://github.com/JonasGeiping/invertinggradients)

See through Gradients: Image Batch Recovery via GradInversion  [[pdf]](https://arxiv.org/abs/2104.07586)

## 后门攻击

Backdoor attacks and defenses in feature-partitioned collaborative learning  [[pdf]](https://arxiv.org/abs/2007.03608)


# 纵向联邦学习的防御


## 基于加密的防御

A homomorphic-encryption-based vertical federated learning scheme for rick management  [[pdf]](http://www.doiserbia.nb.rs/Article.aspx?id=1820-02142000022O#.YU_uuqh7rIU)

Private federated learning on vertically partitioned data via entity resolution and additively homomorphic encryption  [[pdf]](https://arxiv.org/abs/1711.10677)

A Vertical Federated Learning Framework for Graph Convolutional Network  [[pdf]](https://arxiv.org/abs/2106.11593)

Vertically Federated Graph Neural Network for privacy-preserving node classification  [[pdf]](https://arxiv.org/abs/2005.11903)


## 基于扰动的防御
Label Leakage and Protection in Two-party Split Learning  [[pdf]](https://arxiv.org/abs/2102.08504)  [[code]](https://github.com/bytedance/fedlearner/tree/master/example/privacy/label_protection)

Hybrid Differentially Private Federated Learning on Vertically Partitioned Data  [[pdf]](https://arxiv.org/abs/2009.02763)


## 基于对抗训练的防御

Defending against Reconstruction Attack in Vertical Federated Learning  [[pdf]](https://arxiv.org/abs/2107.09898)

Privacy-Preserving Federated Learning on Partitioned Attributes  [[pdf]](https://arxiv.org/abs/2104.14383)


# 纵向联邦学习平台

## FATE
FATE由微众银行开发，其提供了在横向、纵向和联邦迁移学习模式下实施联邦学习的框架。它可以通过docker镜像或手动步骤实现。该框架提供了具有Kubernetes集成的生产准备API。应⽤场景和技术实现，包括⻋险定价、信贷⻛控、销量预测、广告投放、⾃动驾驶、辅助诊断、视觉安防等。  [[Web]](https://github.com/FederatedAI/FATE)
    
## PaddleFL

PaddleFL是基于百度PaddlePaddle开发的开源联邦学习框架。其支持横向联邦学习和纵向联邦学习。研究人员可以很轻松地用PaddleFL复制和比较不同的联邦学习算法，开发人员也比较容易在大规模分布式集群中部署PaddleFL联邦学习系统。PaddleFL提供很多种联邦学习策略（横向联邦学习、纵向联邦学习）及其在计算机视觉、自然语言处理、推荐算法等领域的应用。此外，PaddleFL还将提供传统机器学习训练策略的应用，例如多任务学习、联邦学习环境下的迁移学习。依靠着PaddlePaddle的大规模分布式训练和Kubernetes对训练任务的弹性调度能力，PaddleFL可以基于全栈开源软件轻松地部署。  [[Web]](https://github.com/PaddlePaddle/PaddleFL)
## Pysyft

Pysyft是由OpenMined社区开发的基于安全和隐私的深度学习开源库。它在主流深度学习框架（例如PyTorch和TensorFlow）中使用联邦学习，差分隐私和加密计算（例如多方计算（MPC）和同态加密（HE）），将隐私数据与模型训练分离。在PyVertical中使用私有集交集 (PSI) 的私有实体解析，使用分裂网络( SplitNN)在垂直分区数据上训练模型。神经网络 (NN) 的训练在两个或多个参与方中进行拆分。每个参与方都拥有原始模型层的一个子集，即本地模型。每个参与方训练他们的本地模型，获得中间嵌入层，并将中间嵌入层发送到协作方。这允许在训练过程中在计算能力方面提高分裂神经网络的效率，同时保证性能。  [[Web]](https://github.com/OpenMined/PySyft)
## TF Encrypted

TF-Encrypted(TFE)是用于安全多方计算 (MPC) 机器学习的开源框架。它建立在TensorFlow之上，利用了Keras API的易用性，同时通过安全的多方计算和同态加密对加密数据进行训练和预测。TF Encrypted的目的是让用户在并不精通密码学、分布式系统或高性能计算专业知识的情况下，也可以使用隐私保护加持的机器学习随时可用。用TF Encrypted的安全协议来安全汇总更新内容。当前实现使用了TF Encrypted和额外的密匙共享方法，需要三方（至更多方）实现安全地聚合计算。在安全计算中，其通过在图形模式下运行，并运用分发引擎按恰当顺序执行操作，实现同步功能。  [[Web]](https://github.com/tf-encrypted/tf-encrypted)
## CrypTen

CrypTen是一个基于PyTorch的隐私保护机器学习框架。它目前将Secure Multiparty Computation作为其安全计算后端来实现。该框架通过CrypTensor外观与感觉完全像PyTorch的对象来呈现协议Tensor。这使用户可以使用类似于PyTorch中的自动区分和神经网络模块。CrypTen基于库。就像PyTorch一样，它实现了张量库。这使从业人员更容易调试。CrypTen 目前在Linux 和Mac上使用 Python 3.7运行。不支持Windows。目前尚不支持在GPU 上进行计算。  [[Web]](https://github.com/facebookresearch/CrypTen)
## iBond

智邦iBond是由同盾科技创建的一个分布式机器学习平台。该平台融合了分布式机器学习，安全加密计算，元学习等技术打造知识联邦，使多方联邦在完全满足用户隐私、数据安全和政府合规的要求下，进行数据分析和建模，协同创造和共享知识。该平台支持在原始数据的密文空间上联邦、模型训练中联邦、特征学习结果上进行联邦，还支持多任务、多方异构知识联邦。  [[Web]](https://www.tongdun.cn/)
## PowerFL

PowerFL是由腾讯研发的金融级安全联合计算平台。其基于多数据源联合计算技术，提供稳定、高性能的联邦机器学习。构建在 Angel 机器学习平台上，利用 Angel-­PS 支持万亿级模型训练的能力，将很多在 Worker 上的计算提升到参数服务器端；Angel PowerFL 为联邦学习算法提供了计算、加密、存储、状态同步等基本操作接口，通过流程调度模块协调参与方任务执行状态，而通信模块完成了任务训练过程中所有数据的传输。Angel PowerFL 联邦学习已经在腾讯金融云、腾讯广告联合建模等业务中开始落地。  [[Web]](https://data.qq.com/powerfl/)
