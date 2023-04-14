---
title: 初识GNN
catalog: true
date: 2023-04-12 13:01:28
subtitle: 斯坦福Machine Learning with Graphs
header-img: samuel-bourke-sc-B_2-Om7Q-unsplash.jpg
tags:
    - gnn
    - machine learning

---

# Machine learning with Graphs

#### 

图的种类

![image-20230414121900420](gnn/image-20230414121900420.png)



How do we take advantage ofrelational structure for betterprediction?

为了更好的预测关系！



目前的machine learning 模型

![image-20230414121959036](gnn/image-20230414121959036.png)

目前的deeplearning 工具由简单的网格和序列构成

与神经网络相比：

1.节点位置任意，结构复杂

2.没有固定的节点顺序

3.动态，多模态

Graphs are the new frontierof deep learning

图的模型

![image-20230414122026839](gnn/image-20230414122026839.png)

lifecycle

![image-20230414122048241](gnn/image-20230414122048241.png)

# Different types of tasks:

![image-20230414122139286](gnn/image-20230414122139286.png)

graph ml task

1.Node classification 比如上网用户分类

2.Link prediction 比如知识图谱

3.Graph classification 比如分子性质预测

4.Clustering 比如社会关系

5.Other tasks：

Graph generation：药物

Graph evolution：物理模拟

# Choice of a graph representation：

有向图和无向图：



邻接矩阵

![image-20230414122244515](gnn/image-20230414122244515.png)

矩阵计算

![image-20230414122316766](gnn/image-20230414122316766.png)

权重图与非权重图

![image-20230414122340519](gnn/image-20230414122340519.png)



introduction:why graph!

