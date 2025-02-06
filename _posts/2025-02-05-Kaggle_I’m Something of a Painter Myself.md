---
layout:     post
title:      Kaggle 入门篇：I’m Something of a Painter Myself
subtitle:    "\"CycleGAN 循环生成对抗网络 \""
date:       2025-02-05
author:     星期五
header-img: img/kaggle.jpeg
catalog: true
tags:
    - Kaggle
    - 机器学习
    - GAN
---

> Use GANs to create art - will you be the next Monet?

## 前言

这是kaggle 官方为刚刚接触这项比赛的选手提供的一个非常有意思的项目，要求利用生成对抗网络（GAN）实现将照片转化为莫奈风格的艺术图片，这个项目有意思的地方在于需要选手在没有照片和艺术风格图片一一成对的训练数据的前提下，学习这两个不同域（即照片和艺术作品）之间的映射，比赛链接：[kaggle: I’m Something of a Painter Myself](https://www.kaggle.com/competitions/gan-getting-started/data)。

![](https://github.com/fangyuanleo/fangyuanleo.github.io/blob/master/post_fig/kaggle/monet/compare.png?raw=true)

（图片来源：知乎 calvin）

本篇博文作为Kaggle的入门篇，将会介绍一套完成的Kaggle项目数据集下载、分析、算法代码实现和上传流程。这篇博文的内容参考了以下大佬的工作，向他们分享表达诚挚的谢意：

- [bilibili 同济子豪兄：“CycleGAN照片转梵高莫奈油画“](https://www.bilibili.com/video/BV1wv4y1T71F/?vd_source=93c96df915e6ddad65b78774bf3baf9f)

- [CSDN 仙尊方媛：kaggle社区比赛I’m Something of a Painter Myself](https://blog.csdn.net/m0_73542617/article/details/140230469)

---

## Kaggle比赛流程简介：

---

<!-- Gitalk 评论 start --> <!-- Gitalk end -->

<!-- Gitalk 评论 start -->

<!-- Gitalk end -->
