# 微服务与云原生

## 基本认识

一开始需要建立对微服务的基本了解，知道它从哪里来，要到哪里去：[《凤凰架构》](https://icyfenix.cn/summary/)，其中“演进中的架构”和“不可变基础设施”章节详细的介绍了微服务与云原生，“分布式的基石”则介绍了建立分布式系统需要克服的困难，而它们也是许多微服务研究方向的来源，同时有简单的动手实践，理论与实践结合。

## 经典的微服务论文

2014年，Martin Fowler和James Lewis发表文章--[《Microservices: A Definition of This New Architectural Term》](https://martinfowler.com/articles/microservices.html)

## 容器与容器编排

在操作系统当中，首先了解到的是虚拟化，而虚拟化技术和容器技术的区别在哪？

### Docker

Docker是如何基于Linux的系统调用建立起来的？  [一个造轮子指南](https://blog.lizzie.io/linux-containers-in-500-loc.html)

为什么需要容器？容器的作用在哪？它是如何工作的？

推荐阅读：

* Docker

### Kubernetes

Kubernetes 已经成为事实上的容器编排标准，有必要了解它的工作方式和部分工作原理。

推荐阅读：

* 《Kubernetes in action》，初步的使用，足够对付大部分的应用场景。
* 张勇---深入理解 Kubernetes (一个专栏课程，追求深入理解的话可以看)
* 官方文档，实时查阅
* ...

### istio


