# SpringBoot项目的打包部署

### 若依官方文档教程：

- [项目部署](http://doc.ruoyi.vip/ruoyi/document/hjbs.html#%E9%83%A8%E7%BD%B2%E7%B3%BB%E7%BB%9F)

但是光只了解这么点知识还不够，你必须要再去了解相关的知识，完善自己的知识体系。 比如：

- 项目本地打包后，如何发布到（远程）服务器，并在服务器上启动项目、停止项目、查看项目运行日志来排错等？。
- 阿里云服务器
- 我本人使用的是苹果电脑，所以需要了解 MAC 系统如何连接远程服务器，有什么好的软件？


所以呢，我就到网上搜索浏览了下相关博客， 这里留两个我觉得还可以的博客链接，需要时阅读即可，就不重复写文字教程了。

### 项目打包部署两种方式：war包和jar包

#### 1、打jar包部署：

- [Springboot 如何打包部署项目](https://blog.csdn.net/qq_34491508/article/details/91490434)


#### 2、打war包部署：

- [springboot 项目部署到服务器 两种方式
  ](https://blog.csdn.net/qq_22638399/article/details/81506448)


你以为这就够了吗？NO! 如今项目打包部署有一个主流的技术：Docker容器，但是呢，我还没使用过它，也不了解它，于是
在网上又找了一篇博客，可以入个门。

- [一键部署 Spring Boot 项目到远程 Docker 容器，就是这么秀](http://springboot.javaboy.org/2019/0830/springboot-docker)