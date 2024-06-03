# eBPF技术

之所以有这个板块，是因为实际上可观测性也是我们组的一个研究方向。为什么要学习 eBPF 技术，可以引用[BPF学习总结](https://feisky.xyz/posts/2021-01-06-ebpf-learn-path/)这篇博客——“Linux 内核一直是实现监控/可观察性、网络和安全性的理想场所。不幸的是，这往往是不切实际的，因为它需要改变内核源代码或加载内核模块，并导致层层抽象叠加。eBPF 是一项革命性的技术，它可以在 Linux 内核中运行沙盒程序，而无需改变内核源代码或加载内核模块。”

在最开始接触BPF技术的时候，可以阅读它的开山之作：

{% embed url="https://www.tcpdump.org/papers/bpf-usenix93.pdf?spm=a2c6h.12873639.0.0.47f72d54vVldQy&file=bpf-usenix93.pdf" %}

## BPF技术社区

* [Articles (cn-zh)](https://arthurchiao.art/articles-zh/)

* [https://ebpf.io](https://ebpf.io/)，最全BPF学习资源网站，主要由Cilium团队维护，上面会及时更新BPF技术的文档和视频。⭐
  
* https://lwn.net/Kernel/Index/#Berkeley_Packet_Filter ，lwn是学习Linux内核技术的最好的网站，这个BPF分类文章集合，记录了很多BPF里程碑事件的前前后后，既学会了知识，又明白了背景。⭐
  
* https://cilium.readthedocs.io/en/stable/bpf/，Cilium提供的BPF文档，是我看到过的最具实战价值的BPF手册，值得好好阅读。⭐
 
* https://www.kernel.org/doc/html/latest/bpf/bpf_devel_QA.html，开发BPF必读Q&A，里面是维护BPF内核代码的大佬给出的代码开发建议，读了能明白社区是如何运作BPF的。 ⭐

## bpf相关的代码仓库

* https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf.git/ 这个repo是Linux社区官方维护的独立bpf代码仓库，一旦发布新版本后，代码就不会大改，只接受bug fix，相当于master repo，最终会merge到linux内核代码主干中。
  
* https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/ 这个repo也是Linux社区官方维护的bpf代码仓库，更新频繁，用于引入新功能或现有功能优化，稳定后merge到上面的master repo，相当于feature repo。

## BPF社区的大神们

* Brendan Gregg，[Brendan Gregg's Homepage](https://www.brendangregg.com/)，来自Netflix最强BPF布道师，他的博客都是关于Linux系统优化的，观点独到，每一篇都值得一读；

* Alexei Starovoitov，eBPF创造者，目前在Facebook就职，经常能在内核代码commit中看到他的踪迹；
  
* Daniel Borkmann，eBPF kernel co-maintainer，目前在Cilium所在的公司Isovalent就职，是给eBPF增加feature的能力者；
  
* Thomas Graf，Cilium之父，Isovalent的CTO，他也是eBPF和Cilium的强力布道师，能说会道，各种大会上都有他的风采；
  
* Quentin Monnet，BPFTool co-maintainer，Quentin是在stackoverflow上bpf问题的killer，twitter有关于eBPF的系列实战短文，值得细品；
  
* Oracle 的技术博客分享：[Alan Maguire | Oracle Blogs](https://blogs.oracle.com/linux/authors/alan-maguire)


## BPF书籍

* eBPF 技术进阶使用：[Articles (cn-zh)](https://arthurchiao.art/articles-zh/)

* 官网的介绍 [What is eBPF? An Introduction and Deep Dive into the eBPF Technology](https://ebpf.io/what-is-ebpf)

* BTF（BPF 类型格式，它提供结构信息以避免 Clang 和内核头文件依赖） 和 CO-RE（BPF Compile-Once Run-Everywhere） 技术手册 [BPF CO-RE reference guide](https://nakryiko.com/posts/bpf-core-reference-guide/)

* [《Linux Observability with BPF》](https://www.oreilly.com/library/view/linux-observability-with/9781492050193/) 作者David Calavera和Lorenzo Fontana, 这本书篇幅不长，是来自sysdig的两位大佬写的BPF手册书，推荐入门阅读
  
* [《Linux内核观测技术BPF》](https://item.jd.com/12939760.html) 是最近刚出版的第一本BPF中文书籍，为上面英文书的翻译版本，由范彬和狄卫华两位翻译。 ⭐
  
* [《BPF Performance Tools》](http://www.brendangregg.com/bpf-performance-tools-book.html) 这是Brendan Gregg大神对于BPF技术如何做系统性能优化的一本集大成者的秘籍，BPF学习者必备。⭐
  
* [《Systems Performance: Enterprise and the Cloud, 2nd Edition》](http://www.brendangregg.com/systems-performance-2nd-edition-book.html) 这是Brendan Gregg大神系统优化书籍的第二版，篇幅较长，但是值得一啃。
 
* 最新的书籍：《**Learning eBPF**》Liz Rice，专注于容器安全等领域的大牛。⭐

## BPF技术分享

1. 最开始提到的最近两年的Kubecon上的eBPF相关Session下面是最新的几个session详细链接：
    - 绕过conntrack，使用eBPF增强 IPVS优化k8s网络性能：https://v.qq.com/x/page/s3137ehoq8i.html
  
    - 深入了解服务网格数据平面性能和调优：https://v.qq.com/x/page/v3137ax6zss.html
  
    - Kubernetes中用于混沌与跟踪的BPF：https://v.qq.com/x/page/f3130lpe0iv.html
  
    - https://kccnceu20.sched.com/event/ZejN/tutorial-using-bpf-in-cloud-native-environments-alban-crequy-marga-manterola-kinvolk
  
    - https://kccnceu20.sched.com/event/Zeoz/hubble-ebpf-based-observability-for-kubernetes-sebastian-wicki-isovalent
  
    - https://kccnceu20.sched.com/event/Zexb/designing-a-grpc-interface-for-kernel-tracing-with-ebpf-leonardo-di-donato-sysdig
  
    - https://kccnceu20.sched.com/event/ZemQ/ebpf-and-kubernetes-little-helper-minions-for-scaling-microservices-daniel-borkmann-cilium
  
    - [https://kccnceu20.sched.com/event/Zewd/intro-to-falco-intrusion-detection-for-containers-shane-lawrence-shopify](https://kccnceu20.sched.com/event/Zewd/intro-to-falco-intrusion-detection-for-containers-shane-lawrence-shopify%20)
  
    - https://kccnceu20.sched.com/event/ZetL/seccomp-security-profiles-and-you-a-practical-guide-duffie-cooley-vmware
  
    - https://kccnceu20.sched.com/event/ZeqL/k8s-in-the-datacenter-integrating-with-preexisting-bare-metal-environments-max-stritzinger-bloomberg
  
1. LPC 2020 Networking and BPF Summit，这个会刚结束不久，可以说是BPF技术的专题会，上面有非常多的eBPF实践案例以及未来可能增加的功能列表，比如BPF Map是否能resize，而不是一上来就定义好大小。

## 使用BPF技术的项目

罗列使用BPF技术的项目：

* Tcpdump
* BCC, BPFTrace, kubectl-trace from IOVisor
* Cilium from Isovalent
* Falco from Sysdig
* Katran from Facebook
* Bottlerocket from Amazon

中文社区有：

* 腾讯云 IPVS-BPF K8S网络优化方案
* Kernel Chaos With BPF by PingCAP
* 网易轻舟做系统检测和网络优化
* 字节跳动做高性能网络ACL管理

-- 文档材料源自刘雨晴学长
