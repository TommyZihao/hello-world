# 用树莓派搜寻地外文明

> 子豪兄开篇语：
>
> - 本文介绍了如何用树莓派微型电脑参与世界上最大的分布式计算平台BOINC的科学计算项目，特别是其中最著名的搜寻地外文明SETI@home项目。并介绍了其它有趣的分布式科学计算项目。
>
> - 二十年前本项目精巧的分布式计算、数据分发与回收、积分奖励系统，正是近几年火热的区块链和数字货币系统的萌芽。向本项目的所有贡献者致敬。
> - 我为了写本文，准备了八年时间。
> - 作者：同济大学开源软件协会 [子豪兄Tommy](https://github.com/TommyZihao)  微信公众号：子豪兄的科研小屋
[使用Markdown语法增加的跳转到“前言”的链接](#前言) 
![](https://upload-images.jianshu.io/upload_images/13714448-47bffce99a5f5fb5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 伯克利开放式网络计算平台BOINC和SETI@home项目

- SETI@home是1999年加州大学伯克利分校发起的分布式计算项目，旨在充分利用全球计算机的闲置算力，分析阿雷西博射电望远镜搜集的宇宙射线数据，从不同频段识别可能的文明信号，搜寻地外文明。
- 经过近20年的运营，SETI@home是迄今为止最成功的分布式计算项目，虽然没能找到地外文明的直接证据，但任何连网的电脑都可无条件加入，吸引全球志愿者贡献了巨量的算力，算力超过了任何超算电脑。
- 伯克利在此基础上开发了BOINC分布式计算平台(Berkeley Open Infrastructure for Network Computing)，部署了涉及生物医学、天体物理、密码破译、数学证明等众多领域的[科研项目（点我看这些有趣的项目）](http://boinc.berkeley.edu/projects.php)，
- - [科研项目](#1)其中还包括了中科院的计算项目。
- [跳到一个锚](#jump)

## 在树莓派上安装BOINC客户端

仅需要一行命令即可安装

```shell
sudo apt-get install boinc-client boinc
```

输入`y`和回车，确定安装

输入以下命令查看CPU温度

```shell
vcgencmd measure_temp
```

<h2 id="1"> BOINC平台上其它有趣的各领域分布式计算项目



<span id="jump">跳转到的地方</span>

## 参考文献

> [Bilibili视频：科技小制作 - 树莓派的好去处——SETI@Home - by 科技小制作](https://www.bilibili.com/video/av9388526?from=search&seid=6157990192498395439)
>
> [维基百科：SETI@home](https://zh.wikipedia.org/wiki/SETI@home)
>
> [BOINC官方主页](https://boinc.berkeley.edu/)

<span id="jump">Hello World</span>
# 前言
