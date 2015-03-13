# 项目框架 #

## 项目环境 ##
  * 使用语言: Java
  * 使用框架:
    1. 表示层: zk (一个基于Ajax的轻量级组件框架,用Java实现),官方主页 www.zkoss.org
    1. 业务层: Spring (http://www.springframework.org)
    1. 持久层: Hibernate v3 (http://www.hibernate.org)
    1. Map: Google Earth(gdata http://code.google.com/apis/gdata/)
    1. 索引(可选):lucene (http://lucene.apache.org/)
  * 开发平台:
    1. 开发IDE: Eclipse 3.3.1 [下载页面](http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/europa/winter/eclipse-jee-europa-winter-win32.zip)
    1. Web 容器: Tomcat 5.5 [下载](http://apache.mirror.phpchina.com/tomcat/tomcat-5/v5.5.26/bin/apache-tomcat-5.5.26.exe)
    1. 数据库: MySQL 5.0 [下载页面](http://dev.mysql.com/downloads/mysql/5.0.html)

## 项目分工 ##
> 第一期基本模仿eemap完成wiki功能地图。
| 成员 | 任务 | 需要知识 |
|:-------|:-------|:-------------|
| 陈则润 | 地图，项目设计 | zk,gdata |
| 甘崇志 | 页面,wiki模式的实现 | zk,wiki |
| 杨济荣 | 底层设计(便签的持久化),业务层bean | Spring,Hibernare |
| 刘鹏翔 | 标签搜索，并协助杨济荣 | Spring,Hibernare,Lucene(视情况) |


以上任务为初步分配，如有异议可以提出