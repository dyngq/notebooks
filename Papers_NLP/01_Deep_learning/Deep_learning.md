# DeepLearning

## 第一节 背景、监督学习、反向传播

### pre预备

* 前期知识储备
!['dyngq_images'](images/dyngq_2019-09-14-15-52-12.png)
* 学习建议
!['dyngq_images'](images/dyngq_2019-09-14-16-06-27.png)
* 学习时间分配
!['dyngq_images'](images/dyngq_2019-09-14-16-08-45.png)

### 深度学习背景介绍

* 传统机器学习需要专业领域专家进行特征抽取的设计，深度学习则不同，深度学习通过从数据中学习到的特征层进行特征抽取。
* 背景
!['dyngq_images'](images/dyngq_2019-09-14-16-14-59.png)
* 背景
!['dyngq_images'](images/dyngq_2019-09-14-16-15-19.png)

### 深度学习基本结构

* 基本结构
!['dyngq_images'](images/dyngq_2019-09-14-16-31-14.png)

### 深度学习应用领域

* 应用领域
!['dyngq_images'](images/dyngq_2019-09-14-16-31-48.png)

### 监督学习

* 训练步骤：
!['dyngq_images'](images/dyngq_2019-09-14-16-36-04.png)
* 随机梯度下降_SGD
!['dyngq_images'](images/dyngq_2019-09-14-17-36-46.png)
* 总结
!['dyngq_images'](images/dyngq_2019-09-17-16-54-17.png)

### 反向传播（一种用于计算梯度的算法）

* 反向传播
!['dyngq_images'](images/dyngq_2019-09-17-17-00-43.png)

### 反向传播学习笔记

* Q3_反向传播公式推导；
* [CS231n课程笔记翻译：反向传播笔记](https://zhuanlan.zhihu.com/p/21407711)
* [神经网络反向传播的数学原理](https://zhuanlan.zhihu.com/p/22473137)
* [神经网络BP反向传播算法原理和详细推导流程](https://blog.csdn.net/qq_32865355/article/details/80260212)
* 反向传播，链式法则
* 权重参数减去 偏导数乘学习率 ，更新权重

1. Page one
!['dyngq_images'](images/dyngq_2019-09-21-11-34-41.png)
2. Page two
!['dyngq_images'](images/dyngq_2019-09-21-11-34-55.png)
3. Page three
!['dyngq_images'](images/dyngq_2019-09-21-11-35-09.png)

#### 激活函数

* 激活函数
!['dyngq_images'](images/dyngq_2019-09-23-16-11-19.png)

#### 反向传播总结

* 总结
!['dyngq_images'](images/dyngq_2019-09-23-16-12-53.png)

### 其他作业题

* 来自@目光所及 同学
!['dyngq_images'](images/dyngq_2019-09-23-16-15-31.png)

## 第二节 CNN、基于CNN的图像理解

* !['dyngq_images'](images/dyngq_2019-09-23-16-26-17.png)
* !['dyngq_images'](images/cnn.gif)

### 卷积神经网络基础

* 卷积神经网络基础
!['dyngq_images'](images/dyngq_2019-09-23-16-27-23.png)
!['dyngq_images'](images/dyngq_2019-09-23-16-29-04.png)
!['dyngq_images'](images/dyngq_2019-09-23-17-13-50.png)
* 面试题
!['dyngq_images'](images/dyngq_2019-09-23-17-15-41.png)

### 经典卷积神经网络

1. LeNet
2. AlexNet
!['dyngq_images'](images/dyngq_2019-09-23-17-17-05.png)
3. VGG(参数量庞大)
4. GoogLeNet(不同大小的卷积核)
!['dyngq_images'](images/dyngq_2019-09-23-17-18-31.png)
5. ResNet(残差，减少梯度消失问题)
6. DenseNet(说明不仅强调深度，同时强调宽度)
!['dyngq_images'](images/dyngq_2019-09-23-17-22-47.png)
!['dyngq_images'](images/dyngq_2019-09-23-17-24-06.png)
!['dyngq_images'](images/dyngq_2019-09-23-17-24-30.png)
!['dyngq_images'](images/dyngq_2019-09-23-17-25-11.png)

### 作业

1. 来自@张小李 同学
!['dyngq_images'](images/dyngq_2019-09-23-17-26-56.png)
2. @马健华
!['dyngq_images'](images/dyngq_2019-09-23-17-28-19.png)

## 第三节 分布式特征表示&语言处理、RNN、未来

### 上节回顾

* 回顾
!['dyngq_images'](images/dyngq_2019-09-26-13-58-22.png)

### 分布式特征表示 Distributed representations

* 就是 特征 的一种表示方法，参数化，感觉下图就好比ONE-HOT
* 增加稠密性
* 分布式特征表示能发现**数据之间的语义相似性**
!['dyngq_images'](images/dyngq_2019-09-26-20-29-41.png)
* 深度学习两个巨大优势
!['dyngq_images'](images/dyngq_2019-09-27-12-22-48.png)
* Embedding
!['dyngq_images'](images/dyngq_2019-09-28-17-33-25.png)
!['dyngq_images'](images/dyngq_2019-09-28-17-33-11.png)
* **Word2Vector**
!['dyngq_images'](images/dyngq_2019-09-28-17-32-14.png)
* N-grams
!['dyngq_images'](images/dyngq_2019-09-28-17-32-29.png)

### RNN Recurrent Neural Networks

* 左图是实际的循环，右图是展开
!['dyngq_images'](images/dyngq_2019-09-28-17-37-15.png)
!['dyngq_images'](images/dyngq_2019-09-28-17-37-53.png)
示例
!['dyngq_images'](images/dyngq_2019-09-28-17-39-21.png)
* LSTM
!['dyngq_images'](images/dyngq_2019-09-28-17-40-09.png)
* 双向RNN
!['dyngq_images'](images/dyngq_2019-09-28-17-43-06.png)

### 展望

1. 无监督学习
!['dyngq_images'](images/dyngq_2019-09-28-17-43-27.png)
!['dyngq_images'](images/dyngq_2019-09-28-17-44-44.png)
2. 强化学习
!['dyngq_images'](images/dyngq_2019-09-28-17-45-16.png)
!['dyngq_images'](images/dyngq_2019-09-28-17-45-52.png)

* 生成式对抗网络 GAN
!['dyngq_images'](images/dyngq_2019-09-28-17-47-30.png)

### 总结

> 努力理解深度学习的优势和局限性
