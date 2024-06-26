# 微服务与云原生

## 基本认识

一开始需要建立对微服务的基本了解，知道它从哪里来，要到哪里去：**凤凰架构**书中，其中“演进中的架构”和“不可变基础设施”章节详细的介绍了微服务与云原生，“分布式的基石”则介绍了建立分布式系统需要克服的困难，而它们也是许多微服务研究方向的来源，同时有简单的动手实践，理论与实践结合。我们希望它通过通俗易懂的言语让你快速地认识什么是微服务

{% embed url="https://icyfenix.cn/summary/" %}

## 经典的微服务论文

* 2014 年，Martin Fowler 和 James Lewis 发表文章Microservices: A Definition of This New Architectural Term使得学术界开始对微服务架构进行研究。
* Microservices: Yesterday, Today, and Tomorrow：微服务的顶级综述，描述了微服务架构的过去、现在和未来帮助你从宏观上认识微服务

{% embed url="https://martinfowler.com/articles/microservices.html" %}
{% embed url="https://arxiv.org/pdf/1606.04036.pdf" %}

## 容器、容器编排与服务治理

容器与容器编排是微服务运维的核心，目前学术界和工业界对于微服务运维的研究都集中于这三个基本的工具：

* Docker
* Kubernetes
* Istio

### 容器技术与虚拟化

虚拟化技术和容器技术的区别在哪？这是一个关键的问题，我们推荐下面的这些文章供你阅读，相信你对这两者之间的认识会得到加深。

{% embed url="https://www.atlassian.com/microservices/cloud-computing/containers-vs-vms" %}
{% embed url="https://www.ibm.com/cloud/blog/containers-vs-vms" %}

### Docker

Docker是目前最广泛使用的容器软件。首先你应该明白Docker基本的原理，如何把一个应用程序运行在Docker中，以及Docker是如何为这个应用程序提供一系列的隔离，保证每个服务之间的独立性，同时又使得能够容器能够通信？我们推荐Docker In Action这本书作为入门。

{% embed url="https://book.douban.com/subject/34466033/" %}

然而，Docker到底内部是如何实现的呢？当你理解了Docker的工作机制，你可能会思考容器是如何基于Linux提供的一系列机制建立起来的。我们推荐一个很简单的造轮子指南，你会通过不超过500行的C语言代码理解Docker基本的工作机制。

{% embed url="https://blog.lizzie.io/linux-containers-in-500-loc.html" %}

实际上，有许多优秀的教程教你如何写一个基本的Docker，rubber-docker提供了一系列的教程让你思考如何写一个容器，比起上面的C代码，会给你带来更多的思考和实践。

{% embed url="https://github.com/Fewbytes/rubber-docker" %}

同时，小组成员有实践过该项目的，你可以参考小组成员的GitHub去搭建环境。

{% embed url="https://github.com/shejialuo/rubber-docker" %}

如果你仍然不满足，想明白一个复杂的容器应该要怎么写，我们推荐《自己动手写Docker》。

{% embed url="https://book.douban.com/subject/27082348/" %}

同时小组成员已经动手进行过了实践，你可以参考他们的GitHub搭建环境。

{% embed url="https://github.com/shejialuo/miniDocker/" %}
{% embed url="https://github.com/North-C/GoPractice/tree/main/dockerBySelf" %}

### Kubernetes

容器已经让我们的生活变得更加的轻松了，然而当我们部署系统的时候，我们应该怎么去管理容器呢？如果我们的系统需要很多个容器呢？如何对容器本身实现更加细粒度的管理呢？这就是Kubernetes的作用。目前Kubernetes 已经成为事实上的容器编排标准，我们有必要了解它的工作方式和部分工作原理。

我们仍然推荐Kubernetes in action，当你学完前10章你应该就会对Kubernetes有个了解，能够使用Kubernetes进行容器的编排。

{% embed url="https://book.douban.com/subject/30418855/" %}

由于Kubernetes的复杂性，很少有教程教我们如何自己造一个Kubernetes，但是我们往往想知其所以然，所以如果你想要进阶你可以阅读Kubernetes源码剖析。这本书尽管描述的不详细，但是它能够给你带来宏观的认识。由于Kubernetes的代码量很大，属于相当复杂的开源项目，我们觉得这本书也只能做到这儿了。

{% embed url="https://book.douban.com/subject/35100082/" %}

### Istio

事物总是在不断发展的。为了让微服务运维更加顺畅，服务网格的概念就此出现，你可以参考以下的文章去理解服务网格的概念：

{% embed url="https://jimmysong.io/blog/what-is-a-service-mesh/" %}

{% embed url="https://www.redhat.com/zh/topics/microservices/what-is-a-service-mesh" %}

Istio就是目前微服务领域最热门的服务网格。Istio的书籍仍然有很多，但可惜的是istio in action并没有中文版，我们很推荐in action的书籍。因此，希望你可以阅读英文版进行学习。

{% embed url="https://book.douban.com/subject/33406485/" %}
