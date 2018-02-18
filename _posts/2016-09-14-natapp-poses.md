---
layout: post
title: 外网映射---内网穿透工具NATAPP---灵感源自QQ浏览器微信调试工具
categories: NATAPP
description: 外网映射---内网穿透工具NATAPP---灵感源自QQ浏览器微信调试工具
keywords: NATAPP
---
## 前言 ##

**内网穿透，即NAT穿透，网络连接时术语，计算机是局域网内时，外网与内网的计算机节点需要连接通信**


----------

## 项目必备##

> 搭建本地服务器可以查考我的博客---   [怎样利用XAMPP搭建本地php环境](http://blog.csdn.net/kingrome2017/article/details/74347818)

**没有本地服务无法访问 http://127.0.0.1   任然是然并卵 **


----------


## NATAPP1分钟快速上手 ##

第一步：注册账号 [快速入口](https://natapp.cn/register)

第二步：登录后,点击左边 购买隧道,免费即可--需要实名认证

![这里写图片描述](http://img.blog.csdn.net/20170915105251689?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2luZ3JvbWUyMDE3/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

第三步： 这里以web演示为主，点击免费购买

![这里写图片描述](http://img.blog.csdn.net/20170915105347734?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2luZ3JvbWUyMDE3/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

*购买成功*

![这里写图片描述](http://img.blog.csdn.net/20170915105511313?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2luZ3JvbWUyMDE3/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)


----------

**重点内容**

第四步：在 natapp.cn 根据您的本机下载对应的客户端  [快速下载链接](https://natapp.cn/#download)

下载之后,解压至任意目录,得到natapp.exe

![这里写图片描述](http://img.blog.csdn.net/20170915111103590?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2luZ3JvbWUyMDE3/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

**注意不要着急双击因为还有一步没配置**


----------
第四步： 根据操作系统下载不同的config.ini文件到刚才下载的natapp.exe同级目录 详见[快速链接下载配套系统的.ini 文件](https://natapp.cn/article/config_ini)



**修改里面内容得到的authtoken填进去**

![这里写图片描述](http://img.blog.csdn.net/20170915110159265?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2luZ3JvbWUyMDE3/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

第五步：

 windows下,直接双击natapp.exe 即可.

![这里写图片描述](http://img.blog.csdn.net/20170915110359334?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2luZ3JvbWUyMDE3/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)


Tunnel Status  Online 代表链接成功
Version      当前客户端版本,如果有新版本,会有提示
Forwarding    当前穿透 网址 或者端口
Web Interface  是本地Web管理界面,可在隧道配置打开或关闭,仅用于web开发测试
Total Connections 总连接数



----------

**该网址  http:// 4simke.natappfree.cc  就是可以全球访问的网址！！！ **



