## 相关项目
### 关于Avro
> Avro 是一个独立于编程语言的数据序列化系统。
其目的是为了解决Hadoop中Writable类型的不足：缺乏语言的可移植性。

---
#### 内存中的序列化和反序列化
待定

---
### 关于Parquet

> Parquet 是一种能够有效存储嵌套数据的列式存储格式。
#### Parquet 文件格式
Parquet 文件由一个文件头(header),一个或多个紧随其后的文件块(block),以及一个用于结尾的文件尾(footer)构成。

#### Parquet 的配置

Parquet 文件的属性在操作时设置。

#### Avor, Protocol Buffers 和Thrift


#### Parquet MapReduce

---
### 关于 Flume
> Flume 是hadoop　日志收集系统,同时Flume也可以被用来传输大量事件数据。
其目的是用于从许多不同的源中收集，聚合和移动大量日志数据到一个集中式的数据表存储区。

---
### 关于Sqoop

> sqoop 是Hadoop和关系型数据库服务器之间传输数据的工具。
其核心功能有：
