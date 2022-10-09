# 故障检测及诊断

## 微服务故障相关

微服务领域当中合理官方前后的次序

### 入门综述

- [Anomaly Detection and Failure Root Cause Analysis in (Micro) Service-Based Cloud Applications: A Survey](https://dl.acm.org/doi/full/10.1145/3501297?casa_token=Ca3APwG8dRoAAAAA%3AeJfqc-BlElEgsXUh_lWOtQxNbAvpxNWVIizWPYDvZ7ZD6CDjW2Z6wqx9sbpZ1Im2tjyDrkvuCwec): 详细且全面，多侧重于技术之上

- [awesome-AIOps](https://github.com/linjinjin123/awesome-AIOps): AIOps的学习资料，具有一定参考性

### Benchmark

- [Train-Ticket](https://github.com/FudanSELab/train-ticket)：复旦大学train-ticket案例测试系统，知名度较高。
- [NAB](https://github.com/numenta/NAB)：异常检测的benchmark，本身包含数据，只需要建立算法即可运行。

### 数据集

- [阿里巴巴](https://github.com/alibaba/clusterdata)：生产集群中微服务的`trace`数据集，多个版本，比较新
- [AzurePublicDataset](https://github.com/Azure/AzurePublicDataset)：Azure当中的`trace`数据集，分两类：`VM traces`和`Azure Functions traces`
- [Google Borg](https://github.com/google/cluster-data): Borg系统生产的`Trace` 数据，稍微旧一点，数据量较大，需要通过BigQuery访问
- [Webscope | Yahoo Labs](https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70&guce_referrer=aHR0cHM6Ly9naXRodWIuY29tL2xpbmppbmppbjEyMy9hd2Vzb21lLUFJT3Bz&guce_referrer_sig=AQAAANtwZ-LWTurFxGzHOaXK6OSvY3XoHN1X-vaOCwqMzImz9bS3Moo3yCmThX-lkS87OviQDjADuDd-cxMTz6dlQefuk8_q1-_tFBEPnHYkr88-Gc83YyxpI7efahEKvktmoKBwaJPnbdc7BRgxP02fO0bg-ALRb_lq7DVzPBml5EHZ&guccounter=2)
：已标注的异常检测数据集，数据量不大

