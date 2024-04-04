---
title: 如何搭建我的博客
tags:
  - blog
draft: false
---
## 下载 quartz 仓库模板

``` shell
$ git clone https://github.com/jackyzha0/quartz.git blogs
$ cd blogs
$ npm i
$ npx quartz create
```
`npx quartz create` 用来进行初始化博客骨架，我选择的是使用一个空的博客从零开始编写搭建。

![](https://raw.githubusercontent.com/vurihuang/images/master/imgs/202404041956444.png)

执行如下命令进行预览：
``` sh
$ npx quartz build --serve
```
![](https://raw.githubusercontent.com/vurihuang/images/master/imgs/202404041948190.png)

## 如何部署到 Github

