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

这是Kaggle 官方为刚刚接触这项比赛的选手提供的一个非常有意思的项目，利用生成对抗网络（GAN）实现

![示例图片](https://example.com/image.jpg "这是一个示例图片")

图片来源：知乎 calvin



本篇博文作为Kaggle的入门篇，将会介绍一套完成的Kaggle项目数据集下载、分析、算法代码实现和上传流程。这篇博文的内容参考了以下大佬的工作，向他们分享表达诚挚的谢意：

[bilibili 同济子豪兄：“CycleGAN照片转梵高莫奈油画“](https://www.bilibili.com/video/BV1wv4y1T71F/?vd_source=93c96df915e6ddad65b78774bf3baf9f)

## 正文

接下来说说搭建这个博客的技术细节。  

正好之前就有关注过 [GitHub Pages](https://pages.github.com/) + [Jekyll](http://jekyllrb.com/) 快速 Building Blog 的技术方案，非常轻松时尚。

其优点非常明显：

* **Markdown** 带来的优雅写作体验
* 非常熟悉的 Git workflow ，**Git Commit 即 Blog Post**
* 利用 GitHub Pages 的域名和免费无限空间，不用自己折腾主机
  * 如果需要自定义域名，也只需要简单改改 DNS 加个 CNAME 就好了 
* Jekyll 的自定制非常容易，基本就是个模版引擎

---

主题我直接 Downlosd 了 [Hux的博客主题](https://huangxuan.me/) 的进行修改，简单粗暴，不过遇到了很多坑😂，好在都填完了。。。

本地调试环境需要 `gem install jekyll`，结果 rubygem 的源居然被墙了，~~后来手动改成了我大淘宝的镜像源才成功~~，淘宝的源已经[停止维护](https://gems.ruby-china.org/)，换成了OSChina的源 `https://gems.ruby-china.org/`。
