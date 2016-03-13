


---
## 安装mahout0.11.0

安装有两种方式，一种是直接下载安装，另一种是编译安装。这里采用方式一。

```
wget http://www.eu.apache.org/dist/mahout/0.11.0/apache-mahout-distribution-0.11.0.tar.gz
tar -xzvf apache-mahout-distribution-0.10.1-src.tar.gz -C /opt/
cd /opt/apache-mahout-distribution-0.11.0
```

---
## 配置
为在mahout中使用spark，需配置MAHOUT_HOME和SPARK_HOME，如下所示，大家可按自己环境进行修改。

```
export MAHOUT_HOME=/opt/apache-mahout-distribution-0.11.0
export SPARK_HOME=/opt/cloudera/parcels/CDH-5.3.8-1.cdh5.3.8.p0.5/lib/spark
```

---
## 与之前版本的区别
待补充

----
[↑ 返回上级](https://github.com/asin929/linux-software/blob/master/Big-Data/Big-Data.md)

[← 返回首页](https://github.com/asin929/linux-software)
