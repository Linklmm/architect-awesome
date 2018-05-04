
<h1>《后端架构师技术图谱》</h1>

[![知识共享协议（CC协议）](https://img.shields.io/badge/License-Creative%20Commons-DC3D24.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)
[![GitHub stars](https://img.shields.io/github/stars/xingshaocheng/architect-awesome.svg?style=flat&label=Star)](https://github.com/xingshaocheng/architect-awesome/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/xingshaocheng/architect-awesome.svg?style=flat&label=Fork)](https://github.com/xingshaocheng/architect-awesome/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/xingshaocheng/architect-awesome.svg?style=flat&label=Watch)](https://github.com/xingshaocheng/architect-awesome/watchers)

**最后更新于20180502**
* [数据结构](#数据结构)
	* [队列](#队列)
	* [集合](#集合)
	* [链表、数组](#链表数组)
	* [字典、关联数组](#字典关联数组)
	* [栈](#栈)
	* [树](#树)
		* [二叉树](#二叉树)
		* [完全二叉树](#完全二叉树)
		* [平衡二叉树](#平衡二叉树)
		* [二叉查找树（BST）](#二叉查找树bst)
		* [红黑树](#红黑树)
		* [B-，B+，B*树](#b-bb树)
		* [LSM 树](#lsm-树)
	* [BitSet](#bitset)
* [常用算法](#常用算法)
	* [排序、查找算法](#排序查找算法)
		* [选择排序](#选择排序)
		* [冒泡排序](#冒泡排序)
		* [插入排序](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#插入排序)
		* [快速排序](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#快速排序)
		* [归并排序](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#归并排序)
		* [希尔排序](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#希尔排序)
		* [堆排序](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#堆排序)
		* [计数排序](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#计数排序)
		* [桶排序](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#桶排序)
		* [基数排序](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#基数排序)
		* [二分查找](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#二分查找)
		* [Java 中的排序工具](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#java-中的排序工具)
	* [布隆过滤器](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#布隆过滤器)
	* [字符串比较](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#字符串比较)
		* [KMP 算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#kmp-算法)
	* [深度优先、广度优先](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#深度优先广度优先)
	* [贪心算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#贪心算法)
	* [回溯算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#回溯算法)
	* [剪枝算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#剪枝算法)
	* [动态规划](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#动态规划)
	* [朴素贝叶斯](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#朴素贝叶斯)
	* [推荐算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#推荐算法)
	* [最小生成树算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#最小生成树算法)
	* [最短路径算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#最短路径算法)
* [并发](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#并发)
	* [多线程](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#多线程)
	* [线程安全](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#线程安全)
	* [一致性、事务](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#一致性事务)
		* [事务 ACID 特性](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#事务-acid-特性)
		* [事务的隔离级别](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#事务的隔离级别)
		* [MVCC](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#mvcc)
	* [锁](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#锁)
		* [Java中的锁和同步类](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#java中的锁和同步类)
		* [公平锁 &amp; 非公平锁](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#公平锁--非公平锁)
		* [悲观锁](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#悲观锁)
		* [乐观锁 &amp; CAS](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#乐观锁--cas)
		* [ABA 问题](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#aba-问题)
		* [CopyOnWrite容器](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#copyonwrite容器)
		* [RingBuffer](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#ringbuffer)
		* [可重入锁 &amp; 不可重入锁](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#可重入锁--不可重入锁)
		* [互斥锁 &amp; 共享锁](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#互斥锁--共享锁)
		* [死锁](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#死锁)
* [操作系统](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#操作系统)
	* [计算机原理](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#计算机原理)
	* [CPU](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#cpu)
		* [多级缓存](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#多级缓存)
	* [进程](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#进程)
	* [线程](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#线程)
	* [协程](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#协程)
	* [Linux](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#linux)
* [设计模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#设计模式)
	* [设计模式的六大原则](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#设计模式的六大原则)
	* [23种常见设计模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#23种常见设计模式)
	* [应用场景](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#应用场景)
	* [单例模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#单例模式)
	* [责任链模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#责任链模式)
	* [MVC](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#mvc)
	* [IOC](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#ioc)
	* [AOP](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#aop)
	* [UML](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#uml)
	* [微服务思想](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#微服务思想)
		* [康威定律](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#康威定律)
* [运维 &amp; 统计 &amp; 技术支持](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#运维--统计--技术支持)
	* [常规监控](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#常规监控)
	* [APM](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#apm)
	* [统计分析](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#统计分析)
	* [持续集成(CI/CD)](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#持续集成cicd)
		* [Jenkins](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#jenkins)
		* [环境分离](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#环境分离)
	* [自动化运维](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#自动化运维)
		* [Ansible](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#ansible)
		* [puppet](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#puppet)
		* [chef](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#chef)
	* [测试](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#测试)
		* [TDD 理论](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#tdd-理论)
		* [单元测试](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#单元测试)
		* [压力测试](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#压力测试)
		* [全链路压测](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#全链路压测)
		* [A/B 、灰度、蓝绿测试](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#ab-灰度蓝绿测试)
	* [虚拟化](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#虚拟化)
		* [KVM](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#kvm)
		* [Xen](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#xen)
		* [OpenVZ](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#openvz)
	* [容器技术](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#容器技术)
		* [Docker](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#docker)
	* [云技术](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#云技术)
		* [OpenStack](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#openstack)
	* [DevOps](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#devops)
	* [文档管理](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#文档管理)
* [中间件](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#中间件)
	* [Web Server](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#web-server)
		* [Nginx](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#nginx)
		* [OpenResty](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#openresty)
		* [Apache Httpd](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#apache-httpd)
		* [Tomcat](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#tomcat)
			* [架构原理](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#架构原理)
			* [调优方案](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#调优方案)
		* [Jetty](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#jetty)
	* [缓存](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#缓存)
		* [本地缓存](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#本地缓存)
	* [客户端缓存](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#客户端缓存)
	* [服务端缓存](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#服务端缓存)
		* [Memcached](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#memcached)
		* [Redis](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#redis)
			* [架构](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#架构)
			* [回收策略](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#回收策略)
		* [Tair](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#tair)
	* [消息队列](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#消息队列)
		* [消息总线](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#消息总线)
		* [消息的顺序](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#消息的顺序)
		* [RabbitMQ](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#rabbitmq)
		* [RocketMQ](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#rocketmq)
		* [ActiveMQ](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#activemq)
		* [Kafka](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#kafka)
		* [Redis 消息推送](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#redis-消息推送)
		* [ZeroMQ](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#zeromq)
	* [定时调度](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#定时调度)
		* [单机定时调度](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#单机定时调度)
		* [分布式定时调度](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#分布式定时调度)
	* [RPC](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#rpc)
		* [Dubbo](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#dubbo)
		* [Thrift](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#thrift)
		* [gRPC](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#grpc)
	* [数据库中间件](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#数据库中间件)
		* [Sharding Jdbc](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#sharding-jdbc)
	* [日志系统](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#日志系统)
		* [日志搜集](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#日志搜集)
	* [配置中心](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#配置中心)
	* [API 网关](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#api-网关)
* [网络](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#网络)
	* [协议](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#协议)
		* [OSI 七层协议](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#osi-七层协议)
		* [TCP/IP](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#tcpip)
		* [HTTP](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#http)
		* [HTTP2.0](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#http20)
		* [HTTPS](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#https)
	* [网络模型](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#网络模型)
		* [Epoll](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#epoll)
		* [Java NIO](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#java-nio)
		* [kqueue](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#kqueue)
	* [连接和短连接](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#连接和短连接)
	* [框架](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#框架)
	* [零拷贝（Zero-copy）](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#零拷贝zero-copy)
	* [序列化(二进制协议)](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#序列化二进制协议)
		* [Hessian](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#hessian)
		* [Protobuf](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#protobuf)
* [数据库](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#数据库)
	* [基础理论](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#基础理论)
		* [数据库设计的三大范式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#数据库设计的三大范式)
	* [MySQL](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#mysql)
		* [原理](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#原理)
		* [InnoDB](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#innodb)
		* [优化](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#优化)
		* [索引](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#索引)
			* [聚集索引, 非聚集索引](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#聚集索引-非聚集索引)
			* [复合索引](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#复合索引)
			* [自适应哈希索引(AHI)](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#自适应哈希索引ahi)
		* [explain](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#explain)
	* [NoSQL](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#nosql)
		* [MongoDB](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#mongodb)
		* [Hbase](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#hbase)
* [搜索引擎](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#搜索引擎)
	* [搜索引擎原理](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#搜索引擎原理)
	* [Lucene](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#lucene)
	* [Elasticsearch](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#elasticsearch)
	* [Solr](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#solr)
	* [sphinx](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#sphinx)
* [性能](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#性能)
	* [性能优化方法论](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#性能优化方法论)
	* [容量评估](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#容量评估)
	* [CDN 网络](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#cdn-网络)
	* [连接池](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#连接池)
	* [性能调优](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#性能调优)
* [大数据](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#大数据)
	* [流式计算](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#流式计算)
		* [Storm](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#storm)
		* [Flink](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#flink)
		* [Kafka Stream](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#kafka-stream)
		* [应用场景](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#应用场景-1)
	* [Hadoop](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#hadoop)
		* [HDFS](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#hdfs)
		* [MapReduce](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#mapreduce)
		* [Yarn](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#yarn)
	* [Spark](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#spark)
* [安全](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#安全)
	* [web 安全](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#web-安全)
		* [XSS](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#xss)
		* [CSRF](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#csrf)
		* [SQL 注入](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#sql-注入)
		* [Hash Dos](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#hash-dos)
		* [脚本注入](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#脚本注入)
		* [漏洞扫描工具](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#漏洞扫描工具)
		* [验证码](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#验证码)
	* [DDoS 防范](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#ddos-防范)
	* [用户隐私信息保护](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#用户隐私信息保护)
	* [序列化漏洞](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#序列化漏洞)
	* [加密解密](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#加密解密)
		* [对称加密](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#对称加密)
		* [哈希算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#哈希算法)
		* [非对称加密](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#非对称加密)
	* [服务器安全](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#服务器安全)
	* [数据安全](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#数据安全)
		* [数据备份](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#数据备份)
	* [网络隔离](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#网络隔离)
		* [内外网分离](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#内外网分离)
		* [登录跳板机](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#登录跳板机)
	* [授权、认证](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#授权认证)
		* [RBAC](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#rbac)
		* [OAuth2.0](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#oauth20)
		* [双因素认证（2FA）](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#双因素认证2fa)
		* [单点登录(SSO)](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#单点登录sso)
* [常用开源框架](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#常用开源框架)
	* [开源协议](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#开源协议)
	* [日志框架](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#日志框架)
		* [Log4j、Log4j2](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#log4jlog4j2)
		* [Logback](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#logback)
	* [ORM](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#orm)
	* [网络框架](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#网络框架)
	* [Web 框架](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#web-框架)
		* [Spring 家族](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#spring-家族)
	* [工具框架](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#工具框架)
* [分布式设计](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#分布式设计)
	* [扩展性设计](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#扩展性设计)
	* [稳定性 &amp; 高可用](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#稳定性--高可用)
		* [硬件负载均衡](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#硬件负载均衡)
		* [软件负载均衡](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#软件负载均衡)
		* [限流](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#限流)
		* [应用层容灾](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#应用层容灾)
		* [跨机房容灾](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#跨机房容灾)
		* [容灾演练流程](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#容灾演练流程)
		* [平滑启动](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#平滑启动)
	* [数据库扩展](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#数据库扩展)
		* [读写分离模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#读写分离模式)
		* [分片模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#分片模式)
	* [服务治理](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#服务治理)
		* [服务注册与发现](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#服务注册与发现)
		* [服务路由控制](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#服务路由控制)
	* [分布式一致](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#分布式一致)
		* [CAP 与 BASE 理论](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#cap-与-base-理论)
		* [分布式锁](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#分布式锁)
		* [分布式一致性算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#分布式一致性算法)
			* [PAXOS](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#paxos)
			* [Zab](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#zab)
			* [Raft](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#raft)
			* [Gossip](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#gossip)
			* [两阶段提交、多阶段提交](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#两阶段提交多阶段提交)
		* [幂等](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#幂等)
		* [分布式一致方案](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#分布式一致方案)
		* [分布式 Leader 节点选举](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#分布式-leader-节点选举)
		* [TCC(Try/Confirm/Cancel) 柔性事务](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#tcctryconfirmcancel-柔性事务)
	* [分布式文件系统](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#分布式文件系统)
	* [唯一ID 生成](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#唯一id-生成)
		* [全局唯一ID](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#全局唯一id)
	* [一致性Hash算法](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#一致性hash算法)
* [设计思想 &amp; 开发模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#设计思想--开发模式)
	* [DDD(Domain-driven Design - 领域驱动设计)](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#ddddomain-driven-design---领域驱动设计)
		* [命令查询职责分离(CQRS)](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#命令查询职责分离cqrs)
		* [贫血，充血模型](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#贫血充血模型)
	* [Actor 模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#actor-模式)
	* [响应式编程](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#响应式编程)
		* [Reactor](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#reactor)
		* [RxJava](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#rxjava)
		* [Vert.x](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#vertx)
	* [DODAF2.0](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#dodaf20)
	* [Serverless](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#serverless)
	* [Service Mesh](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#service-mesh)
* [项目管理](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#项目管理)
	* [架构评审](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#架构评审)
	* [重构](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#重构)
	* [代码规范](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#代码规范)
	* [代码 Review](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#代码-review)
	* [RUP](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#rup)
	* [看板管理](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#看板管理)
	* [SCRUM](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#scrum)
	* [敏捷开发](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#敏捷开发)
	* [极限编程（XP）](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#极限编程xp)
	* [结对编程](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#结对编程)
	* [FMEA管理模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#fmea管理模式)
* [通用业务术语](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#通用业务术语)
* [技术趋势](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#技术趋势)
* [政策、法规](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#政策法规)
	* [法律](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#法律)
		* [严格遵守刑法253法条](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#严格遵守刑法253法条)
* [架构师素质](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#架构师素质)
* [团队管理](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#团队管理)
	* [招聘](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#招聘)
* [资讯](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#资讯)
	* [行业资讯](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#行业资讯)
	* [公众号列表](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#公众号列表)
	* [博客](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#博客)
		* [团队博客](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#团队博客)
		* [个人博客](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#个人博客)
	* [综合门户、社区](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#综合门户社区)
	* [问答、讨论类社区](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#问答讨论类社区)
	* [行业数据分析](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#行业数据分析)
	* [专项网站](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#专项网站)
	* [其他类](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#其他类)
	* [推荐参考书](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#推荐参考书)
		* [在线电子书](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#在线电子书)
		* [纸质书](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#纸质书)
			* [开发方面](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#开发方面)
			* [架构方面](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#架构方面)
			* [技术管理方面](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#技术管理方面)
			* [基础理论](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#基础理论-1)
			* [工具方面](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#工具方面)
			* [大数据方面](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#大数据方面)
* [技术资源](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#技术资源)
	* [开源资源](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#开源资源)
	* [手册、文档、教程](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#手册文档教程)
	* [在线课堂](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#在线课堂)
	* [会议、活动](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#会议活动)
	* [常用APP](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#常用app)
	* [找工作](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#找工作)
	* [工具](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#工具)
	* [代码托管](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#代码托管)
	* [文件服务](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#文件服务)
	* [综合云服务商](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#综合云服务商)
	

**（Toc generated by [simple-php-github-toc](https://github.com/xingshaocheng/simple-php-github-toc) ）**

# 数据结构

## 队列
* [《java队列——queue详细分析》](https://www.cnblogs.com/lemon-flm/p/7877898.html)
	* 非阻塞队列：ConcurrentLinkedQueue(无界线程安全)，采用CAS机制（compareAndSwapObject原子操作）。
	* 阻塞队列：ArrayBlockingQueue(有界)、LinkedBlockingQueue（无界）、DelayQueue、PriorityBlockingQueue，采用锁机制；使用 ReentrantLock 锁。

* [《LinkedList、ConcurrentLinkedQueue、LinkedBlockingQueue对比分析》](https://www.cnblogs.com/mantu/p/5802393.html)

## 集合
* [《Java Set集合的详解》](https://blog.csdn.net/qq_33642117/article/details/52040345)

## 链表、数组
* [《Java集合详解--什么是List》](https://blog.csdn.net/wz249863091/article/details/52853360)

## 字典、关联数组
* [《Java map 详解 - 用法、遍历、排序、常用API等》](https://baike.xsoftlab.net/view/250.html)

## 栈
* [《java数据结构与算法之栈（Stack）设计与实现》](https://blog.csdn.net/javazejian/article/details/53362993)
* [《Java Stack 类》](http://www.runoob.com/java/java-stack-class.html)
* [《java stack的详细实现分析》](https://blog.csdn.net/f2006116/article/details/51375225)
	* Stack 是线程安全的。
	* 内部使用数组保存数据，不够时翻倍。

## 树

### 二叉树

每个节点最多有两个叶子节点。
*  [《二叉树》](https://blog.csdn.net/cai2016/article/details/52589952)

### 完全二叉树
* [《完全二叉树》](https://baike.baidu.com/item/%E5%AE%8C%E5%85%A8%E4%BA%8C%E5%8F%89%E6%A0%91/7773232?fr=aladdin)
	* 叶节点只能出现在最下层和次下层，并且最下面一层的结点都集中在该层最左边的若干位置的二叉树。

### 平衡二叉树
左右两个子树的高度差的绝对值不超过1，并且左右两个子树都是一棵平衡二叉树。
* [《浅谈数据结构-平衡二叉树》](http://www.cnblogs.com/polly333/p/4798944.html)
* [《浅谈算法和数据结构: 八 平衡查找树之2-3树》](http://www.cnblogs.com/yangecnu/p/Introduce-2-3-Search-Tree.html)

### 二叉查找树（BST）
二叉查找树（Binary Search Tree），也称有序二叉树（ordered binary tree）,排序二叉树（sorted binary tree）。

* [《浅谈算法和数据结构: 七 二叉查找树》](http://www.cnblogs.com/yangecnu/p/Introduce-Binary-Search-Tree.html)


### 红黑树
* [《最容易懂得红黑树》](https://blog.csdn.net/sun_tttt/article/details/65445754)
	* 添加阶段后，左旋或者右旋从而再次达到平衡。 
* [《浅谈算法和数据结构: 九 平衡查找树之红黑树》](http://www.cnblogs.com/yangecnu/p/Introduce-Red-Black-Tree.html)

### B-，B+，B*树
MySQL是基于B+树聚集索引组织表

* [《B-树，B+树，B\*树详解》](https://blog.csdn.net/aqzwss/article/details/53074186)
* [《B-树，B+树与B\*树的优缺点比较》](https://blog.csdn.net/bigtree_3721/article/details/73632405)
	* B+ 树的叶子节点链表结构相比于 B- 树便于扫库，和范围检索。
### LSM 树

LSM（Log-Structured Merge-Trees）和 B+ 树相比，是牺牲了部分读的性能来换取写的性能(通过批量写入)，实现读写之间的。
Hbase、LevelDB、Tair（Long DB）、nessDB 采用 LSM 树的结构。LSM可以快速建立索引。

* [《LSM树 VS B+树》](https://blog.csdn.net/dbanote/article/details/8897599)
	* B+ 树读性能好，但由于需要有序结构，当key比较分散时，磁盘寻道频繁，造成写性能。
	* LSM 是将一个大树拆分成N棵小树，先写到内存（无寻道问题，性能高），在内存中构建一颗有序小树（有序树），随着小树越来越大，内存的小树会flush到磁盘上。当读时，由于不知道数据在哪棵小树上，因此必须遍历（二分查找）所有的小树，但在每颗小树内部数据是有序的。
	
* [《LSM树（Log-Structured Merge Tree）存储引擎》](https://blog.csdn.net/u014774781/article/details/52105708)
	* 极端的说，基于LSM树实现的HBase的写性能比MySQL高了一个数量级，读性能低了一个数量级。
	* 优化方式：Bloom filter 替代二分查找；compact 小数位大树，提高查询性能。
	* Hbase 中，内存中达到一定阈值后，整体flush到磁盘上、形成一个文件（B+数），HDFS不支持update操作，所以Hbase做整体flush而不是merge update。flush到磁盘上的小树，定期会合并成一个大树。

## BitSet

经常用于大规模数据的排重检查。

* [《Java Bitset类》](http://www.runoob.com/java/java-bitset-class.html)
* [《Java BitSet（位集）》](https://blog.csdn.net/caiandyong/article/details/51581160)

# 常用算法

* [《常见排序算法及对应的时间复杂度和空间复杂度》](https://blog.csdn.net/gane_cheng/article/details/52652705)

## 排序、查找算法

* [《常见排序算法及对应的时间复杂度和空间复杂度》](https://blog.csdn.net/gane_cheng/article/details/52652705)

### 选择排序
* [《Java中的经典算法之选择排序（SelectionSort）》](https://www.cnblogs.com/shen-hua/p/5424059.html)
	* 每一趟从待排序的记录中选出最小的元素，顺序放在已排好序的序列最后，直到全部记录排序完毕。

### 冒泡排序
* [《冒泡排序的2种写法》](https://blog.csdn.net/shuaizai88/article/details/73250615)
	* 相邻元素前后交换、把最大的排到最后。
	* 时间复杂度 O(n²) 

### 插入排序
* [《排序算法总结之插入排序》](https://www.cnblogs.com/hapjin/p/5517667.html)

### 快速排序
* [《坐在马桶上看算法：快速排序》](http://developer.51cto.com/art/201403/430986.htm)
	* 一侧比另外一次都大或小。 
### 归并排序
* [《图解排序算法(四)之归并排序》](http://www.cnblogs.com/chengxiao/p/6194356.html)
	* 分而治之，分成小份排序，在合并(重建一个新空间进行复制)。 

### 希尔排序
TODO

### 堆排序
* [《图解排序算法(三)之堆排序》](https://www.cnblogs.com/chengxiao/p/6129630.html)
	* 排序过程就是构建最大堆的过程，最大堆：每个结点的值都大于或等于其左右孩子结点的值，堆顶元素是最大值。

### 计数排序
* [《计数排序和桶排序》](https://www.cnblogs.com/suvllian/p/5495780.html)
	* 和桶排序过程比较像，差别在于桶的数量。

### 桶排序
* [《【啊哈！算法】最快最简单的排序——桶排序》](http://blog.51cto.com/ahalei/1362789)
* [《排序算法（三）：计数排序与桶排序》](https://blog.csdn.net/sunjinshengli/article/details/70738527)
	* 桶排序将[0,1)区间划分为n个相同的大小的子区间，这些子区间被称为桶。
	* 每个通单独进行排序，然后再遍历每个桶。

### 基数排序

按照个位、十位、百位、...依次来排。

* [《排序算法系列：基数排序》](https://blog.csdn.net/lemon_tree12138/article/details/51695211)
* [《基数排序》](https://www.cnblogs.com/skywang12345/p/3603669.html)


### 二分查找
* [《二分查找(java实现)》](https://www.cnblogs.com/coderising/p/5708632.html)
	* 要求待查找的序列有序。
	* 时间复杂度 O(logN)。

* [《java实现二分查找-两种方式》](https://blog.csdn.net/maoyuanming0806/article/details/78176957)
	* while + 递归。
### Java 中的排序工具
* [《Arrays.sort和Collections.sort实现原理解析》](https://blog.csdn.net/u011410529/article/details/56668545?locationnum=6&fps=1)
	* Collections.sort算法调用的是合并排序。
	* Arrays.sort() 采用了2种排序算法 -- 基本类型数据使用快速排序法，对象数组使用归并排序。

## 布隆过滤器

常用于大数据的排重，比如email，url 等。
核心原理：将每条数据通过计算产生一个指纹（一个字节或多个字节，但一定比原始数据要少很多），其中每一位都是通过随机计算获得，在将指纹映射到一个大的按位存储的空间中。注意：会有一定的错误率。
优点：空间和时间效率都很高。
缺点：随着存入的元素数量增加，误算率随之增加。

* [《布隆过滤器 -- 空间效率很高的数据结构》](https://segmentfault.com/a/1190000002729689)
* [《大量数据去重：Bitmap和布隆过滤器(Bloom Filter)》](https://blog.csdn.net/zdxiq000/article/details/57626464)
* [《基于Redis的布隆过滤器的实现》](https://blog.csdn.net/qq_30242609/article/details/71024458)
	* 基于 Redis 的 Bitmap 数据结构。
* [《网络爬虫：URL去重策略之布隆过滤器(BloomFilter)的使用》](https://blog.csdn.net/lemon_tree12138/article/details/47973715)
	* 使用Java中的 BitSet 类 和 加权和hash算法。

## 字符串比较

### KMP 算法
KMP：Knuth-Morris-Pratt算法（简称KMP）
核心原理是利用一个“部分匹配表”，跳过已经匹配过的元素。
* [《字符串匹配的KMP算法》](http://www.ruanyifeng.com/blog/2013/05/Knuth%E2%80%93Morris%E2%80%93Pratt_algorithm.html)

## 深度优先、广度优先
* [《广度优先搜索BFS和深度优先搜索DFS》](https://www.cnblogs.com/0kk470/p/7555033.html)

## 贪心算法
* [《算法：贪婪算法基础》](https://www.cnblogs.com/MrSaver/p/8641971.html)
* [《常见算法及问题场景——贪心算法》](https://blog.csdn.net/a345017062/article/details/52443781)

## 回溯算法
* [《 五大常用算法之四：回溯法》](https://blog.csdn.net/qfikh/article/details/51960331)

## 剪枝算法
* [《α-β剪枝算法》](https://blog.csdn.net/luningcsdn/article/details/50930276)

## 动态规划
* [《详解动态规划——邹博讲动态规划》](https://www.cnblogs.com/little-YTMM/p/5372680.html)
* [《动态规划算法的个人理解》](https://blog.csdn.net/yao_zi_jie/article/details/54580283)

## 朴素贝叶斯

* [《带你搞懂朴素贝叶斯分类算法》](https://blog.csdn.net/amds123/article/details/70173402)
	* P(B|A)=P(A|B)P(B)/P(A)

* [《贝叶斯推断及其互联网应用1》](http://www.ruanyifeng.com/blog/2011/08/bayesian_inference_part_one.html)
* [《贝叶斯推断及其互联网应用2》](http://www.ruanyifeng.com/blog/2011/08/bayesian_inference_part_two.html)


## 推荐算法
* [《推荐算法综述》](http://www.infoq.com/cn/articles/recommendation-algorithm-overview-part01)
* [《TOP 10 开源的推荐系统简介》](https://www.oschina.net/news/51297/top-10-open-source-recommendation-systems)

## 最小生成树算法
* [《算法导论--最小生成树（Kruskal和Prim算法）》](https://blog.csdn.net/luoshixian099/article/details/51908175)

## 最短路径算法

* [《Dijkstra算法详解》](https://blog.csdn.net/qq_35644234/article/details/60870719)

# 并发

## 多线程

* [《40个Java多线程问题总结》](http://www.importnew.com/18459.html)

## 线程安全

* [《Java并发编程——线程安全及解决机制简介》](https://www.cnblogs.com/zhanht/p/5450325.html)

## 一致性、事务

### 事务 ACID 特性
* [《数据库事务ACID特性》](https://blog.csdn.net/u012440687/article/details/52116108)

### 事务的隔离级别

* 未提交读：一个事务可以读取另一个未提交的数据，容易出现脏读的情况。
* 读提交：一个事务等另外一个事务提交之后才可以读取数据，但会出现不可重复读的情况（多次读取的数据不一致），读取过程中出现UPDATE操作，会多。（大多数数据库默认级别是RC，比如SQL Server，Oracle），读取的时候不可以修改。
* 可重复读： 同一个事务里确保每次读取的时候，获得的是同样的数据，但不保障原始数据被其他事务更新（幻读），Mysql InnoDB 就是这个级别。
* 序列化：所有事物串行处理（牺牲了效率）

* [《理解事务的4种隔离级别》](https://blog.csdn.net/qq_33290787/article/details/51924963)
* [数据库事务的四大特性及事务隔离级别](https://www.cnblogs.com/z-sm/p/7245981.html)

* [《MySQL的InnoDB的幻读问题 》](http://blog.sina.com.cn/s/blog_499740cb0100ugs7.html)
	* 幻读的例子非常清楚。
	* 通过 SELECT ... FOR UPDATE 解决。
	
* [《一篇文章带你读懂MySQL和InnoDB》](http://database.51cto.com/art/201804/570101.htm)
	* 图解脏读、不可重复读、幻读问题。


### MVCC


* [《【mysql】关于innodb中MVCC的一些理解》](https://www.cnblogs.com/chenpingzhao/p/5065316.html)
	* innodb 中 MVCC 用在 Repeatable-Read 隔离级别。
	* MVCC 会产生幻读问题（更新时异常。）

* [《轻松理解MYSQL MVCC 实现机制》](https://blog.csdn.net/whoamiyang/article/details/51901888)

	* 通过隐藏版本列来实现 MVCC 控制，一列记录创建时间、一列记录删除时间，这里的时间
	* 每次只操作比当前版本小（或等于）的 行。
	


## 锁

### Java中的锁和同步类

* [《Java中的锁分类》](https://www.cnblogs.com/qifengshi/p/6831055.html)
	* 主要包括 synchronized、ReentrantLock、和 ReadWriteLock。 

* [《Java并发之AQS详解》](https://www.cnblogs.com/waterystone/p/4920797.html)

* [《Java中信号量 Semaphore》](http://cuisuqiang.iteye.com/blog/2020146)
	* 有数量控制
	* 申请用 acquire，申请不要则阻塞；释放用 release。

* [《java开发中的Mutex vs Semaphore》](https://www.cnblogs.com/davidwang456/p/6094947.html)
	* 简单的说 就是Mutex是排它的，只有一个可以获取到资源， Semaphore也具有排它性，但可以定义多个可以获取的资源的对象。	 

### 公平锁 & 非公平锁

公平锁的作用就是严格按照线程启动的顺序来执行的，不允许其他线程插队执行的；而非公平锁是允许插队的。

* [《公平锁与非公平锁》](https://blog.csdn.net/EthanWhite/article/details/55508357)
	* 默认情况下 ReentrantLock 和 synchronized 都是非公平锁。ReentrantLock 可以设置成公平锁。

### 悲观锁 

悲观锁如果使用不当（锁的条数过多），会引起服务大面积等待。推荐优先使用乐观锁+重试。

* [《【MySQL】悲观锁&乐观锁》](https://www.cnblogs.com/zhiqian-ali/p/6200874.html)
	* 乐观锁的方式：版本号+重试方式
	* 悲观锁：通过 select ... for update 进行行锁(不可读、不可写，share 锁可读不可写)。

* [《Mysql查询语句使用select.. for update导致的数据库死锁分析》](https://www.cnblogs.com/Lawson/p/5008741.html)
	* mysql的innodb存储引擎实务锁虽然是锁行，但它内部是锁索引的。
	* 锁相同数据的不同索引条件可能会引起死锁。
	
* [《Mysql并发时经典常见的死锁原因及解决方法》](https://www.cnblogs.com/zejin2008/p/5262751.html)

### 乐观锁 & CAS

* [《乐观锁的一种实现方式——CAS》](http://www.importnew.com/20472.html)
	* 和MySQL乐观锁方式相似，只不过是通过和原值进行比较。	 

### ABA 问题

由于高并发，在CAS下，更新后可能此A非彼A。通过版本号可以解决，类似于上文Mysql 中提到的的乐观锁。

* [《Java CAS 和ABA问题》](https://www.cnblogs.com/549294286/p/3766717.html)
* [《Java 中 ABA问题及避免》](https://blog.csdn.net/li954644351/article/details/50511879)
	* AtomicStampedReference 和 AtomicStampedReference。 

### CopyOnWrite容器

可以对CopyOnWrite容器进行并发的读，而不需要加锁。CopyOnWrite并发容器用于读多写少的并发场景。比如白名单，黑名单，商品类目的访问和更新场景，不适合需要数据强一致性的场景。

* [《JAVA中写时复制(Copy-On-Write)Map实现》](https://www.cnblogs.com/hapjin/p/4840107.html)
	* 实现读写分离，读取发生在原始数据上，写入发生在副本上。  
	* 不用加锁，通过最终一致实现一致性。
	
* [《聊聊并发-Java中的Copy-On-Write容器》](https://blog.csdn.net/a494303877/article/details/53404623)

### RingBuffer 
* [《线程安全的无锁RingBuffer的实现【一个读线程，一个写线程】》](http://www.cnblogs.com/l00l/p/4115001.html)

### 可重入锁 & 不可重入锁

* [《可重入锁和不可重入锁》](https://www.cnblogs.com/dj3839/p/6580765.html)
	* 通过简单代码举例说明可重入锁和不可重入锁。
	* 可重入锁指同一个线程可以再次获得之前已经获得的锁。
	* 可重入锁可以用户避免死锁。
	* Java中的可重入锁：synchronized 和 java.util.concurrent.locks.ReentrantLock

* [《ReenTrantLock可重入锁（和synchronized的区别）总结》](https://www.cnblogs.com/baizhanshi/p/7211802.html)
	* synchronized 使用方便，编译器来加锁，是非公平锁。
	* ReenTrantLock 使用灵活，锁的公平性可以定制。
	* 相同加锁场景下，推荐使用 synchronized。

### 互斥锁 & 共享锁

互斥锁：同时只能有一个线程获得锁。比如，ReentrantLock 是互斥锁，ReadWriteLock 中的写锁是互斥锁。
共享锁：可以有多个线程同时或的锁。比如，Semaphore、CountDownLatch 是共享锁，ReadWriteLock 中的读锁是共享锁。

* [《ReadWriteLock场景应用》](https://www.cnblogs.com/liang1101/p/6475555.html)

### 死锁
* [《“死锁”四个必要条件的合理解释》](https://blog.csdn.net/yunfenglw/article/details/45950305)
	* 互斥、持有、不可剥夺、不可剥夺。
* [Java如何查看死锁？](https://blog.csdn.net/u014039577/article/details/52351626)
	* JConsole 可以识别死锁。
	
* [java多线程系列：死锁及检测](https://blog.csdn.net/bohu83/article/details/51135061)
	* jstack 可以显示死锁。
	
# 操作系统

## 计算机原理

* [《操作系统基础知识——操作系统的原理，类型和结构》](https://segmentfault.com/a/1190000003692840)

## CPU

### 多级缓存
典型的 CPU 有三级缓存，距离核心越近，速度越快，空间越小。L1 一般 32k，L2 一般 256k，L3 一般12M。内存速度需要200个 CPU 周期，CPU 缓存需要1个CPU周期。

* [《从Java视角理解CPU缓存和伪共享》](https://blog.csdn.net/zero__007/article/details/54089730)

## 进程

TODO

## 线程

* [《线程的生命周期及状态转换详解》](https://blog.csdn.net/asdf_1024/article/details/78978437)

## 协程

* [《终结python协程----从yield到actor模型的实现》](https://www.thinksaas.cn/group/topic/839375/)
	* 线程的调度是由操作系统负责，协程调度是程序自行负责
	* 与线程相比，协程减少了无畏的操作系统切换.
	* 实际上当遇到IO操作时做切换才更有意义，（因为IO操作不用占用CPU），如果没遇到IO操作，按照时间片切换.
	
## Linux

* [《Linux 命令大全》](http://www.runoob.com/linux/linux-command-manual.html)

# 设计模式

## 设计模式的六大原则
* [《设计模式的六大原则》](https://blog.csdn.net/q291611265/article/details/48465113)
	* 开闭原则：对扩展开放,对修改关闭，多使用抽象类和接口。
	* 里氏代换原则：基类可以被子类替换，使用抽象类继承,不使用具体类继承。
	* 依赖倒转原则：要依赖于抽象,不要依赖于具体，针对接口编程,不针对实现编程。
	* 接口隔离原则：使用多个隔离的接口,比使用单个接口好，建立最小的接口。
	* 迪米特法则：一个软件实体应当尽可能少地与其他实体发生相互作用，通过中间类建立联系。
	* 合成复用原则：尽量使用合成/聚合,而不是使用继承，尽量使用合成/聚合,而不是使用继承。

## 23种常见设计模式
* [《设计模式》](http://www.runoob.com/design-pattern/design-pattern-tutorial.html)
* [《23种设计模式全解析》](https://www.cnblogs.com/susanws/p/5510229.html)

## 应用场景
* [《细数JDK里的设计模式》](http://blog.jobbole.com/62314/)
	* 结构型模式：
		* 适配器：用来把一个接口转化成另一个接口，如 java.util.Arrays#asList()。
		* 桥接模式：这个模式将抽象和抽象操作的实现进行了解耦，这样使得抽象和实现可以独立地变化，如JDBC；
		* 组合模式：使得客户端看来单个对象和对象的组合是同等的。换句话说，某个类型的方法同时也接受自身类型作为参数，如 Map.putAll，List.addAll、Set.addAll。
		* 装饰者模式：动态的给一个对象附加额外的功能，这也是子类的一种替代方式，如 java.util.Collections#checkedList|Map|Set|SortedSet|SortedMap。
		* 享元模式：使用缓存来加速大量小对象的访问时间，如 valueOf(int)。
		* 代理模式：代理模式是用一个简单的对象来代替一个复杂的或者创建耗时的对象，如 java.lang.reflect.Proxy
		
	* 创建模式:
		* 抽象工厂模式：抽象工厂模式提供了一个协议来生成一系列的相关或者独立的对象，而不用指定具体对象的类型，如 java.util.Calendar#getInstance()。
		* 建造模式(Builder)：定义了一个新的类来构建另一个类的实例，以简化复杂对象的创建，如：java.lang.StringBuilder#append()。
		* 工厂方法：就是 **一个返*** 回具体对象的方法，而不是多个，如 java.lang.Object#toString()、java.lang.Class#newInstance()。
		* 原型模式：使得类的实例能够生成自身的拷贝、如：java.lang.Object#clone()。
		* 单例模式：全局只有一个实例，如 java.lang.Runtime#getRuntime()。
	* 行为模式：
		* 责任链模式：通过把请求从一个对象传递到链条中下一个对象的方式，直到请求被处理完毕，以实现对象间的解耦。如 javax.servlet.Filter#doFilter()。
		* 命令模式：将操作封装到对象内，以便存储，传递和返回，如：java.lang.Runnable。
		* 解释器模式：定义了一个语言的语法，然后解析相应语法的语句，如，java.text.Format，java.text.Normalizer。
		* 迭代器模式：提供一个一致的方法来顺序访问集合中的对象，如 java.util.Iterator。
		* 中介者模式：通过使用一个中间对象来进行消息分发以及减少类之间的直接依赖，java.lang.reflect.Method#invoke()。
		* 空对象模式：如 java.util.Collections#emptyList()。
		* 观察者模式：它使得一个对象可以灵活的将消息发送给感兴趣的对象，如 java.util.EventListener。
		* 模板方法模式：让子类可以重写方法的一部分，而不是整个重写，如 java.util.Collections#sort()。

* [《Spring-涉及到的设计模式汇总》](https://www.cnblogs.com/hwaggLee/p/4510687.html)
* [《Mybatis使用的设计模式》](https://blog.csdn.net/u012387062/article/details/54719114)

## 单例模式
* [《单例模式的三种实现 以及各自的优缺点》](https://blog.csdn.net/YECrazy/article/details/79481964)
* [《单例模式－－反射－－防止序列化破坏单例模式》](https://www.cnblogs.com/ttylinux/p/6498822.html)
	* 使用枚举类型。

## 责任链模式
TODO

## MVC
* [《MVC 模式》](http://www.runoob.com/design-pattern/mvc-pattern.html)
	* 模型(model)－视图(view)－控制器(controller) 

## IOC
* [《理解 IOC》](https://www.zhihu.com/question/23277575)
* [《IOC 的理解与解释》](https://www.cnblogs.com/NancyStartOnce/p/6813162.html)
	* 正向控制：传统通过new的方式。反向控制，通过容器注入对象。
	* 作用：用于模块解耦。
	* DI：Dependency Injection，即依赖注入，只关心资源使用，不关心资源来源。

## AOP

* [《轻松理解AOP(面向切面编程)》](https://my.oschina.net/yanquan345/blog/203415)
* [《Spring AOP详解》](https://www.cnblogs.com/hongwz/p/5764917.html)
* [《Spring AOP的实现原理》](http://www.importnew.com/24305.html)
	* Spring AOP使用的动态代理，主要有两种方式：JDK动态代理和CGLIB动态代理。
* [《Spring AOP 实现原理与 CGLIB 应用》](https://www.ibm.com/developerworks/cn/java/j-lo-springaopcglib/)
	* Spring AOP 框架对 AOP 代理类的处理原则是：如果目标对象的实现类实现了接口，Spring AOP 将会采用 JDK 动态代理来生成 AOP 代理类；如果目标对象的实现类没有实现接口，Spring AOP 将会采用 CGLIB 来生成 AOP 代理类 


## UML

* [《UML教程》](https://www.w3cschool.cn/uml_tutorial/)

## 微服务思想
* [《微服务架构设计》](https://www.cnblogs.com/wintersun/p/6219259.html)
* [《微服务架构技术栈选型手册》](http://www.infoq.com/cn/articles/micro-service-technology-stack)

### 康威定律
* [《微服务架构的理论基础 - 康威定律》](https://yq.aliyun.com/articles/8611)
	* 定律一：组织沟通方式会通过系统设计表达出来，就是说架构的布局和组织结构会有相似。
	* 定律二：时间再多一件事情也不可能做的完美，但总有时间做完一件事情。一口气吃不成胖子，先搞定能搞定的。
	* 定律三：线型系统和线型组织架构间有潜在的异质同态特性。种瓜得瓜，做独立自治的子系统减少沟通成本。
	* 定律四：大的系统组织总是比小系统更倾向于分解。合久必分，分而治之。

* [《微服务架构核⼼20讲》](https://static.geekbang.org/PDF-%E4%BF%AE%E6%94%B9%E7%89%88-%E6%9E%81%E5%AE%A2%E6%97%B6%E9%97%B4-%E5%9B%BE%E7%89%87-%E6%9D%A8%E6%B3%A2-%E5%BE%AE%E6%9C%8D%E5%8A%A1%E6%9E%B6%E6%9E%84.pdf)

# 运维 & 统计 & 技术支持 

## 常规监控

* [《腾讯业务系统监控的修炼之路》](https://blog.csdn.net/enweitech/article/details/77849205)
	* 监控的方式：主动、被动、旁路(比如舆情监控)
	* 监控类型： 基础监控、服务端监控、客户端监控、
	监控、用户端监控
	* 监控的目标：全、块、准
	* 核心指标：请求量、成功率、耗时

* [《开源还是商用？十大云运维监控工具横评》](https://www.oschina.net/news/67525/monitoring-tools)
	* Zabbix、Nagios、Ganglia、Zenoss、Open-falcon、监控宝、 360网站服务监控、阿里云监控、百度云观测、小蜜蜂网站监测等。

* [《监控报警系统搭建及二次开发经验》](http://developer.51cto.com/art/201612/525373.htm)

**命令行监控工具**

* [《常用命令行监控工具》](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/44-an-quan-yu-yun-wei/445-fu-wu-qi-zhuang-tai-jian-ce/4451-ming-ling-xing-gong-ju.html)
	* top、sar、tsar、nload

* [《20个命令行工具监控 Linux 系统性能》](http://blog.jobbole.com/96846/)

* [《JVM性能调优监控工具jps、jstack、jmap、jhat、jstat、hprof使用详解》](https://my.oschina.net/feichexia/blog/196575)

## APM

APM —  Application Performance Management

* [《Dapper，大规模分布式系统的跟踪系统》](http://bigbully.github.io/Dapper-translation/)

* [CNCF OpenTracing](http://opentracing.io)，[中文版](https://github.com/opentracing-contrib/opentracing-specification-zh)

* 主要开源软件，按字母排序
  * [Apache SkyWalking](https://github.com/apache/incubator-skywalking)
  * [CAT](https://github.com/dianping/cat)
  * [CNCF jaeger](https://github.com/jaegertracing/jaeger)
  * [Pinpoint](https://github.com/naver/pinpoint)
  * [Zipkin](https://github.com/openzipkin/zipkin)

* [《开源APM技术选型与实战》](http://www.infoq.com/cn/articles/apm-Pinpoint-practice)
	* 主要基于 Google的Dapper（大规模分布式系统的跟踪系统） 思想。
	


## 统计分析

* [《流量统计的基础：埋点》](https://zhuanlan.zhihu.com/p/25195217)
	* 常用指标：访问与访客、停留时长、跳出率、退出率、转化率、参与度

* [《APP埋点常用的统计工具、埋点目标和埋点内容》](http://www.25xt.com/company/17066.html)
	* 第三方统计：友盟、百度移动、魔方、App Annie、talking data、神策数据等。

* [《美团点评前端无痕埋点实践》](https://tech.meituan.com/mt-mobile-analytics-practice.html)
	* 所谓无痕、即通过可视化工具配置采集节点，在前端自动解析配置并上报埋点数据，而非硬编码。 


## 持续集成(CI/CD)

* [《持续集成是什么？》](http://www.ruanyifeng.com/blog/2015/09/continuous-integration.html)
* [《8个流行的持续集成工具》](https://www.testwo.com/article/1170)

### Jenkins

* [《使用Jenkins进行持续集成》](https://www.liaoxuefeng.com/article/001463233913442cdb2d1bd1b1b42e3b0b29eb1ba736c5e000)

### 环境分离

开发、测试、生成环境分离。

* [《开发环境、生产环境、测试环境的基本理解和区》](https://my.oschina.net/sancuo/blog/214904)

## 自动化运维

### Ansible
* [《Ansible中文权威指南》](http://www.ansible.com.cn/)
* [《Ansible基础配置和企业级项目实用案例》](https://www.cnblogs.com/heiye123/articles/7855890.html)

### puppet
* [《自动化运维工具——puppet详解》](https://www.cnblogs.com/keerya/p/8040071.html)

### chef
* [《Chef 的安装与使用》](https://www.ibm.com/developerworks/cn/cloud/library/1407_caomd_chef/)

## 测试

### TDD 理论

* [《深度解读 - TDD（测试驱动开发）》](https://www.jianshu.com/p/62f16cd4fef3)
	* 基于测试用例编码功能代码，XP（Extreme Programming）的核心实践.
	* 好处：一次关注一个点，降低思维负担；迎接需求变化或改善代码的设计；提前澄清需求；快速反馈； 

### 单元测试

* [《Java单元测试之JUnit篇》](https://www.cnblogs.com/happyzm/p/6482886.html)
* [《JUnit 4 与 TestNG 对比》](https://blog.csdn.net/hotdust/article/details/53406086)
	* TestNG 覆盖 JUnit 功能，适用于更复杂的场景。 
* [《单元测试主要的测试功能点》](https://blog.csdn.net/wqetfg/article/details/50900512)
	* 模块接口测试、局部数据结构测试、路径测试 、错误处理测试、边界条件测试 。 

### 压力测试

* [《Apache ab 测试使用指南》](https://blog.csdn.net/blueheart20/article/details/52170790)
* [《大型网站压力测试及优化方案》](https://www.cnblogs.com/binyue/p/6141088.html)
* [《10大主流压力/负载/性能测试工具推荐》](http://news.chinabyte.com/466/14126966.shtml)
* [《真实流量压测工具 tcpcopy应用浅析》](http://quentinxxz.iteye.com/blog/2249799)
* [《nGrinder 简易使用教程》](https://www.cnblogs.com/jwentest/p/7136727.html)


### 全链路压测
* [《京东618：升级全链路压测方案，打造军演机器人ForceBot》](http://www.infoq.com/cn/articles/jd-618-upgrade-full-link-voltage-test-program-forcebot)
* [《饿了么全链路压测的探索与实践》](https://zhuanlan.zhihu.com/p/30306892)
* [《四大语言，八大框架｜滴滴全链路压测解决之道》](https://zhuanlan.zhihu.com/p/28355759)
* [《全链路压测经验》](https://www.jianshu.com/p/27060fd61f72)


### A/B 、灰度、蓝绿测试

* [《技术干货 | AB 测试和灰度发布探索及实践》](https://testerhome.com/topics/11165)
* [《nginx 根据IP 进行灰度发布》](http://blog.51cto.com/purplegrape/1403123)

* [《蓝绿部署、A/B 测试以及灰度发布》](https://www.v2ex.com/t/344341)

## 虚拟化

* [《VPS的三种虚拟技术OpenVZ、Xen、KVM优缺点比较》](https://blog.csdn.net/enweitech/article/details/52910082)

### KVM
* [《KVM详解，太详细太深入了，经典》](http://blog.chinaunix.net/uid-20201831-id-5775661.html)
* [《【图文】KVM 虚拟机安装详解》](https://www.coderxing.com/kvm-install.html)

### Xen
* [《Xen虚拟化基本原理详解》](https://www.cnblogs.com/sddai/p/5931201.html)

### OpenVZ
* [《开源Linux容器 OpenVZ 快速上手指南》](https://blog.csdn.net/longerzone/article/details/44829255)

## 容器技术

### Docker
* [《几张图帮你理解 docker 基本原理及快速入门》](https://www.cnblogs.com/SzeCheng/p/6822905.html)
* [《Docker 核心技术与实现原理》](https://draveness.me/docker)
* [《Docker 教程》](http://www.runoob.com/docker/docker-tutorial.html)

## 云技术

### OpenStack
* [《OpenStack构架知识梳理》](https://www.cnblogs.com/klb561/p/8660264.html)

## DevOps
* [《一分钟告诉你究竟DevOps是什么鬼？》](https://www.cnblogs.com/jetzhang/p/6068773.html)
* [《DevOps详解》](http://www.infoq.com/cn/articles/detail-analysis-of-devops)

## 文档管理

* [Confluence-收费文档管理系统](http://www.confluence.cn/)
* GitLab?
* Wiki

# 中间件

## Web Server

### Nginx
* [《Ngnix的基本学习-多进程和Apache的比较》](https://blog.csdn.net/qq_25797077/article/details/52200722)
	* Nginx 通过异步非阻塞的事件处理机制实现高并发。Apache 每个请求独占一个线程，非常消耗系统资源。
	* 事件驱动适合于IO密集型服务(Nginx)，多进程或线程适合于CPU密集型服务(Apache)，所以Nginx适合做反向代理，而非web服务器使用。  

* [《nginx与Apache的对比以及优缺点》](https://www.cnblogs.com/cunkouzh/p/5410154.html)
	* nginx只适合静态和反向代理，不适合处理动态请求。

### OpenResty
* [官方网站](http://openresty.org/cn/)
* [《浅谈 OpenResty》](http://www.linkedkeeper.com/detail/blog.action?bid=1034)
	* 通过 Lua 模块可以在Nginx上进行开发。 

### Apache Httpd
* [官方网站](http://httpd.apache.org/)

### Tomcat

#### 架构原理
* [《TOMCAT原理详解及请求过程》](https://www.cnblogs.com/hggen/p/6264475.html)
* [《Tomcat服务器原理详解》](https://www.cnblogs.com/crazylqy/p/4706223.html)
* [《Tomcat 系统架构与设计模式,第 1 部分: 工作原理》](https://www.ibm.com/developerworks/cn/java/j-lo-tomcat1/)

* [《四张图带你了解Tomcat系统架构》](https://blog.csdn.net/xlgen157387/article/details/79006434)

* [《JBoss vs. Tomcat: Choosing A Java Application Server》](https://www.futurehosting.com/blog/jboss-vs-tomcat-choosing-a-java-application-server/)
	* Tomcat 是轻量级的 Serverlet 容器，没有实现全部 JEE 特性（比如持久化和事务处理），但可以通过其他组件代替，比如Srping。
	* Jboss 实现全部了JEE特性，软件开源免费、文档收费。

#### 调优方案

* [《Tomcat 调优方案》](https://www.cnblogs.com/sunfenqing/p/7339058.html)
	* 启动NIO模式（或者APR）；调整线程池；禁用AJP连接器（Nginx+tomcat的架构，不需要AJP）； 

* [《tomcat http协议与ajp协议》](http://blog.chinaunix.net/uid-20662363-id-3012760.html)
* [《AJP与HTTP比较和分析》](http://dmouse.iteye.com/blog/1354527)
	* AJP 协议（8009端口）用于降低和前端Server（如Apache，而且需要支持AJP协议）的连接数(前端)，通过长连接提高性能。
	* 并发高时，AJP协议优于HTTP协议。

### Jetty
* [《Jetty 的工作原理以及与 Tomcat 的比较》](https://www.ibm.com/developerworks/cn/java/j-lo-jetty/)
* [《jetty和tomcat优势比较》](https://blog.csdn.net/doutao6677/article/details/51957288)
	* 架构比较:Jetty的架构比Tomcat的更为简单。
	* 性能比较：Jetty和Tomcat性能方面差异不大，Jetty默认采用NIO结束在处理I/O请求上更占优势，Tomcat默认采用BIO处理I/O请求，Tomcat适合处理少数非常繁忙的链接，处理静态资源时性能较差。
	* 其他方面：Jetty的应用更加快速，修改简单，对新的Servlet规范的支持较好;Tomcat 对JEE和Servlet 支持更加全面。 



## 缓存

* [《缓存失效策略（FIFO 、LRU、LFU三种算法的区别）》](https://blog.csdn.net/clementad/article/details/48229243)

### 本地缓存

* [《HashMap本地缓存》](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/421-ying-yong-ceng-ben-di-huan-cun/4211.html)

* [《EhCache本地缓存》](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/421-ying-yong-ceng-ben-di-huan-cun/4212-ehcache.html)
	* 堆内、堆外、磁盘三级缓存。
	* 可按照缓存空间容量进行设置。
	* 按照时间、次数等过期策略。

* [《Guava Cache》](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/421-ying-yong-ceng-ben-di-huan-cun/4213-guava-cache.html)
	* 简单轻量、无堆外、磁盘缓存。


* [《Nginx本地缓存》](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/422-fu-wu-duan-ben-di-huan-cun/nginx-ben-di-huan-cun.html)

* [《Pagespeed—懒人工具，服务器端加速》](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/422-fu-wu-duan-ben-di-huan-cun/4222-pagespeed.html)

## 客户端缓存

* [《浏览器端缓存》](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/423-ke-hu-duan-huan-cun.html)
	* 主要是利用 Cache-Control 参数。

* [《H5 和移动端 WebView 缓存机制解析与实战》](https://mp.weixin.qq.com/s/qHm_dJBhVbv0pJs8Crp77w)

## 服务端缓存
### Memcached
* [《Memcached 教程》](http://www.runoob.com/Memcached/Memcached-tutorial.html)
* [《深入理解Memcached原理》](https://blog.csdn.net/chenleixing/article/details/47035453)
	* 采用多路复用技术提高并发性。
	* slab分配算法： memcached给Slab分配内存空间，默认是1MB。分配给Slab之后 把slab的切分成大小相同的chunk，Chunk是用于缓存记录的内存空间，Chunk 的大小默认按照1.25倍的速度递增。好处是不会频繁申请内存，提高IO效率，坏处是会有一定的内存浪费。
* [《Memcached软件工作原理》](https://www.jianshu.com/p/36e5cd400580)
* [《Memcache技术分享：介绍、使用、存储、算法、优化、命中率》](http://zhihuzeye.com/
