# 专业基础

专业基础是你需要不断进行精进的东西，在此教程中我们所提到的专业基础你需要在**长时间内**不断坚持学习。因此，在本教程中我们重点介绍你应该去学习的一些基础知识。

微服务是目前新兴的一种软件开发架构，其中开发微服务的框架以 Java 的生态最为丰富，我们推荐你了解一些生态中的基本框架，如果你的就业方向倾向于Java开发，你可以长时间的规划进行学习。但是，项目组的方向并不是使用java语言开发微服务系统，更多的是研究现在微服务系统所存在的问题。

{% embed url="https://spring.io/projects/spring-boot" %}

{% embed url="https://spring.io/projects/spring-cloud" %}

同时，目前，使用 Go 语言开发的与云服务相关的软件显著增多，Docker和K8s的兴起使得应用微服务架构的软件运维更加方便和智能，同时istio的兴起让服务治理更加方便。这三个都是微服务方向所必需的技能。

{% embed url="https://www.docker.com" %}

{% embed url="https://kubernetes.io" %}

{% embed url="https://istio.io/" %}

由于云原生的操作系统多为 Linux，故对于 Linux 的基本使用也是必须要掌握的。

## 编程语言相关

### Java

Java 生态完善，拥有丰富的框架资料和实践项目。本教程并不过多对此进行阐述。你应熟悉基本的 Java 编程，对于基本技术比较熟练，能够使用框架进行开发工作。我们认为你应该已经具备这些基本的技能。如果你从来没有接触过Java语言，我们推荐你根据下面的文档进行学习。然而对于项目组工作而言，学习Java语言并不是重点，你应合理地分配好时间。

#### 基础知识

如果你从来没有接触过Java语言，掌握好基本的 Java 语法是第一步。

* Java 编程思想
* Java 核心技术编程

#### 进阶

并发和设计模式在大型项目的框架中使用很多，虽然不一定会直接用到所有，但是熟悉它们一定受益匪浅。

* 并发编程：《Java 并发编程实战》
* 设计模式：《Head First 设计模式》，《设计模式之禅》
* 网络编程：《Java TCP/IP 编程》
* JVM：有兴趣可以读一读，《深入理解 Java 虚拟机：JVM 高级特性与最佳实践》，挑选看，对 Java 语言的理解一定会更深刻。

{% hint style="info" %}
建议没事看看书或者博客，以后实践中慢慢掌握。有些可能找工作的时候会问...
{% endhint %}

#### 框架和微服务

常用框架：Spring、SpringBoot、SpringCloud 全家桶。很多教程视频等，主要了解 Spring 的基本知识,熟悉 SpringBoot 的使用，重在 SpringCloud 的微服务组件的使用和理解。

### Go

Go 语言简洁高效，是天生的高并发语言，在云原生的许多基础应用当中得到使用。其一，熟练使用 Go 能方便的处理服务端的编程工作；其二，是阅读 Kubernetes，Istio 等云原生应用源代码的基本功，加深你对微服务的理解。你应该优先地掌握 Go 语言的使用，云原生的工作无法绕开 Go 语言。你可以根据下面的文档有选择地进行学习。

#### 基础学习---偏向于实践

* 《Go 语言编程》，许世伟，吕桂华等编著，版本较老，但是思想比较重要。
* 《Go 语言圣经》，即《The Go Programming Language》中文版
* 《Go 语言高级编程》--- 柴树彬，曹春晖。本书涵盖 CGO、Go 汇编语言、RPC 实现、Web 框架实现、分布式系统等**高阶主题**，针对 Go 语言有一定经验想深入了解 Go 语言各种高级用法的开发人员。

#### 练手项目

* 《Go 语言编程之旅：一起用 Go 做项目》，作者：陈剑煜，徐新华。面向项目实践，同时会针对核心细节进行分析。
* 尝试自己写一个 web 框架。资料：极客时间专栏---叶剑锋，手把手带你写一个 Web 框架

{% hint style="info" %}
练手项目很多，做出点东西就好，难易程度自选.
{% endhint %}

#### 框架学习

* gin 框架:用 Go (Golang) 编写的 HTTP web 框架。---[文档链接](https://www.topgoer.com/gin%E6%A1%86%E6%9E%B6/)
* go-micro：专注于简化分布式系统开发的微服务生态系统。
* Go chassis：华为开源的一个 go 语言微服务开发框架
* gRPC 框架：Google 公司开发的一个高性能、开源和通用的 RPC 框架，面向移动和 HTTP/2 设计。

{% hint style="info" %}
选择需要或者感兴趣的就好。
{% endhint %}

#### 微服务

利用 Go 语言实现微服务的搭建和部署,实际服务内容无所谓，重在实践体会。

## Linux

Linux 的使用尤为关键，掌握其基本的命令以及在 Linux 系统中部署应用是必须要掌握的技能。

### 部署 Linux 环境

首先，你需要部署一个 Linux 环境，有以下四种方式：

* 在 Windows 系统中使用虚拟机安装 Linux。
* 在 Win 10 的系统中使用 Windows Subsystem for Linux (WSL)。
* 安装双系统使用 Linux。
* 购买 vps 使用 Linux。

对于在 Windows 系统中使用虚拟机安装 Linux，这是一个比较容易的事情，你可以直接通过百度和谷歌搜索找到这个问题的答案。

对于在 Win10 的系统中使用 WSL，你可以参考[微软官方](https://docs.microsoft.com/zh-cn/windows/wsl/)的文档获取相关信息。此外，你可能需要安装 Windows Terminal 作为终端，同样你可以参考[微软官方](https://docs.microsoft.com/zh-cn/windows/terminal/)的文档。

{% embed url="https://docs.microsoft.com/zh-cn/windows/wsl/" %}

{% embed url="https://docs.microsoft.com/zh-cn/windows/terminal/" %}

对于安装双系统使用 Linux，你同样可以通过谷歌和百度寻找到答案。

对于购买 vps 使用 Linux，你可以使用阿里云、腾讯云以及其他云服务商提供的相关服务，每个月 10 元左右，更容易入门如何使用 Linux。

{% hint style="info" %}
实际上，我们最推荐第二种方法，因为你可以在使用 Win10 的同时，优雅且方便地使用 Linux。我们最不推荐第三种方法，折腾双系统的时间可能会比你学习 Linux 的时间更长。如果你的主机性能良好，我们则推荐第一种方式。
{% endhint %}

### Linux 基础书籍推荐

实际上，对于初次接触 Linux 或者只仅仅接触了一点 Linux 的人来说，学习 Linux 的过程是比较枯燥的，因为书一般来说都比较厚。

* Linux Command Line and Shell Scripting Bible
* Harley Hahn's Guide to Unix and Linux

{% embed url="https://book.douban.com/subject/26309537/" %}

{% embed url="https://book.douban.com/subject/4286737/" %}

对于第一本书，我们提供了本书的中文文字版PDF，作为组内成员可以共享，但是请尊重版权！

{% hint style="info" %}
你可能听说过《鸟哥的 Linux 私房菜》，如果你喜欢他的风格，也可以学习这本书。
{% endhint %}

### Linux 进阶书籍推荐

实际上，掌握了基本的 Linux 命令以及脚本编程，对于你日常使用 Linux 已经足够了。如果你希望了解一下更加底层的 Linux 知识，或者想精进操作系统知识或者网络编程，有以下的书籍可以推荐：

* Advance Bash-Scripting Guide
* Advanced Programming in the UNIX Environment, 3rd Edition
* UNIX 网络编程

{% embed url="https://book.douban.com/subject/3010746/" %}

{% embed url="https://book.douban.com/subject/11937511/" %}

{% embed url="https://book.douban.com/subject/1500149/" %}
