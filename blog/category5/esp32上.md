---
title: arduino2.1搭建esp32s3环境
keywords: arduino2.1搭建esp32s3环境
desc: teedoc 生成静态博客页面, 第一篇博客
author: wuboy19
date: 2023-06-12
tags: esp32s3, blog, arduino2.1
---



<!-- more -->


## 下载aruduino软件
[arduino官网链接](https://www.arduino.cc/en/software)因为我是win11,所以就下载windows install类型就可以  
>首选项-附加开发板管理器网址中填入
```
https://espressif.github.io/arduino-esp32/package_esp32_index.json
```
>如图  
![图片](../../../wuboy19.github.io/static/image/1.png)
## 下载安装包  
>方法一esp32 2.0.9的离线package
链接：https://pan.baidu.com/s/1uq9IxmwRhW2VRhXsFgMd2w 
提取码：2ua7  

>方法二：科学上网下载  
但是我自己通过科学上网也有问题，会报错失败然后给出一个github的zip网址，把提示的网址下载下来也可以
## 环境的安装
+ 打开文件夹的显示隐藏项目文件
+ 将方法一或者方法二的压缩包放到放到 用户文件夹\AppData\Local\Arduino15\staging\packages\ 下
+ 在arduino开发板管理器运行安装esp32


