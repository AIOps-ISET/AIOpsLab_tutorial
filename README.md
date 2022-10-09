# 导论

欢迎来到西安电子科技大学智能软件工程实验室 AIOps 组新生培训。

![AIOps Team](assets/AIOps_logo.jpg)

教程内容托管于[GitHub](https://github.com/AIOps-ISET/AIOpsLab_tutorial)。

GitBook 在线阅读地址为： [Tutorial](https://aiopsteam.gitbook.io/aiops-tutorial/)。

本文档使用[lint-md](https://github.com/lint-md/lint-md)进行中文 MarkDown 文件的格式检查， 务必在提交 Pr 之前确保格式的正确。

## 参与贡献

注意，由于我们采用MarkDown的形式进行教程的书写，GitBook有些特殊的MarkDown格式，我们记录在这里以便后续的查询。如果你仅仅只想阅读教程，你应该跳过这部分的内容。

### Hint

GitBook总共有四种形式的Hint：

{% hint style="success" %}
This is a successful hint
{% endhint %}

{% hint style="info" %}
This is a info hint
{% endhint %}

{% hint style="warning" %}
This is a warning hint
{% endhint %}

{% hint style="danger" %}
This is a danger hint
{% endhint %}

### File

GitBook支持File类型的操作，更加的美观。

{% file src="./assets/addItemById.png" %}

### Embed a URL

比起传统的MarkDown的语法`[]()`，GitBook提供了更加优雅的方式：

{% embed url="https://martinfowler.com/articles/microservices.html" %}

同时GitBook支持Google Docs等文档的在线浏览机制。可惜依赖于科学上网的功能，不过这仍然是个好功能。

### Tabs

GitBook提供了Tabs，更加的方便。

{% tabs %}

{% tab title="First Tab" %}
This is the tab1 content
{% endtab %}

{% tab title="Second Tab" %}
This is the tab2 content
{% endtab %}

{% endtabs %}
