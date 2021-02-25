---
layout: article
title: 折腾开始
author :
mathjax: true
mermaid: true
chart: true
mathjax_autoNumber: true
toc: true
tags : 网络 IPv6 路由器 openwrt
key: ipv6
mode: immersive
header:
  theme: dark
article_header:
  type: overlay
  theme: dark
  background_color: '#ffffff'
  background_image:
    gradient: 'linear-gradient(0deg, rgba(0, 0, 0 , .3), rgba(0, 0, 0, .3))'
    src: assets/background/morning.jpg
---

会在接下来继续家庭网络端的一些折腾经历
<!--more-->

# 前言

今年家里添置了一些网络相关器材，如搞了一套POE供电监控，因为我涉及交换机网段以及在不在家查看监控，又重新开始了很久以前就停止的路由器折腾，预计会在接下来记录一下相关的操作记录。
> 在开始折腾前，其实已经有一些前期的实验性操作了，目前我的主要要求还是失败，深刻认识到自己在网络路由上的知识浅薄，也因为这样，计划实现的目标有很大机会到最后也没有实现的同时也得不到什么有意义的解决，到时就算是个备忘，起码知道这样是不行的。

## 预定目标
>###1. ISP分发DHCP-PD前缀是::/64，二级路由IPv6中继研究
###2. 802.11r/k以及爱快AC/AP等无线覆盖漫游实用性评价
###3. 基于N3150 CPU的x86软路由架设及虚拟机实践
###4. socat udproxy等Openwrt插件功能使用

**参考**：
- 同时大量参考了[Timeforget](https://lwz322.github.io)的博客
 -  文章思路比较清晰，引用来源清楚，有出处的都可以找到原来讨论的地方看有没有人遇到自己相同问题
 -  本博来自Fork他的博客，因为第一次接触博客模板，不知道有什么应该改的没有改，希望没有侵犯他的各项权利