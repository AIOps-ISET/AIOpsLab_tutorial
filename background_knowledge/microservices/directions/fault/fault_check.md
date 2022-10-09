# 故障检测及诊断

## 入门综述及参考资料

Anomaly Detection and Failure Root Cause Analysis in (Micro) Service-Based Cloud Applications: A Survey系统详细地讲述了故障检测及诊断的应用，且侧重于技术，刚看的时候可能比较吃力，但这是入门的第一步！

{% embed url="https://dl.acm.org/doi/full/10.1145/3501297" %}

同时我们推荐一个GitHub仓库awesome-AIOps，有许多AIOps的学习资料，可以参考。

{% embed url="https://github.com/linjinjin123/awesome-AIOps" %}

## Benchmark

* Train-Ticket：复旦大学train-ticket案例测试系统，知名度较高。
* NAB：异常检测的benchmark，本身包含数据，只需要建立算法即可运行。

{% embed url="https://github.com/FudanSELab/train-ticket" %}

{% embed url="https://github.com/numenta/NAB" %}

## 数据集

* 阿里巴巴：生产集群中微服务的`trace`数据集，多个版本，比较新
* AzurePublicDataset：Azure当中的`trace`数据集，分两类：`VM traces`和`Azure Functions traces`
* Google Borg: Borg系统生产的`Trace` 数据，稍微旧一点，数据量较大，需要通过BigQuery访问
* Webscope | Yahoo Labs：已标注的异常检测数据集，数据量不大

{% embed url="https://github.com/alibaba/clusterdata" %}

{% embed url="https://github.com/Azure/AzurePublicDataset" %}

{% embed url="https://github.com/google/cluster-data" %}

{% embed url="https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70" %}
