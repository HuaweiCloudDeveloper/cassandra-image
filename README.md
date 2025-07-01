<p align="center">
  <h1 align="center">Cassandra Database</h1>
  <p align="center">
    <strong>English</strong> | <a href="README_ZH.md">简体中文</a>
  </p>

## Table of Contents

- [Repository Introduction](#project-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Project Introduction
[Cassandra](https://github.com/apache/Cassandra) is an open-source distributed database management system designed for storing extremely large amounts of data.

### **Core Features**
**1. Distributed and Decentralized Architecture**
- It uses a P2P network structure where all nodes are equal, avoiding single points of failure.
- Data is allocated through the consistent hashing algorithm, supporting dynamic node expansion.

**2. High Availability and Fault Tolerance**
- The multi-replica mechanism enables cross-data center replication, supporting over 99.9% availability.
- Node communication is based on the Gossip protocol, which automatically handles failover.

**3. High-Performance Writes**
- The LSM-Tree storage engine optimizes write throughput, with a single cluster supporting tens of millions of QPS.

**4. Adjustable Consistency**
- It supports multi-level strategies from ZERO (weak consistency) to ALL (strong consistency).

The open-source image product [**Cassandra**](https://marketplace.huaweicloud.com/contents/9f55f9d6-83ed-4fa8-8ae5-4d02028ab162#productid=OFFI1121281976600530944) provided by this project has Cassandra and its related operating environments pre-installed and provides deployment templates. Come and follow the usage guide to easily start an "out-of-the-box" efficient experience!

> **System requirements are as follows:**
> - CPU: 2GHz or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                            | Feature Description                                           | Remarks |
|---------------------------------|------------------------------------------------| --- |
| [Cassandra-4.1.3-kunpeng](https://github.com/HuaweiCloudDeveloper/cassandra-image/tree/Cassandra-4.1.3-kunpeng) | Installed and deployed based on Kunpeng servers + Huawei Cloud EulerOS 2.0 64-bit |  |

## Get Help
- For more questions, you can contact us via [issues](https://github.com/HuaweiCloudDeveloper/cassandra-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace.
- You can view other open-source images at [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## How to Contribute
- Fork this repository and submit a merge request.
- Synchronously update README.md based on your open-source image information.