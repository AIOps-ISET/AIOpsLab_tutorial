# 微服务与云原生

## 基本认识

一开始需要建立对微服务的基本了解，知道它从哪里来，要到哪里去：**凤凰架构**书中，其中“演进中的架构”和“不可变基础设施”章节详细的介绍了微服务与云原生，“分布式的基石”则介绍了建立分布式系统需要克服的困难，而它们也是许多微服务研究方向的来源，同时有简单的动手实践，理论与实践结合。我们希望它通过通俗易懂的言语让你快速地认识什么是微服务

{% embed url="https://icyfenix.cn/summary/" %}

## 经典的微服务论文

* 2014 年，Martin Fowler 和 James Lewis 发表文章Microservices: A Definition of This New Architectural Term使得学术界开始对微服务架构进行研究。
* Microservices: Yesterday, Today, and Tomorrow：微服务的顶级综述，描述了微服务架构的过去、现在和未来帮助你从宏观上认识微服务

{% embed url="https://martinfowler.com/articles/microservices.html" %}
{% embed url="https://arxiv.org/pdf/1606.04036.pdf" %}

## 容器与容器编排

在操作系统当中，首先了解到的是虚拟化，而虚拟化技术和容器技术的区别在哪？

### Docker

Docker 是如何基于 Linux 的系统调用建立起来的？  [一个造轮子指南](https://blog.lizzie.io/linux-containers-in-500-loc.html)

为什么需要容器？容器的作用在哪？它是如何工作的？

推荐阅读：

* Docker 的[官方网站](https://www.docker.com/)。
* [Docker In Action](https://book.douban.com/subject/34466033/)。

### Kubernetes

Kubernetes 已经成为事实上的容器编排标准，有必要了解它的工作方式和部分工作原理。

推荐阅读：

* 《Kubernetes in action》，初步的使用，足够对付大部分的应用场景。
* 张勇---深入理解 Kubernetes (一个专栏课程，追求深入理解的话可以看)
* 官方文档，实时查阅
* ...

### istio

<!-- TODO: Add something about istio -->