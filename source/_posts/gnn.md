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



How do we take advantage ofrelational structure for betterprediction?

为了更好的预测关系！

![image-20230414150932469](../img/gnn/image-20230414150932469.png)

目前的machine learning 模型

![image-20230414150959294](../img/gnn/image-20230414150959294.png)

目前的deeplearning 工具由简单的网格和序列构成

与神经网络相比：

1.节点位置任意，结构复杂

2.没有固定的节点顺序

3.动态，多模态

Graphs are the new frontierof deep learning

图的模型

![image-20230414151024004](../img/gnn/image-20230414151024004.png)

lifecycle

![image-20230414151046698](../img/gnn/image-20230414151046698.png)

# Different types of tasks:

![image-20230414151106800](../img/gnn/image-20230414151106800.png)

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

![image-20230414151133631](../img/gnn/image-20230414151133631.png)

矩阵计算

![image-20230414151156446](../img/gnn/image-20230414151156446.png)

权重图与非权重图

![image-20230414151217271](../img/gnn/image-20230414151217271.png)



introduction:why graph!接下去看李牧的gnn入门课

