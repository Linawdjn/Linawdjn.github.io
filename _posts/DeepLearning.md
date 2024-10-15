---
layout:     post
title:      《Nature》深度学习
subtitle:   函数式编程框架 ReactiveCocoa 进阶
date:       2024-10-15
author:     linyawei
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - iOS
    - ReactiveCocoa
    - 函数式编程
    - 开源框架
---
# QA-GNN: Reasoning with Language Models and Knowledge Graphs for Question Answering

## 动机



## 方法

流程：

1、建图：给定问题、答案、上下文实体，将他们拼接为图。

首先，提取问题与答案节点，在KG中进行子图提取，然后提取一个代表QA上下文的节点Z。

2、上下文图节点特征：利用LM进行文本嵌入。

3、节点相关性评分

使用预训练语言模型将实体节点与上下文实体节点计算相似性评分
