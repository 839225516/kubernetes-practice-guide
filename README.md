# Kubernetes 实践指南

## Roadmap

本书正在起草初期，内容将包含大量 Kubernetes 实践干货，大量规划内容还正在路上，勾选的表示是已经可以在左侧导航栏中找到的并预览的文章，但不代表已经完善，会不断的优化改进。

* [ ] 部署指南
  * [ ] 部署方案选型
  * [ ] 单机部署
  * [ ] 二进制部署
  * [ ] 工具部署
    * [ ] Kubeadm
    * [ ] Minikube
    * [ ] Bootkube
    * [ ] Ansible
* [ ] 插件扩展
  * [ ] 网络
  * [ ] 运行时
    * [ ] Docker
    * [ ] Containerd
    * [ ] CRI-O
  * [ ] 存储
  * [ ] Ingress Controller
  * [ ] Scheduler Plugin
  * [ ] Device Plugin
  * [ ] Cloud Provider
  * [ ] Network Policy
* [ ] 排错指南
  * [ ] 问题排查
    * [x] Pod 排错
    * [x] 网络排错
    * [x] 集群排错
    * [x] 其它排错
  * [ ] 处理实践
    * [x] 高负载
    * [x] 内存碎片化
    * [x] 磁盘空间满
    * [x] inotify watch 耗尽
  * [ ] 踩坑分享
    * [x] DNS 5 秒延时
    * [x] cgroup 泄露
    * [x] tcp\_tw\_recycle 引发丢包
    * [x] 驱逐导致服务中断
    * [ ] conntrack 冲突导致丢包
  * [ ] 排错技巧
    * [x] 分析 ExitCode 定位 Pod 异常退出原因
    * [x] 容器内抓包定位网络问题
    * [x] 使用 Systemtap 定位疑难杂症
* [ ] 最佳实践
  * [ ] 服务高可用
    * [ ] 使用反亲和性避免单点故障
    * [x] 服务更新不中断
    * [ ] 节点下线不停服
    * [x] 解决长连接服务扩容失效
  * [ ] 动态伸缩
    * [ ] 使用 HPA 对 Pod 水平伸缩
    * [ ] 使用 VPA 对 Pod 垂直伸缩
    * [ ] 使用 Cluster Autoscaler 对节点水平伸缩
  * [ ] 资源限制
    * [ ] 资源预留
    * [ ] Request 与 Limit
    * [ ] Resource Quotas
    * [ ] Limit Ranges
  * [ ] 资源隔离
    * [ ] 利用 kata-container 隔离容器资源
    * [ ] 利用 gVisor 隔离容器资源
    * [ ] 利用 lvm 和 xfs 实现容器磁盘隔离
    * [ ] 利用 lxcfs 隔离 proc 提升容器资源可见性
  * [ ] 集群安全
    * [x] 集群权限控制
    * [ ] PodSecurityPolicy
    * [ ] 集群审计
  * [ ] GPU
  * [ ] 大页内存
  * [ ] 证书管理
    * [x] 安装 cert-manager
    * [x] 使用 cert-manager 自动生成证书
  * [ ] 配置管理
    * [ ] Helm
      * [x] 安装 Helm
      * [x] Helm V2 迁移到 V3
      * [ ] 使用 Helm 部署与管理应用
      * [ ] 开发 Helm Charts
    * [ ] Kustomize
      * [ ] Kustomize 基础入门
  * [ ] 备份恢复
  * [ ] 大规模集群
    * [ ] 内核参数优化
    * [ ] 调度器优化
  * [ ] 集群迁移
  * [ ] 多集群
  * [x] 泛域名转发
  * [x] kubectl 实用技巧
  * [ ] 监控
    * [ ] Prometheus
    * [ ] Grafana
  * [ ] 服务治理
    * [ ] 服务发现
    * [ ] 分布式追踪
      * [ ] Jaeger
  * [ ] K8S 可视化管理
    * [ ] Kubernetes Dashboard
    * [ ] KubSphere
    * [ ] Weave Scope
    * [ ] Rancher
    * [ ] Kui
    * [ ] Kubebox
  * [ ] 服务发现
  * [ ] 基础设施容器化部署
    * [ ] ETCD
    * [ ] Zookeeper
    * [ ] Redis
    * [ ] TiKV
    * [ ] ElasticSearch
      * [x] [使用 elastic-oparator 部署 Elasticsearch 和 Kibana](best-practice/elasticsearch/install-elasticsearch-and-kibana-with-elastic-oparator)
    * [ ] MySQL
    * [ ] TiDB
    * [ ] PostgreSQL
    * [ ] MongoDB
    * [ ] Cassandra
    * [ ] InfluxDB
    * [ ] OpenTSDB
* [ ] 开发指南
  * [ ] 开发环境搭建
  * [ ] Operator
  * [ ] client-go
  * [ ] 社区贡献
* [ ] 领域应用
  * [ ] 微服务架构
  * [ ] Service Mesh
    * [ ] Istio
  * [ ] Serverless
  * [ ] DevOps
  * [ ] 人工智能
  * [ ] 大数据

## 在线阅读

本书将支持中英文两个语言版本，通常文章会先用中文起草并更新，等待其内容较为成熟完善，更新不再频繁的时候才会翻译成英文，点击左上角切换语言。

* [ ] 中文: [https://k8s.imroc.io](https://k8s.imroc.io)
* [ ] English: [https://k8s.imroc.io/v/en/](https://k8s.imroc.io/v/en/)

### 项目源码

项目源码存放于 Github 上: [https://github.com/imroc/kubernetes-practice-guide](https://github.com/imroc/kubernetes-practice-guide)

### 贡献

欢迎参与贡献和完善内容，贡献方法参考 [CONTRIBUTING](https://github.com/imroc/kubernetes-practice-guide/blob/master/CONTRIBUTING.md)

### License

![](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)

[署名-非商业性使用-相同方式共享 4.0 \(CC BY-NC-SA 4.0\)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)

