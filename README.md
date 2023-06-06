# flink-patchs

针对特定场景的 flink 能力增加以及优化

## flink 1.14

- 增加配置项，支持 k8s 部署时，设置 cpu requests 以及 memory requests ，进行资源超卖 (慎用)
- 升级 netty 版本
- 增加 ARM64 环境下的 `libnetty_transport_native_epoll_aarch_64.so`