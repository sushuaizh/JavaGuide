# JavaGuide

一份面向 Java 后端开发者的学习与面试指南，覆盖 Java 基础、并发、JVM、数据库、系统设计等内容。

GitHub 访问较慢时，可改用 [Gitee](https://gitee.com/SnailClimb/JavaGuide) 或 [在线阅读](https://snailclimb.gitee.io/javaguide)。

<p align="center">
  <a href="https://github.com/Snailclimb/JavaGuide" target="_blank">
    <img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-3/logo - 副本.png" alt="JavaGuide" />
  </a>
</p>

<p align="center">
  <a href="https://snailclimb.gitee.io/javaguide"><img src="https://img.shields.io/badge/阅读-read-brightgreen.svg" alt="阅读"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-JavaGuide-lightgrey.svg" alt="公众号"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/PDF-Java面试突击-important.svg" alt="Java面试突击"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/support-投稿-critical.svg" alt="投稿"></a>
  <a href="https://xiaozhuanlan.com/javainterview?rel=javaguide"><img src="https://img.shields.io/badge/Java-面试指南-important" alt="Java面试指南"></a>
</p>

## 交流与资源

1. [公众号 — JavaGuide](#公众号)：最新原创文章，可领取本文档配套的《Java 面试突击》以及 Java 工程师学习资源。
2. [微信](#联系我)：交流、答疑（账号接近上限）。
3. [B 站 - Guide哥](https://space.bilibili.com/504390397)：干货与生活向视频。
4. [知识星球 — JavaGuide 读者圈](https://javaguide.cn/2019/01/02/chat/%E5%81%9A%E4%BA%86%E4%B8%80%E4%B8%AA%E5%BE%88%E4%B9%85%E6%B2%A1%E6%95%A2%E5%81%9A%E7%9A%84%E4%BA%8B%E6%83%85/)

<h3 align="center">Sponsor</h3>
<p align="center">
  <a href="https://mp.weixin.qq.com/s/li9_YXNVxan6Qgt3Q9FYqA">
    <img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-7/WechatIMG1.png" alt="Sponsor" style="margin: 0 auto;width:400px" />
  </a>
</p>

## 目录

- [Java](#java)
  - [基础](#基础)
  - [容器](#容器)
  - [并发](#并发)
  - [JVM](#jvm)
  - [I/O](#io)
  - [Java 8](#java-8)
  - [编程规范](#编程规范)
- [网络](#网络)
- [操作系统](#操作系统)
- [数据结构与算法](#数据结构与算法)
- [数据库](#数据库)
  - [MySQL](#mysql)
  - [Redis](#redis)
- [系统设计](#系统设计)
  - [设计模式](#设计模式)
  - [常用框架](#常用框架)
  - [认证授权](#认证授权)
  - [分布式](#分布式)
  - [大型网站架构](#大型网站架构)
  - [微服务](#微服务)
- [面试指南](#面试指南)
- [Java 学习常见问题](#java-学习常见问题)
- [工具](#工具)
- [资源](#资源)
- [待办](#待办)
- [说明](#说明)

## Java

### 基础

**系统总结：**

1. **[Java 基础知识](docs/java/Java基础知识.md)**
2. **[Java 基础知识疑难点 / 易错点](docs/java/Java疑难点.md)**
3. [【加餐】一些重要的 Java 程序设计题](docs/java/Java程序设计题.md)
4. [【选看】J2EE 基础知识](docs/java/J2EE基础知识.md)

**重要知识点：**

1. [枚举](docs/java/basic/用好Java中的枚举真的没有那么简单.md)
2. [Java 常见关键字：final、static、this、super](docs/java/basic/final、static、this、super.md)
3. [反射机制及应用场景](docs/java/basic/reflection.md)
4. [Collections / Arrays 常见方法](docs/java/basic/Arrays,CollectionsCommonMethods.md)

**其他：**

- [JAD 反编译](docs/java/JAD反编译tricks.md)

### 容器

1. **[Java 容器常见面试题 / 知识点总结](docs/java/collection/Java集合框架常见面试题.md)**
2. [ArrayList 源码](docs/java/collection/ArrayList.md)
3. [ArrayList 扩容](docs/java/collection/ArrayList-Grow.md)
4. [LinkedList 源码](docs/java/collection/LinkedList.md)
5. [HashMap（JDK 1.8）源码](docs/java/collection/HashMap.md)

### 并发

**面试题总结：**

1. **[Java 并发基础常见面试题总结](docs/java/Multithread/JavaConcurrencyBasicsCommonInterviewQuestionsSummary.md)**
2. **[Java 并发进阶常见面试题总结](docs/java/Multithread/JavaConcurrencyAdvancedCommonInterviewQuestions.md)**

**必备知识点：**

1. [并发编程基础知识](docs/java/Multithread/并发编程基础知识.md)
2. [synchronized](docs/java/Multithread/synchronized.md)
3. [并发容器总结](docs/java/Multithread/并发容器总结.md)
4. **[Java 线程池学习总结](docs/java/Multithread/java线程池学习总结.md)**（示例代码见 [`code/java/ThreadPoolExecutorDemo`](code/java/ThreadPoolExecutorDemo)）
5. [ThreadLocal](docs/java/Multithread/ThreadLocal.md)
6. [乐观锁与悲观锁](docs/essential-content-for-interview/面试必备之乐观锁与悲观锁.md)
7. [JUC 中的 Atomic 原子类总结](docs/java/Multithread/Atomic.md)
8. [AQS 原理以及 AQS 同步组件总结](docs/java/Multithread/AQS.md)
9. [多线程系列文章](docs/java/多线程系列.md)

### JVM

1. [JVM 知识点汇总](docs/java/jvm/jvm%20知识点汇总.md)
2. **[Java 内存区域](docs/java/jvm/Java内存区域.md)**
3. **[JVM 垃圾回收](docs/java/jvm/JVM垃圾回收.md)**
4. [JDK 监控和故障处理工具](docs/java/jvm/JDK监控和故障处理工具总结.md)
5. [类文件结构](docs/java/jvm/类文件结构.md)
6. **[类加载过程](docs/java/jvm/类加载过程.md)**
7. [类加载器](docs/java/jvm/类加载器.md)
8. [【待完成】最重要的 JVM 参数指南](docs/java/jvm/最重要的JVM参数指南.md)
9. [JVM 常用参数和 GC 调优策略](docs/java/jvm/GC调优参数.md)
10. **[【加餐】大白话带你认识 JVM](docs/java/jvm/%5B加餐%5D大白话带你认识JVM.md)**

### I/O

1. **[BIO、NIO、AIO 总结](docs/java/BIO-NIO-AIO.md)**
2. [Java IO 与 NIO](docs/java/Java%20IO与NIO.md)

### Java 8

1. [Java 8 新特性总结](docs/java/What's%20New%20in%20JDK8/Java8Tutorial.md)
2. [Java 8 学习资源推荐](docs/java/What's%20New%20in%20JDK8/Java8教程推荐.md)
3. [Java 8 forEach 指南](docs/java/What's%20New%20in%20JDK8/Java8foreach指南.md)

### 编程规范

- **[Java 编程规范以及优雅 Java 代码实践总结](docs/java/Java编程规范.md)**

## 网络

1. [计算机网络常见面试题](docs/network/计算机网络.md)
2. [计算机网络基础知识总结](docs/network/干货：计算机网络知识总结.md)
3. [HTTPS 中的 TLS](docs/network/HTTPS中的TLS.md)

## 操作系统

### Linux

- [后端程序员必备的 Linux 基础知识](docs/operating-system/后端程序员必备的Linux基础知识.md)
- [Shell 编程入门](docs/operating-system/Shell.md)

## 数据结构与算法

### 数据结构

- [数据结构知识学习与面试](docs/dataStructures-algorithms/数据结构.md)
- [布隆过滤器](docs/dataStructures-algorithms/data-structure/bloom-filter.md)

### 算法

- [算法学习资源推荐](docs/dataStructures-algorithms/算法学习资源推荐.md)
- [几道常见的字符串算法题总结](docs/dataStructures-algorithms/几道常见的子符串算法题.md)
- [几道常见的链表算法题总结](docs/dataStructures-algorithms/几道常见的链表算法题.md)
- [剑指 Offer 部分编程题](docs/dataStructures-algorithms/剑指offer部分编程题.md)
- [公司真题](docs/dataStructures-algorithms/公司真题.md)
- [回溯算法经典案例：N 皇后问题](docs/dataStructures-algorithms/Backtracking-NQueens.md)

## 数据库

### MySQL

1. **[MySQL / 数据库知识点总结](docs/database/MySQL.md)**
2. **[阿里巴巴开发手册数据库部分的一些最佳实践](docs/database/阿里巴巴开发手册数据库部分的一些最佳实践.md)**
3. **[一千行 MySQL 学习笔记](docs/database/一千行MySQL命令.md)**
4. [MySQL 高性能优化规范建议](docs/database/MySQL高性能优化规范建议.md)
5. [数据库索引总结](docs/database/MySQL%20Index.md)
6. [事务隔离级别（图文详解）](docs/database/事务隔离级别%28图文详解%29.md)
7. [一条 SQL 语句在 MySQL 中如何执行](docs/database/一条sql语句在mysql中如何执行的.md)
8. [数据库连接池](docs/database/数据库连接池.md)

### Redis

- [Redis 总结](docs/database/Redis/Redis.md)
- [Redis 持久化](docs/database/Redis/Redis持久化.md)
- [Redlock 分布式锁](docs/database/Redis/Redlock分布式锁.md)
- [如何做可靠的分布式锁，Redlock 真的可行么](docs/database/Redis/如何做可靠的分布式锁，Redlock真的可行么.md)
- [几种常见的 Redis 集群以及使用场景](docs/database/Redis/redis集群以及应用场景.md)

## 系统设计

### 设计模式

- [设计模式系列文章](docs/system-design/设计模式.md)

### 常用框架

#### Spring

1. [Spring 学习与面试](docs/system-design/framework/spring/Spring.md)
2. **[Spring 常见问题总结](docs/system-design/framework/spring/SpringInterviewQuestions.md)**
3. [Spring 中 Bean 的作用域与生命周期](docs/system-design/framework/spring/SpringBean.md)
4. [SpringMVC 工作原理详解](docs/system-design/framework/spring/SpringMVC-Principle.md)
5. [Spring 中都用到了哪些设计模式？](docs/system-design/framework/spring/Spring-Design-Patterns.md)

#### Spring Boot

- **[Spring Boot 指南 / 常见面试题总结](https://github.com/Snailclimb/springboot-guide)**

#### MyBatis

- [MyBatis 常见面试题总结](docs/system-design/framework/mybatis/mybatis-interview.md)

### 认证授权

**[认证授权基础：Authentication、Authorization 以及 Cookie、Session、Token、OAuth 2、SSO](docs/system-design/authority-certification/basis-of-authority-certification.md)**

#### JWT

- **[JWT 优缺点分析以及常见问题解决方案](docs/system-design/authority-certification/JWT-advantages-and-disadvantages.md)**
- **[适合初学者入门的 Spring Security With JWT Demo](https://github.com/Snailclimb/spring-security-jwt-guide)**

#### SSO（单点登录）

SSO（Single Sign On）指用户登录多个子系统中的一个后，即可访问与其相关的其他系统。例如登录京东金融后，同时也登录了京东超市、京东家电等子系统。

- **[SSO 单点登录看这篇就够了](docs/system-design/authority-certification/sso.md)**

### 分布式

[分布式相关概念入门](docs/system-design/website-architecture/分布式.md)

#### RPC

让调用远程服务像调用本地方法那样简单。

- [Dubbo 总结：关于 Dubbo 的重要知识点](docs/system-design/data-communication/dubbo.md)
- [服务之间的调用为什么不直接用 HTTP 而用 RPC？](docs/system-design/data-communication/why-use-rpc.md)

#### 消息队列

消息队列在分布式系统中主要用于解耦和削峰。相关阅读：**[消息队列总结](docs/system-design/data-communication/message-queue.md)**。

**RabbitMQ**

- [RabbitMQ 入门](docs/system-design/data-communication/rabbitmq.md)

**RocketMQ**

- [RocketMQ 入门](docs/system-design/data-communication/RocketMQ.md)
- [RocketMQ 的几个简单问题与答案](docs/system-design/data-communication/RocketMQ-Questions.md)

**Kafka**

- **[Kafka 入门 + Spring Boot 整合 Kafka 系列](https://github.com/Snailclimb/springboot-kafka)**
- [Kafka 系统设计开篇：面试看这篇就够了](docs/system-design/data-communication/Kafka系统设计开篇-面试看这篇就够了.md)
- [【加餐】Kafka 入门看这一篇就够了](docs/system-design/data-communication/Kafka入门看这一篇就够了.md)

#### API 网关

网关主要用于请求转发、安全认证、协议转换、容灾。

- [浅析如何设计一个亿级网关（API Gateway）](docs/system-design/micro-service/API网关.md)

#### 唯一 ID 生成

- [分布式 ID 生成方案总结](docs/system-design/micro-service/分布式id生成方案总结.md)

#### ZooKeeper

> 前两篇文章可能有内容重合，建议都看一遍。

1. [【入门】ZooKeeper 相关概念总结](docs/system-design/framework/ZooKeeper.md)
2. [【进阶】ZooKeeper 原理简单入门](docs/system-design/framework/ZooKeeper-plus.md)
3. [【拓展】ZooKeeper 数据模型和常见命令](docs/system-design/framework/ZooKeeper数据模型和常见命令.md)

### 大型网站架构

- [8 张图读懂大型网站技术架构](docs/system-design/website-architecture/8%20张图读懂大型网站技术架构.md)
- [关于大型网站系统架构你不得不懂的 10 个问题](docs/system-design/website-architecture/关于大型网站系统架构你不得不懂的10个问题.md)

#### 性能测试

- [后端程序员也要懂的性能测试知识](https://articles.zsxq.com/id_lwl39teglv3d.html)（知识星球）

#### 高可用

高可用描述的是一个系统在大部分时间都可用、能为我们提供服务。即使发生硬件故障或系统升级，服务仍然可用。相关阅读：**[如何设计一个高可用系统？要考虑哪些地方？](docs/system-design/website-architecture/如何设计一个高可用系统？要考虑哪些地方？.md)**。

### 微服务

#### Spring Cloud

- [大白话入门 Spring Cloud](docs/system-design/micro-service/spring-cloud.md)

## 面试指南

### 备战面试

1. **[程序员的简历就该这样写](docs/essential-content-for-interview/PreparingForInterview/程序员的简历之道.md)**
2. [手把手教你用 Markdown 写一份高质量的简历](docs/essential-content-for-interview/手把手教你用Markdown写一份高质量的简历.md)
3. [简历模板](docs/essential-content-for-interview/简历模板.md)
4. **[初出茅庐的程序员该如何准备面试？](docs/essential-content-for-interview/PreparingForInterview/interviewPrepare.md)**
5. **[7 个大部分程序员在面试前很关心的问题](docs/essential-content-for-interview/PreparingForInterview/JavaProgrammerNeedKnow.md)**
6. **[GitHub 上开源的 Java 面试 / 学习相关仓库推荐](docs/essential-content-for-interview/PreparingForInterview/JavaInterviewLibrary.md)**
7. **[如果面试官问你「你有什么问题问我吗？」时，你该如何回答](docs/essential-content-for-interview/PreparingForInterview/面试官-你有什么问题要问我.md)**
8. [应届生面试最爱问的几道 Java 基础问题](docs/essential-content-for-interview/PreparingForInterview/应届生面试最爱问的几道Java基础问题.md)
9. **[美团面试常见问题总结（附详解答案）](docs/essential-content-for-interview/PreparingForInterview/美团面试常见问题总结.md)**
10. **[一些刁难的面试问题总结](https://xiaozhuanlan.com/topic/9056431872)**

### 真实面试经历分析

- **[我和阿里面试官的一次「邂逅」（附问题详解）](docs/essential-content-for-interview/real-interview-experience-analysis/alibaba-1.md)**

### 面经

- [5 面阿里，终获 offer（2018 年秋招）](docs/essential-content-for-interview/BATJrealInterviewExperience/5面阿里,终获offer.md)
- [蚂蚁金服 2019 实习生面经总结（已拿口头 offer）](docs/essential-content-for-interview/BATJrealInterviewExperience/蚂蚁金服实习生面经总结%28已拿口头offer%29.md)
- [2019 年蚂蚁金服、头条、拼多多的面试总结](docs/essential-content-for-interview/BATJrealInterviewExperience/2019alipay-pinduoduo-toutiao.md)
- [Bigo 的 Java 面试，我挂在了第三轮技术面](docs/essential-content-for-interview/BATJrealInterviewExperience/bingo-interview.md)
- [2020 字节跳动后端面经分享！已拿 offer](docs/essential-content-for-interview/BATJrealInterviewExperience/2020-zijietiaodong.md)

## Java 学习常见问题

1. [Java 学习路线和方法推荐](docs/questions/java-learning-path-and-methods.md)
2. [Java 培训四个月能学会吗？](docs/questions/java-training-4-month.md)
3. [新手学习 Java，有哪些相关博客、专栏和技术学习网站推荐？](docs/questions/java-learning-website-blog.md)
4. [Java 还是大数据，你需要了解这些东西！](docs/questions/java-big-data.md)
5. [Java 后台开发 / 大数据？你需要了解这些东西！](https://articles.zsxq.com/id_wto1iwd5g72o.html)（知识星球）

## 工具

### Git

- [Git 入门](docs/tools/Git.md)

### Docker

1. [Docker 基本概念解读](docs/tools/Docker.md)
2. [一文搞懂 Docker 镜像的常用操作](docs/tools/Docker-Image.md)

### 其他

- [阿里云服务器使用经验](docs/tools/阿里云服务器使用经验.md)

## 资源

### 书单

- [Java 程序员必备书单](docs/data/java-recommended-books.md)

### 实战项目推荐

- [GitHub 上热门的 Spring Boot 项目实战推荐](docs/data/spring-boot-practical-projects.md)

### GitHub

- [GitHub 上 Star 数最多的 10 个项目](docs/tools/github/github-star-ranking.md)
- [年末将至，值得你关注的 16 个 Java 开源项目](docs/github-trending/2019-12.md)
- [Java 项目月榜单](docs/github-trending/JavaGithubTrending.md)

<details>
<summary>历史月榜（2018–2019）</summary>

- [2018-12](docs/github-trending/2018-12.md)
- [2019-01](docs/github-trending/2019-1.md)
- [2019-02](docs/github-trending/2019-2.md)
- [2019-03](docs/github-trending/2019-3.md)
- [2019-04](docs/github-trending/2019-4.md)
- [2019-05](docs/github-trending/2019-5.md)
- [2019-06](docs/github-trending/2019-6.md)

</details>

### 公众号历史文章

- [公众号历史文章汇总](docs/公众号历史文章汇总.md)

---

## 待办

- [ ] Netty 总结（进行中）
- [ ] 数据结构总结重构（进行中）
- [ ] Elasticsearch（分布式搜索引擎）
- [ ] 数据库扩展：读写分离、分库分表
- [ ] 接口幂等性
- [ ] 高并发
- [ ] 配置中心

## 说明

开源项目的价值来自大家的参与。感谢有你！

### JavaGuide 介绍

开源 JavaGuide 的初始想法源于作者一段比较迷茫的学习经历，主要目的是帮助在学习 Java 或准备面试时遇到问题的同学。

- **对于 Java 初学者：** 本文档倾向于提供一条比较完整的学习路径，让你对 Java 整体知识体系有初步认识；文中的部分文章也适合学习和复习。
- **对于非 Java 初学者：** 更适合回顾知识、准备面试，搞清面试应该把重心放在哪些问题上。提前了解高频考点，不是为了背下来应付面试，而是为了更有针对性地学习重点。

Markdown 格式参考：[GitHub Markdown 格式](https://guides.github.com/features/mastering-markdown/)，表情素材来自：[EMOJI CHEAT SHEET](https://www.webpagefx.com/tools/emoji-cheat-sheet/)。

本仓库使用 [docsify](https://docsify.js.org/#/) 生成文档并部署到 GitHub Pages。

### 作者的其他开源项目推荐

1. [springboot-guide](https://github.com/Snailclimb/springboot-guide)：适合新手入门以及有经验的开发人员查阅的 Spring Boot 教程。
2. [programmer-advancement](https://github.com/Snailclimb/programmer-advancement)：技术人员应该有的一些好习惯。
3. [spring-security-jwt-guide](https://github.com/Snailclimb/spring-security-jwt-guide)：从零入门 Spring Security With JWT（含权限验证）后端部分代码。

### 关于转载

转载本仓库文章到自己的博客时，请注明原文地址。

### 如何对该开源文档进行贡献

1. 笔记内容多为手敲，难免有笔误，欢迎帮忙找错别字。
2. 很多知识点可能尚未覆盖，欢迎补充。
3. 现有内容难免不完善或有误，欢迎修改 / 补充。

### 投稿

欢迎投稿优质原创文章。可通过 Issue 联系，或通过下方微信与作者沟通。

### 联系我

![个人微信](https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-7/wechat3.jpeg)

### Contributor

下面是收集的一些对本仓库提过有价值的 PR 或 Issue 的朋友。排名不分先后。如果你也曾提交过不错的贡献，可以加作者微信联系。

<a href="https://github.com/fanofxiaofeng">
  <img src="https://avatars.githubusercontent.com/u/3983683?s=460&v=4" width="45px" alt="fanofxiaofeng">
</a>
<a href="https://github.com/LiWenGu">
  <img src="https://avatars.githubusercontent.com/u/15909210?s=460&v=4" width="45px" alt="LiWenGu">
</a>
<a href="https://github.com/fanchenggang">
  <img src="https://avatars.githubusercontent.com/u/8225921?s=460&v=4" width="45px" alt="fanchenggang">
</a>
<a href="https://github.com/Rustin-Liu">
  <img src="https://avatars.githubusercontent.com/u/29879298?s=400&v=4" width="45px" alt="Rustin-Liu">
</a>
<a href="https://github.com/ipofss">
  <img src="https://avatars.githubusercontent.com/u/5917359?s=460&v=4" width="45px" alt="ipofss">
</a>
<a href="https://github.com/Gene1994">
  <img src="https://avatars.githubusercontent.com/u/24930369?s=460&v=4" width="45px" alt="Gene1994">
</a>
<a href="https://github.com/spikesp">
  <img src="https://avatars.githubusercontent.com/u/12581996?s=460&v=4" width="45px" alt="spikesp">
</a>
<a href="https://github.com/illusorycloud">
  <img src="https://avatars.githubusercontent.com/u/31980412?s=460&v=4" width="45px" alt="illusorycloud">
</a>
<a href="https://github.com/kinglaw1204">
  <img src="https://avatars.githubusercontent.com/u/20039931?s=460&v=4" width="45px" alt="kinglaw1204">
</a>
<a href="https://github.com/jun1st">
  <img src="https://avatars.githubusercontent.com/u/14312378?s=460&v=4" width="45px" alt="jun1st">
</a>
<a href="https://github.com/fantasygg">
  <img src="https://avatars.githubusercontent.com/u/13445354?s=460&v=4" width="45px" alt="fantasygg">
</a>
<a href="https://github.com/debugjoker">
  <img src="https://avatars.githubusercontent.com/u/26218005?s=460&v=4" width="45px" alt="debugjoker">
</a>
<a href="https://github.com/zhyank">
  <img src="https://avatars.githubusercontent.com/u/17696240?s=460&v=4" width="45px" alt="zhyank">
</a>
<a href="https://github.com/Goose9527">
  <img src="https://avatars.githubusercontent.com/u/43314997?s=460&v=4" width="45px" alt="Goose9527">
</a>
<a href="https://github.com/yuechuanx">
  <img src="https://avatars.githubusercontent.com/u/19339293?s=460&v=4" width="45px" alt="yuechuanx">
</a>
<a href="https://github.com/cnLGMing">
  <img src="https://avatars.githubusercontent.com/u/15910705?s=460&v=4" width="45px" alt="cnLGMing">
</a>

### 公众号

如果想实时关注更新文章和干货分享，可以关注公众号。

**《Java 面试突击》：** 由本文档衍生、专为面试准备的《Java 面试突击》V2.0 PDF，公众号后台回复 **「Java面试突击」** 即可免费领取。

**Java 工程师必备学习资源：** 公众号后台回复关键字 **「1」** 即可获取。

![我的公众号](https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-6/167598cd2e17b8ec.png)
