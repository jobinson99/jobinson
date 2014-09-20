---
layout: post
title: "利用metalsmith建静态网站"
date: 2014-09-13 12:15:31 +0800
description: ""
categories: 建站之路
tags: [静态站, metalsmith]
lastmod: 
--- 

## 为何选用metalsmith ##

metalsmith的特点：

+ 全部插件化
+ 核心很小，就一个调用程序，处理目录，输入输出的标口层（标准接口层）
+ 灵活性大，可以生成各种类型项目：静态站，项目架构，生成工具，电子书，项目文档等


## 安装环境 ##

除了要安装metalsmith外，还要安装所需的插件

    $ npm install metalsmith

一般需要的插件：

assets：不渲染的部分
beautifier：为运行效率考虑，一般不需要。但为了方便检查代码生成结果，需要。
collections：分类？
navigation：根据稳健树输出导航
paginate：分页
permalinks：简化链接形式
tags：使用标签
templates：布局模板




## 模板选用 ##



## 预览 ##



