# 简介
本项目记录了我在搭建微服务架构过程中遇到的值得注意的问题和事项。
## 涉及的组件

服务类型 | 服务名称 | 版本
---|---|---
服务注册与发现 | Consul | 1.4.0
网关路由 | Zuul | 2.0.0.RELEASE
远程配置 | Spring Cloud Config | 2.0.0.RELEASE
熔断器 | Hystrix | 2.0.0.RELEASE
监控信息聚合 | Turbine | 2.0.0.RELEASE
监控仪表盘 | Hystrix Dashboard | 2.0.0.RELEASE
链路跟踪 | Zipkin + Sleuth | 2.12.0
消息队列 | RabbitMQ | 3.7.10