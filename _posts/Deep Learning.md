---
layout:     post
title:      iOS手势与变形
subtitle:   手势与变形基础知识笔记
date:       2016-10-10
author:     BY
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - iOS
    - iOS开发基础
---

>手势在用户交互中有着举足轻重的作用，这篇文字简单的介绍了iOS中的手势，并通过手势对控件进行变形处理。

# QA-GNN: Reasoning with Language Models and Knowledge Graphs for Question Answering

## 动机



## 方法

流程：

1、建图：给定问题、答案、上下文实体，将他们拼接为图。

首先，提取问题与答案节点，在KG中进行子图提取，然后提取一个代表QA上下文的节点Z。

2、上下文图节点特征：利用LM进行文本嵌入。

3、节点相关性评分

使用预训练语言模型将实体节点与上下文实体节点计算相似性评分

4、
