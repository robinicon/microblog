---
layout:     post
title:      安装Apache Maven
date:       2016-09-12 23:47:00
summary:    如何安装Apache Maven?
categories: jekyll-pixyll
---

本来只是想找个时间，找个地点安心学习一下Jave的服务器开发，谁知道原来世界很复杂，有好多附带的东西需要学习Maven就是其中一个。
 
我为什么要弄这个玩意儿？原因很简单想学习一些Java的开发框架，但是现在已经不再是之前的下载.jar 安装配置的时代了，都改用哦那个各种工具比如Maven...

1.下载地址: http://maven.apache.org/download.cgi

解释一下，我现在学习用的是最low的windows电脑，所以下载安装用的是windows版的Maven.

2.解压这个安装包到 d:\javalib 目录下（个人电脑设置）

3.配置环境变量 d:\javalib\apache-maven-3.3.9\bin 因为之前安装过java 8 我以为这样就大功告成了.于是就在cmd里输入我的第一个maven命令
###windows 控制台
    mvn -v
其结果可想而知...没有JAVA_HOME这个环境变量... 这是大学时代里教科书里的东西，我用的是windows无脑安装的java 跟 jdk...
那么就只好再来一遍
点开我的电脑->属性->高级系统设置->环境变量 编辑一个叫JAVA_HOME的环境变量

4.验证一下
###windows 控制台
    echo %JAVA_HOME%

就这么点儿破事儿折腾了20分钟

后来瞄了一眼官方的文档里其实提供了安装的文档，其实文档里全都写清楚了，就是我当时没去看而已

原文大意如下:
Windows 提示
检查环境变量是否存在，比如:
    echo %JAVA_HOME% ##文中写的测试命令就是后来看到这个才写的 ^ ^;
添加解压包的bin路径到你的用户PATH环境变量之后，比如 c:\Program File\apache-maven\bin,
winkey + r 然后执行
    mvn -v 

好吧！人家早都写清楚了，只不过是我没看到...个人眼神问题...

最后附上官方文档，我英语停留在ABC阶段...
http://maven.apache.org/install.html
