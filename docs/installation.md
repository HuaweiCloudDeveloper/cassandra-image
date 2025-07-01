# Cassandra部署指南

## ‌一、环境准备

### 一、更新系统

```bash
yum -y update  
yum -y upgrade
```

## ‌二、安装包下载
下载Cassandra二进制包
```bash
wget https://archive.apache.org/dist/cassandra/4.1.3/apache-cassandra-4.1.3-bin.tar.gz
tar -zxvf apache-cassandra-4.1.3-bin.tar.gz
mv apache-cassandra-4.1.3 /opt/cassandra

# 配置环境变量
echo 'export CASSANDRA_HOME=/opt/cassandra' >> ~/.bashrc
echo 'export PATH=$PATH:$CASSANDRA_HOME/bin' >> ~/.bashrc
source ~/.bashrc
```

## ‌三、关键配置
编辑配置文件 $CASSANDRA_HOME/conf/cassandra.yaml：
```yml
# 监听地址（单机改为 localhost）
listen_address: localhost
rpc_address: localhost
```


## 四、连接 CQL Shell
```bash
$CASSANDRA_HOME/bin/cqlsh localhost 9042   # 出现以下提示即成功
Connected to Test Cluster at localhost:9042
```
