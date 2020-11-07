- [微服务](Microservices.md)
- 软件开发没有银弹。
- [微服务利弊权衡](https://martinfowler.com/articles/microservice-trade-offs.html)
  - 微服务优点：
    - 强模块边界：微服务加强了模块化结构
    - 独立部署：简单服务更容易部署，而且由于它们是自治的，所以当它们出错时不太可能导致系统故障。
    - 技术多样性：使用微服务，您可以混合使用多种语言、开发框架和数据存储技术
  - 微服务缺点：
    - 分布式：分布式系统更难编程，因为远程调用很慢，而且总是面临失败的风险。
    - 最终一致性：对于分布式系统而言，保持强一致性非常困难，这意味着每个人都必须管理最终一致性。
    - 操作复杂性：您需要一个成熟的操作团队来管理大量定期重新部署的服务。