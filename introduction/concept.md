# 什么是弹性伸缩

> 该产品处于内测中，如有需要您可以联系客户经理申请使用

弹性伸缩UAS（UCloud Auto Scaling）是根据用户提前设置的规则，动态调整负载均衡集群下计算资源，形成既能满足用户高峰业务时的扩容需求，又能在用户非高峰业务时的成本控制，增加当前计算资源的利用率。


# 使用限制

- 一个伸缩组对应一个主机模版、多个负载均衡
- 目前使用伸缩组部署的业务必须为无状态应用，如有数据信息存储等需求建议保存到独立的云资源中
- 加入伸缩组的机器，全部受伸缩规则限制，伸缩组内机器可能会被删除
