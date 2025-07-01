<p align="center">
  <h1 align="center">Cassandra数据库</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
[Cassandra](https://github.com/apache/Cassandra) 是一套开源分布式数据库管理系统，用于储存特别大的数据。

### **核心特性**
**1.分布式无中心架构‌**
 - 采用 P2P 网络结构，所有节点对等，避免单点故障。
 - 通过一致性哈希算法分配数据，支持动态节点扩容。

**2.高可用与容错‌**
 - 多副本机制实现跨数据中心复制，支持 99.9% 以上可用性。
 - 基于 Gossip 协议的节点通信，自动处理故障转移。

**3.高性能写入‌**
 - LSM-Tree 存储引擎优化写入吞吐，单集群支持千万级 QPS。

**4.可调一致性‌**
 - 支持从 ZERO（弱一致）到 ALL（强一致）的多级别策略。

本项目提供的开源镜像商品 [**Cassandra**](https://marketplace.huaweicloud.com/contents/9f55f9d6-83ed-4fa8-8ae5-4d02028ab162#productid=OFFI1121281976600530944)，已预先安装 Cassandra 及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
> - CPU: 2GHz 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                            | 特性说明                                           | 备注 |
|---------------------------------|------------------------------------------------| --- |
| [Cassandra-4.1.3-kunpeng](https://github.com/HuaweiCloudDeveloper/cassandra-image/tree/Cassandra-4.1.3-kunpeng) | 基于 鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/cassandra-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
