# 专业基础

微服务是目前新兴的一种软件开发架构，其中开发微服务的框架以 Java 的生态最为丰富：

* [Spring Boot](https://spring.io/projects/spring-boot)
* [Spring Cloud](https://spring.io/projects/spring-cloud)

目前，使用 Go 语言开发的与云服务相关的软件显著增多：

* [Docker](https://www.docker.com/)
* [K8s](https://kubernetes.io/)

由于云原生的操作系统多为 Linux，故对于 Linux 的基本使用也是 必须要掌握的。

## 编程语言相关

### Java

Java生态完善，拥有丰富的框架资料和实践项目。

#### 基础

熟悉基本的Java编程，对于基本技术比较熟练，能够使用框架进行开发工作。

#### 参考资料

* 《Java编程思想》，有最新版《on Java8》，经常翻一翻
* 《Java核心技术编程》,相对容易阅读。

#### 进阶

* 并发编程：《Java并发编程实战》，
* 设计模式：《Head First 设计模式》，《设计模式之禅》，[可视化网站](https://refactoringguru.cn/)
* 网络编程：《Java TCP/IP 编程》
* ...
{% hint style="info" %}
    建议没事看看书或者博客，以后实践中慢慢掌握。
{% endhint %}

#### 框架和微服务

常用框架：Spring、SpringBoot、SpringCloud全家桶。很多教程视频等，主要了解Spring的基本知识,熟悉SpringBoot的使用，重在SpringCloud的微服务组件的使用和理解。

### Go

Go语言简洁高效，是天生的高并发语言，在云原生的许多基础应用当中得到使用。其一，熟练使用Go能方便的处理服务端的编程工作；其二，是阅读 Kubernetes，Istio 等云原生应用源代码的基本功。
#### 基础学习---偏向于实践

* 《Go语言编程》，许世伟，吕桂华等编著，版本较老，但是思想比较重要。
* 《Go语言圣经》，即《The Go Programming Language》中文版
* 《Go语言高级编程》--- 柴树彬，曹春晖。本书涵盖CGO、Go汇编语言、RPC实现、Web框架实现、分布式系统等**高阶主题**，针对Go语言有一定经验想深入了解Go语言各种高级用法的开发人员。  

#### 练手项目

* 《Go 语言编程之旅：一起用 Go 做项目》，作者：陈剑煜，徐新华。面向项目实践，同时会针对核心细节进行分析。
* 尝试自己写一个web框架。资料：极客时间专栏---叶剑锋，手把手带你写一个Web框架

{% hint style="info" %}
    练手项目很多，做出点东西就好，难易程度自选.
{% endhint %}

#### 框架学习

* gin框架:用 Go (Golang) 编写的 HTTP web 框架。---[文档链接](https://www.topgoer.com/gin%E6%A1%86%E6%9E%B6/)
* go-micro：专注于简化分布式系统开发的微服务生态系统。
* Go chassis：华为开源的一个 go 语言微服务开发框架
* gRPC框架：Google公司开发的一个高性能、开源和通用的 RPC 框架，面向移动和 HTTP/2 设计。
* ....

{% hint style="info" %}
    选择需要或者感兴趣的就好。
{% endhint %}

#### 微服务

利用Go语言实现微服务的搭建和部署,实际服务内容无所谓，重在实践和思考。









