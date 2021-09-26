# VFL-Survey

This Github repository summarizes a curated list of Vertical Federated Learning resources. For more details and the categorization criteria, please refer to our survey.

什么是纵向联邦学习？
联邦学习（Federated Learning, FL）是一个机器学习框架，能有效帮助多个机构在满足数据隐私保护的要求下，利用各自的数据使用机器学习进行联合建模。FL旨在实现利用传输中间结果来实现学习目标，从而保证机构的原始数据都存储在本地，不进行任何的交换和传输。纵向联邦学习根据参与训练的机构的数据具有不同的特征分布，通常分为横向联邦学习（Horizontal FL, HFL）和纵向联邦学习（Vertical FL, VFL）。其中VFL适用于机构具有相同样本空间但不同特征空间的场景。近年来VFL被广泛应用于医疗健康、风险评估和广告推荐等领域。


 1. 纵向联邦学习算法
 - 1.1  基本模型
 - 1.1.1 基于线性回归
 - 1.1.2 基于逻辑回归
 - 1.1.3 基于树模型
 - 1.1.4 基于神经网络
 
 - 1.2 通信效率
 - 1.2.1 基于异步更新
 - 1.2.2 基于拟牛顿法
 - 1.2.3 基于梯度压缩
 - 1.2.4 基于通信方式
 
 - 1.3 数据对齐
 - 1.3.1 基于隐私集合求交对齐
 - 1.3.2 基于相似度匹配
 - 1.3.3 基于半监督学习
 
 - 1.4 标签分布
 - 1.4.1 标签一方持有
 - 1.4.2 标签多方持有
 -
 3. 纵向联邦学习的攻击
 4. 纵向联邦学习的防御
