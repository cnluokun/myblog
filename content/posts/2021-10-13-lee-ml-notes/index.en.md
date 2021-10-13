---
title: Lee-ML-notes
author: cnluokun
date: '2021-10-13'
slug: []
categories: []
tags: []
description: ~
featured_image: ~
---
# 李宏毅机器学习课程学习笔记01 - 机器学习介绍

人工智能、机器学习与深度学习的包含关系。人工智能是我们想要达成的目标，而机器学习是想要达成目标的手段，希望机器通过学习方式，他跟人一样聪明。而深度学习和机器学习有什么关系呢？深度学习就是机器学习的其中一种方法。

![](https://i.loli.net/2021/10/11/fQCxZGMEcLpDl5N.png)

##   01 机器学习: looking for a function

机器学习就是给出一堆大量数据（比如语音、图片数据等）通过编程让机器去学习这些数据里的信息，最后再有相似的数据给到机器时，它会基于学习到的数据信息输出结果。

**机器学习的目标应该说是在训练一个模型(Function Set)，一个能解决某一类问题的函数。** 例如将语音转化成文字的函数，这种函数的参数非常多，我们无法通过人工直接找出，所以我们给机器一个**函数集(Function Set)** ，要求机器自己寻找到那个函数。我们会提供数据以便于计算机找到函数。机器学习被视为人工智能研究的一部分，其算法是基于样本数据来构建模型的，所以说机器学习的过程就是在**利用样本数据提升模型相对某种任务的泛化性能[^1]。**

![](https://i.loli.net/2021/10/11/hEQVeIvw8mi5CLy.png)

因此机器学习可以比作是在**looking for a function**

* Model ：A set of function

  ![](https://i.loli.net/2021/10/11/G5BH6ACD3gMcOFw.png)

* 监督学习：告诉了机器input和output

  ![](https://i.loli.net/2021/10/11/CbyJmdkqt6viRL5.png)

* 机器学习三步走：define a set of functions $\rightarrow $ goodness of functions $\rightarrow $pick the bese function

  ![](https://i.loli.net/2021/10/11/B5DrEzm2oJvFOLc.png)

## 02 机器学习: Learning map and Scenarios



---





**Reference**

[^1]: [《机器学习》——李宏毅 学习笔记（一）| 阿一的博客](https://ayispace.github.io/2021/10/10/Introduction%20to%20Machine%20Learning/) 

[Hung-yi Lee (李宏毅) 个人主页](https://speech.ee.ntu.edu.tw/~hylee/index.html)

HUNG-YI LEE(李宏毅) | MACHINE LEARNING 2019 SPRING : [ML 2019 Spring (可以下载PPT课件)](https://speech.ee.ntu.edu.tw/~hylee/ml/2019-spring.html)

B站·Datawhale | 李宏毅《机器学习》2019 :  https://www.bilibili.com/video/BV1Ht411g7Ef

Datawhale出品 | [李宏毅机器学习笔记(LeeML-Notes)](https://datawhalechina.github.io/leeml-notes/#/?id=李宏毅机器学习笔记leeml-notes)

