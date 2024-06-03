# Linux内核知识

Linux Kernel 是操作系统的核心，它管理硬件资源、提供系统服务和支持多任务处理等。如今Linux 内核知识已经很庞大了，可以按照自己的兴趣广泛探索。通过以下系统构成图谱可以窥见一下内核世界。

{% embed url="https://makelinux.github.io/kernel/map/" %}

## 用户态

Linux/Unix 用户态层面包含文件系统与IO、内存、网络、Terminal、进/线程、系统等，其中详细的Linux指令学习可以参考Linux基础知识。

这一部分的内容可以通过翻阅以下书籍进行学习：

* 《Linux/unix系统编程手册》

{% embed url="https://book.douban.com/subject/25809330/" %}

## 内核态

Linux 内核态是指操作系统内核执行的特权模式，在该模式下，内核可以直接访问硬件和内存资源，执行关键系统任务并管理用户态进程的运行。在这一部分包含了更多较为硬核的模块，尤其还涉及到如何在内核进行编译、调试、驱动开发、内核开发等。如果有志于做更层次的 Linux 学习与研究，而不仅仅使用 Linux 提供的API等，以下的推荐博客与书籍可能对你大有裨益：

* 《Debug Hacks — 深入调试的技术与工具》
* 《Linux设备驱动开发详解-宋宝华》

{% embed url="https://book.douban.com/subject/6799412/" %}

{% embed url="https://book.douban.com/subject/5351818/" %}

如果你对国产操作系统感兴趣，想进一步了解相关的近况，可以到[龙芯开源社区](http://www.loongnix.cn/zh/)学习相关资源。

当你下定决心希望做 Linux 内核开发时，一个良好的工作环境或许能带来事半功倍的效果，那么这篇博客[Linux内核开发环境](https://mysummary.readthedocs.io/zh/latest/%E8%BD%AF%E4%BB%B6%E6%9E%84%E6%9E%B6%E8%AE%BE%E8%AE%A1/%E5%88%86%E4%BA%AB%E6%88%91%E7%9A%84Linux%E5%86%85%E6%A0%B8%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83.html)或许对你有很大的帮助.

## 核心子系统入门与分析

如果你对 Linux 中某个子模块感兴趣并且希望在内核中进行实践操作，那么推荐参考下面的书籍：

* 《Linux内核设计与实现》
* 《深入Linux内核架构》
* 《深入理解Linux内核》
* 《图解Linux内核基于 6.x》

{% embed url="https://book.douban.com/subject/6097773/" %}

{% embed url="https://book.douban.com/subject/4843567/" %}

{% embed url="https://book.douban.com/subject/2287506/" %}

{% embed url="https://dcd.cmpkgs.com/ebook/web/index.html#/pdfReader?SkuExternalId=P00109-01-5C67ECD2736472B8C7C0CF8A200777E310C940731131795F5A4ACA93E6551A18-Pdf&Extra=qEbbiKvTB-FwgKrzAi0f6IEEy6I4LUJ1Wn7_oAxJV4xZHHKznSVqgtfahIfwniugxqv6z7OgGIEIGkjCuRDFLBqZ0kWgYBV5oXDJJWiJQrlfAaflxuWPGbBDGqhGoMdLrK-ihZeTt4InKiw-AragRHTvXPKK1M9IGI6MJIcHz0lheCK952uUGN35tYwIC6yFvvE-leeCkPg9_eVhqfbgk99lQOyAJwt5ZDlKO57NKsvg7X6ZOOLEv_-NS9rSyDMtdFbzyDr1JkqxX6tJIDEqlA%3D%3D" %}

同时，在一些博客中也可学习到相关的内容，[Linux 内核实战课 - 人人极客社区](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzIxMjE1MzU4OA==&action=getalbum&album_id=2683052151098802179&from_itemidx=1&from_msgid=2648934685&scene=173&count=3&nolastread=1#wechat_redirect)、[极客时间Linux内核技术实践课](https://time.geekbang.org/column/intro/100058001?utm_campaign=geektime_search&utm_content=geektime_search&utm_medium=geektime_search&utm_source=geektime_search&utm_term=geektime_search&tab=catalog)等。

需要注意的是，从使用 Linux 到深入 Linux 做特定模块的开发与研究并不是一件简单的事，需要长时间对这个领域保持关注与探索，需要花时间才能逐渐了解这个 Linux 世界。

## 内核知识概况

这个部分并不是指导要怎么学习 Linux 中某个具体的模块，而是罗列了一些上述内容中或许没有提及但是在内核中同样重要的组成成分：内存研究、进/线程调度研究、锁机制、文件系统、设备驱动模型、虚拟化技术、内核数据结构、GNU C与make在内核中的使用、BPF技术等。尤其是BPF技术，将会在额外的章节做更进一步的阐述。

-- 文档材料源自刘雨晴学长
