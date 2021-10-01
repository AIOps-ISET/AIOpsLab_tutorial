# 专业基础

微服务是目前新兴的一种软件开发架构，其中开发微服务的框架以 Java 的生态最为丰富：

* [Spring Boot](https://spring.io/projects/spring-boot)
* [Spring Cloud](https://spring.io/projects/spring-cloud)

目前，使用 Go 语言开发的与云服务相关的软件显著增多：

* [Docker](https://www.docker.com/)
* [K8s](https://kubernetes.io/)

由于云原生的操作系统多为 Linux，故对于 Linux 的基本使用也是必须要掌握的。

## Linux

Linux 的使用尤为关键，掌握其基本的命令以及在 Linux 系统中部署应用是必须要掌握的技能。

### 部署 Linux 环境

首先，你需要部署一个 Linux 环境，有以下四种方式：

* 在 Windows 系统中使用虚拟机安装 Linux。
* 在 Win 10 的系统中使用 Windows Subsystem for Linux (WSL)。
* 安装双系统使用 Linux。
* 购买 vps 使用 Linux。

对于在 Windows 系统中使用虚拟机安装 Linux，这是一个比较容易的事情，你可以直接通过百度和谷歌搜索找到这个问题的答案。

对于在 Win10 的系统中使用 WSL，你可以参考[微软官方](https://docs.microsoft.com/zh-cn/windows/wsl/)的文档获取相关信息。此外，你可能需要安装 Windows Terminal 作为终端，同样你可以参考[微软官方](https://docs.microsoft.com/zh-cn/windows/terminal/)的文档。当然，你也可以参考小组成员写过的[教程](https://luolibrary.com/64ee9fde735a/)。

对于安装双系统使用 Linux，你同样可以通过谷歌和百度寻找到答案。

对于购买 vps 使用 Linux，你可以使用阿里云、腾讯云以及其他云服务商提供的相关服务，每个月 10 元左右，更容易入门如何使用 Linux。

{% hint style="info" %}
实际上，我们最推荐第二种方法，因为你可以在使用 Win10 的同时，优雅且方便地使用 Linux。我们最不推荐第三种方法，折腾双系统的时间可能会比你学习 Linux 的时间更长。
{% endhint %}

### Linux 基础书籍推荐

实际上，对于初次接触 Linux 或者只仅仅接触了一点 Linux 的人来说，学习 Linux 的过程是比较枯燥的，因为书一般来说都比较厚。

* [Linux Command Line and Shell Scripting Bible](https://book.douban.com/subject/26309537/)。
* [Harley Hahn's Guide to Unix and Linux](https://book.douban.com/subject/4286737/)

{% hint style="info" %}
你可能听说过《鸟哥的 Linux 私房菜》，如果你喜欢他的风格，也可以学习这本书。
{% endhint %}

### Linux 进阶书籍推荐

实际上，掌握了基本的 Linux 命令以及脚本编程，对于你日常使用 Linux 已经足够了。如果你希望了解一下更加底层的 Linux 知识，或者想精进操作系统知识或者网络编程，有以下的书籍可以推荐：

* [Advance Bash-Scripting Guide](https://book.douban.com/subject/3010746/)。
* [Advanced Programming in the UNIX Environment, 3rd Edition](https://book.douban.com/subject/11937511/)。
* [UNIX 网络编程](https://book.douban.com/subject/1500149/)。
