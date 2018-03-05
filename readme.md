# 基础知识

## java基础

1. 基本类型（占用的内存）和包装类型
2. 数组和对象
3. 程序控制语句，if、switch、while、for
4. 包、接口和抽象类
5. 异常处理
6. 多线程变成、线程池、fork-join、并发编程
7. annotation
8. 枚举
9. 泛型
10. 反射
11. 字符串和String研究
12. 集合内容，List、Map
13. 文件io和网络io
13. bio、nio和aio

## 常用设计模式

1. 模板模式
2. 单例模式 & 多例模式
3. 代理模式
4. 策略模式
5. 原型模式
6. 工厂模式
7. 委托
8. 其他

## Spring5

1. IOC容器设计原理及高级特性
2. AOP设计原理
3. FactoryBean和BeanFactory
4. Spring事务处理机制
5. Spring JDBC
6. Spring MVC九大组件
7. 手动实现Spring MVC
8. Spring5新特性

## Mybatis

1. 代码自动生成器
2. mybatis关联查询和嵌套查询
3. 缓存使用场景及选择策略
4. Spring集成下的SqlSession和Mapper
5. Mybatis的事务
6. 分析Mybatis动态代理的真正实现
7. 手动实现Mini版本的Mybatis

# 分布式

## 分布式原理

1. 分布式架构的演进过程
2. 如何把应用从单机扩展到分布式
3. CDN加速静态文件的访问
4. 系统监控、容灾、存储动态扩容
5. 架构设计及业务驱动划分
6. CAP、BASE理论及应用

## 分布式策略

## 分布式中间件

## 分布式实战

# 微服务

## 微框架Spring boot

1. 与微服务之间的关系
2. 热部署
3. 核心组件，Starter、Actuator、AutoConfiguration、Cli
4. 集成Mybatis实现多数据源路由
5. 集成redis实现缓存
6. 集成swagger2构建api管理及测试体系
7. 实现多环境配置动态解析

## Spring Cloud

1. Eureka注册中心
2. Ribbon集成REST实现负载均衡
3. Fegion声明式服务调用
4. Hystrix服务熔断降级方式
5. Zuul实现微服务网关
6. Config分布式统一配置中心
7. Sleuth调用链路跟踪
8. BUS消息总线
9. 基于Hystrix实现接口降级方案实战
10. 集成Spring clouds实现统一整合方案

## Docker虚拟化

1. Docker镜像、仓库、容器
2. Docker File构建LNMP环境个人博客
3. Docker Compose构建LNMP环境个人博客
4. Docker网络组成、路由互联、Openvswitch
5. 基于swarn构建docker集群
6. Kubernetes简介

## 漫谈微服务架构

1. SOA架构和微服务架构之间的区别和联系
2. 如何设计微服务及其设计原则
3. 解惑Spring boot流行因素及能解决什么问题
4. 什么是Spring cloud，为啥要选择它
5. 全局分析Spring cloud各个组件所解决的问题

# 性能优化

性能只讲科学，不讲运气

## 理解性能优化

1. 性能基准
2. 性能优化到底是什么
3. 衡量维度

## Jvm调优

1. 知其然，知其所以然
2. 什么是jvm运行时数据区
3. 什么是jvm内存模型 JMM
4. 垃圾回收器的使用场景（Throughput / CMS）
5. 理解GC日志，从日志中查询有用信息
6. MAT分析dump文件

## Tomcat调优

1. tomcat如何工作的，探查tomcat的运行机制及框架
2. 分析tomcat线程模型
3. tomcat系统参数认识及调优
4. 基准测试

## Mysql调优

1. 理解底层B+Tree机制
2. SQL执行计划详解
3. 索引优化详解
4. SQL语句优化

# 工程管理

## Maven

1. 生成可执行jar、理解Scope
2. 类冲突、包依赖，NoClassDefFoundError问题定位及jj解决
3. 全方位理解Maven的Lifecycle、Phase、Goal
4. 架构师必备之Maven生成Archetype
5. Maven插件实战，自己实现插件
6. Nexus使用、上传、配置
7. 对比Gradle

## Jenkins

1. 搭建Jenkins自动化部署环境
2. Jenkins和git、maven的集成
3. 多环境发布，dev、test、gld和prod
4. Jenkins多环境配置、权限管理和插件使用
5. Pipeline搭建自动化流水

## Git

1. git是什么，git的工作原理是什么
2. git常用命令，最佳实践
3. git冲突的原因，要如何解决
4. git flow规范团队的git使用（架构师必备）

## Sonar

# 实战