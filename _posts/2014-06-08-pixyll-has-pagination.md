---
layout:     post
title:      苹果系统安装Tomcat
date:       2015-06-12 13:50:42
summary:    如何在苹果系统安装Tomcat?
categories: jekyll-pixyll
---

在苹果系统安装Tomcat:
首先下载最新的Tomcat包(http://tomcat.apache.org/ 下载Binary Distributions/Core目录下tar.gz)，然后下载后解压将文件加命名为Tomcat，把这个文件加移动到根目录/Library中。(拷贝到~/library/资源库中)
在Terminal中执行 
	sudo sh Library/tomcat/bin/startup.sh
(tomcat与文件夹名称一致包含大小写)如果遇到提示
	No such file or directory
错误提示，请执行
	sudo chmod 755 Library/Tomcat/bin/*.sh 
和 
	sudo chmod 755 Library/Tomcat/bin/*.bat
然后重新执行startup.sh，如果想停止Tomcat，直接执行shutdown.sh即可。
在执行sudo时，必须使用带密码的用户。

启动:
	sudo sh Library/Tomcat/bin/startup.sh，(tomcat与文件夹名称一致包含大小写)

关闭:
	sudo sh Library/Tomcat/bin/shutdown.sh

设置环境变量:
	export PATH=/Users/Lion/Library/tomcat/bin/:$PATH