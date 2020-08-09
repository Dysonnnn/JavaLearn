# JavaLearn

java的方向大致分为
- javaEE
- 安卓
- 大数据

## 环境搭建

一般都是JavaEE的
如果是JavaWeb的 就不要
那个虽然简单 但是过时了

不过要接受javaEE的架构可能要看比较久
从面向过程的编程思想去到面向切面编程思想


tomcat7   
[下载网页](http://tomcat.apache.org/download-70.cgi)   
[windows版本下载地址](https://www-us.apache.org/dist/tomcat/tomcat-7/v7.0.94/bin/apache-tomcat-7.0.94.exe)

####  maven
maven配置[参考此文章](http://www.cnblogs.com/leefreeman/archive/2013/03/05/2944519.html)
[下载网页](http://maven.apache.org/download.cgi)

**windows系统下环境配置**
在我的电脑--->属性--->高级系统设置--->环境变量--->系统变量--->新建
```
变量名：M2_HOME
变量值：C:\Program Files\apache-maven-3.6.1
```
找到Path在环境变量值尾部加入：;%M2_HOME%\bin;  //前面注意分号  

检验：
打开CMD窗口运行命令
```
mvn -v
```
出现maven版本信息说明安装成功。



## Web服务器运行
- Apache
> Apache是Web服务器而Tomcat是Java应用服务器。 Apache服务器 只处理 静态HTML 
- tomcat
> tomcat服务器 静态HTML 动态 JSP Servlet 都能处理。

## 实战项目
1. [简易图书馆预约系统 带前端界面](https://github.com/Dysonnnn/ssmbookappointment)
