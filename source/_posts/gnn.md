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

![image-20230413165416997](gnn.assets/image-20230413165416997.png)



How do we take advantage ofrelational structure for betterprediction?

为了更好的预测关系！



目前的machine learning 模型

![image-20230413161006250](D:\blog2023\hexo-beantech\source\img\image-20230413161006250.png)

目前的deeplearning 工具由简单的网格和序列构成

与神经网络相比：

1.节点位置任意，结构复杂

2.没有固定的节点顺序

3.动态，多模态

Graphs are the new frontierof deep learning

图的模型

![image-20230413161147088](D:\blog2023\hexo-beantech\source\img\image-20230413161147088.png)

![image-20230413161822510](D:\blog2023\hexo-beantech\source\img\image-20230413161822510.png)

# Different types of tasks:

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

![image-20230413162225783](C:\Users\22418\AppData\Roaming\Typora\typora-user-images\image-20230413162225783.png)

邻接矩阵

![image-20230413162327585](C:\Users\22418\AppData\Roaming\Typora\typora-user-images\image-20230413162327585.png)

计算

![image-20230413162354176](C:\Users\22418\AppData\Roaming\Typora\typora-user-images\image-20230413162354176.png)

权重图

![image-20230413162433343](C:\Users\22418\AppData\Roaming\Typora\typora-user-images\image-20230413162433343.png)

![image-20230413171458279](../img/image-20230413171458279.png)

![image-20230413174221985](gnn/image-20230413174221985.png)
