**整理**了一波学到头秃的 Java 入坑笔记，劝退一波，别搞后端了，转算法去吧！

| ![image-20200317230215494](assets/image-20200317230215494.png) | ![image-20200317230339393](assets/image-20200317230339393.png) | ![image-20200318080237857](assets/image-20200318080237857.png) | ![image-20200318080416391](assets/image-20200318080416391.png) | <img src="assets/image-20200318080710502.png" alt="image-20200318080710502" style="zoom:90%;" /> | ![image-20200318080804629](assets/image-20200318080804629.png) | ![image-20200318080907764](assets/image-20200318080907764.png) | ![image-20200318081002237](assets/image-20200318081002237.png) | ![image-20200318081120263](assets/image-20200318081120263.png) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|                           **Java**                           |                         **设计模式**                         |                           **算法**                           |                           **网络**                           |                         **操作系统**                         |                          **数据库**                          |                          **Spring**                          |                          **分布式**                          |                          **大数据**                          |



### 目录

----

#### Java

##### 1. 基础

- [x] **基础**：数据与程序结构、关键字等。
- [x] **对象与类**：继承、接口、抽象类、内部类、枚举、常用类、常用接口、注解等。
- [x] **异常**：异常体系等。
- [x] **泛型**：用法、类型参数、通配符等。

##### 2. 集合与容器

- [x] **集合容器类**：队列、列表、栈、Map、Set 等结构，含 ArrayList、LinkedList、ArrayDeque、PriorityQueue、HashMap、LinkedHashMap、TreeMap 及并发容器类等。

##### 3. 并发

- [x] **并发**：线程基础、JMM、AQS、CAS、锁与线程安全（Synchronized、ReentrantLock）、JUC、线程池、定时任务、TreadLocal 等。

##### 4. Java8/IO/其他

- [ ] **Java8**：Lambda、流 Stream 等。
- [x] **IO**：文件操作、IO流、网络操作等（NIO 放到了 Netty 部分）。
- [ ] **其他**：Java性能问题定位、必备技能等。

----

#### 数据结构与算法

#### 网络

- [x] **网络基础与物理层**：网络分层、物理层等。
- [x] **数据链路层**：点对点信道、广播信道、PPP 协议、以太网、局域网等。
- [x] **网络层**：IP 协议栈、ICMP协议、路由选择协议（RIP、OSPF、BGP协议等）、IPV6、VPN 等。
- [x] **传输层**：UDP、TCP、ARQ协议、TCP 可靠传输、TCP连接释放等。
- [x] **应用层**：DNS、FTP、DHCP、邮件协议等。
- [x] **网络安全**：密码体制、数字签名、鉴别、安全协议、Web攻击技术（CSRF、XSS、SQL注入、DOS等）等。
- [x] **HTTP**：报文结构、HTTP方法、HTTP状态码、HTTP首部、HTTP应用等。
- [x] **HTTPS**：加密、认证、完整性保护、TLS等。

----

#### 操作系统

##### 1. 操作系统理论

- [x] **操作系统概述**：操作系统基本特征、基本功能、系统调用、系统中断等。
- [x] **进程管理**：进程与线程、进程描述符、进程状态、进程调度算法、进程同步、线程同步、进程间通信、死锁等。
- [x] **内存管理**：内存管理机制、虚拟地址、虚拟内存、分页、分段等。
- [x] **IO管理与磁盘调度**：磁盘结构、磁盘调度算法等。
- [x] **编译原理**：编译系统、目标文件、动态链接、静态链接等。
- [x] **IO模型**：五种 IO 模型、IO 多路复用实现等。

##### 2. Linux

- [x] **Linux基础**：磁盘接口、分区表、开机监测程序等。
- [x] **Linux文件与文件系统**：文件系统、目录、文件、文件与目录操作命令等。
- [x] **Linux Shell编程**：基础、变量操作、数据流重定向、提取与转换、排序指令、测试指令等。
- [x] **Linux系统管理**：Linux启动、进程管理、系统资源管理、网络管理、定时任务等。

#### 数据库

##### 1. 数据库系统原理

- [x] **基础**：函数依赖、数据库范式、ER图等。

##### 2. MySQL

- [x] **基础**：基础、数据类型、运算符、DDL数据定义语言、DQL数据查询语言（基础查询、条件查询、查询排序、常见函数、分组查询、连接查询、子查询、分页查询、组合查询等）、DML数据操作语言（增加数据、删除数据、修改数据等）等。
- [x] **高级特性**：MySQL函数、存储过程、视图、触发器等。
- [x] **系统原理**：MySQL架构、存储引擎、SQL语句执行等。
- [x] **索引**：概述、B+Tree、索引与存储引擎实现、索引优化、索引设计等。
- [x] **事务与并发控制**：ACID、并发一致性问题、锁机制、隔离级别、MVCC等。
- [x] **优化**：查询优化、大表优化。
- [x] **架构设计**：切分与分库分表、主从复制与读写分离。
- [x] **设计规范**：命名规范、设计规范、字段设计规范、SQL开发规范。
- [x] **LeetCode**数据库题解

##### 3. 非关系型数据库

- [ ] MongoDB 相关内容

#### JVM

- [x] **JVM内存区域与对象解析**：运行时数据区、对象创建过程、对象内存布局等。
- [x] **内存分配与垃圾收集**：堆结构、内存分配策略、引用类型、垃圾回收算法、垃圾收集器、内存泄漏与内存溢出等。
- [x] **JVM监控与故障处理工具**：jsp、jstat、jinfo、jmap、jstack、JConsole、VisualVM、堆转储、GC日志等。
- [x] **类文件结构与类加载机制**：Class类文件结构、类的生命周期、类初始化时机、类加载器等。
- [x] **虚拟机方法调用与指令执行引擎**：字节码指令、运行时栈帧结构、方法调用等。
- [x] **程序编译与代码优化**：编译期优化、运行期优化。
- [x] **虚拟机调优及参数总结**：GC调优、JVM参数总结。
- [x] **大白话认识虚拟机**

#### 设计模式

- [x] **面向对象思想**：封装、继承、多态等、设计原则（SOLID）等。
- [x] **UML类图**：类图结构、类之间的关系等（继承、实现、组合、聚合、关联、依赖）。
- [x] **设计模式之创建型**：单例模式、简单工厂模式、工厂方法模式、抽象工厂模式、生成器模式、原型模式等。
- [x] **设计模式之行为型**：责任链模式、解释器模式、迭代器模式、中介者模式、命令模式、备忘录模式、观察者模式、状态模式、策略模式、模板方法模式、访问者模式等。
- [x] **设计模式之结构型**：适配器模式、桥接模式、组合模式、装饰器模式、外观模式、享元模式、代理模式等。

#### Spring

- [x] **J2EE与Web基础**：JSP、Servlet等。
- [x] **Spring基础**：基础、Spring EL 等。
- [x] **Spring IOC**：控制反转、Bean作用域、依赖注入、Bean生命周期、BeanFactory等。
- [x] **AOP**：基础、Spring AOP、AspectJ AOP。
- [x] **Spring事务**：事务管理方式、事务管理接口、事务属性详解等。
- [x] **Spring MVC**：基础、工作流程、重要组件。
- [x] **Spring Boot基础与原理**：基础、配置文件、自动配置原理等。
- [x] **Spring Boot应用整合**：数据整合、日志、调度、热部署、监控、邮件任务等。
- [x] **Spring注解总结**
- [x] **Spring中的设计模式**
- [x] **RESTful API设计**
- [x] **Spring IOC源码分析**

#### 缓存

- [x] **缓存理论**：缓存基础、缓存问题（缓存穿透、缓存雪崩、缓存无底洞、缓存一致性问题）等。
- [x] **Redis基础**：基础、基本命令与数据类型、底层数据结构、Redis高级功能、其他等。
- [x] **Redis持久化**：RDB持久化、AOF持久化等。
- [x] **Redis主从复制**：基础、复制原理、运维问题等。
- [x] **Redis哨兵**：架构基础、实现原理等。
- [x] **Redis Cluster**：数据分布理论、集群搭建、通信机制、集群伸缩、请求路由、故障转移、集群运维等。
- [x] **Redis内存、阻塞与运维**：内存消耗分析、内存管理、内存优化、阻塞分析、Redis运维等。

#### ORM

- [x] **MyBatis**：JDBC、MyBatis框架设计、缓存等。

#### 分布式与系统设计

- [x] **分布式系统设计**：基础、CAP、BASE、负载均衡、分布式锁、分布式ID、一致性算法、分布式事务等。
- [x] **系统认证与授权**：Cookie与Session、Token与JWT、OAuth2、单点登录SSO、分布式Session等。
- [x] **网关**：网关设计、大厂网关总结等。
- [x] **Zookeeper**：概述、Znode、客户端、集群、ZAB协议、Zookeeper使用场景等。
- [x] **限流**：基础、限流算法（固定窗口、滑动窗口、漏桶算法、令牌桶算法）等。
- [ ] **Nginx**

#### 消息队列

- [x] **消息队列概述**：消息模型、使用场景、问题、JMS与AMQP、消息队列对比等。
- [x] **RabbitMQ**：基础、RabbitMQ 架构。
- [x] **RocketMQ**：消息模型、架构、消费问题、刷盘机制等。
- [x] **Kafka**：架构模型、存储实现、生产者、消费者、可靠性、Zookeeper与Kafka、Kafka事务、各种API等。

#### RPC

- [x] **RPC概述**：基本原理、常见RPC框架。
- [x] **Dubbo**：架构、负载均衡、通信协议、集群容错策略、SPI等。

#### Netty

- [x] **Java网络IO**：BIO、NIO、AIO等。
- [x] **Netty核心功能与线程模型**：基础、线程模型、模块与组件、ByteBuf、编解码、粘包拆包、心跳机制、零拷贝等。
- [x] **Netty应用**：WebSocket弹幕系统、Dubbo、HTTP服务器等。

#### 搜索引擎





### 备注

本项目 Markdown 文件均由 **Typora** 编辑器整理，且使用了高亮语法（标识重点），Typora 需要打开高亮开关，看起来才舒服。如下图。

![image-20191205192232182](assets/image-20191205192232182-1594213823681.png)

针对部分内容有相应图示，**架构图**源文件在各种小章节的文件夹之下，可使用如下软件打开：

- 桌面版：https://github.com/jgraph/drawio-desktop

- 在线版：https://www.draw.io/





### 参考资料

由于是站在巨人的肩膀上前进，**==侵删==**。

##### 1. 参考书籍

- 《Java 核心技术卷》 凯S.霍斯特曼
- BruceEckel. Java 编程思想: 第 4 版 [M]. 机械工业出版社, 2007
- 《深入理解 Java 虚拟机第二版》 周志明
- 《计算机网络第七版》 谢希仁

##### 2. 参考项目

参考了不少优秀的项目啊（大佬们是真的![img](assets/0A97B0EE.png)）。

- https://github.com/CyC2018/CS-Notes



**欢迎三连**~

<img src="../JavaNotes/assets/image-20200318081422659.png" alt="image-20200318081422659" style="zoom:35%;" />



 