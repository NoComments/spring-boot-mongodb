# Spring-mongoDB
  随着Nosql分布式数据库的不断出现，各种非关系型数据库的重要性日益涌现。本项目基于Spring-data的API，实现一个Spring框架连接文档数据库mongoDB，并对数据进行管理的基本功能，包含的内容如下：
  
  1.包含对文档的基本增删改查（CRUD）的功能，基于Spring-data的MongoRepository扩展实现，update和insert操作本质上使用的同一个DAO接口，区别是update操作必须提供主键id，insert操作不提供id字段；
  
  2.包含数据排序、分页的功能；
  
  3.包含按条件进行数据筛选的功能；
  
  4.前端分页插件使用Bootgrid，前端框架使用Bootstrap；
  
  5.使用时，先开启mongoDB，新建数据库Spring-nosql;
  
  6.页面访问入口http://localhost:8080/Spring-mongoDB/mongodb/index
  
  
  本项目的实例文档模式如下：
```
{
    "_id" : ObjectId("58369d57eab6bfd4371a5d37"),
    "_class" : "po.Picture",
    "filename" : "activiti教程",
    "path" : "f盘",
    "size" : NumberLong(9765)
  }
```
  
  
  
  效果图

![输入图片说明](http://git.oschina.net/uploads/images/2016/1129/204109_2e0eb116_1110335.jpeg "在这里输入图片标题")
![输入图片说明](http://git.oschina.net/uploads/images/2016/1129/204119_e64b2915_1110335.jpeg "在这里输入图片标题")
![输入图片说明](http://git.oschina.net/uploads/images/2016/1129/204131_df5ed465_1110335.jpeg "在这里输入图片标题")

### 附录：个人作品索引目录（持续更新）

#### 基本篇

1. [SpringMVC,Mybatis,Spring三大框架的整合实现增删改查](https://gitee.com/shenzhanwang/SSM)
2. [Struts2,Hibernate,Spring三大框架的整合实现增删改查](https://gitee.com/shenzhanwang/S2SH)
3. [Spring,SpringMVC和Hibernate的整合实现增删改查](https://gitee.com/shenzhanwang/SSH)
4. [Spring平台整合activiti工作流引擎实现OA开发](https://gitee.com/shenzhanwang/Spring-activiti)
5. [Spring发布与调用REST风格的WebService](https://gitee.com/shenzhanwang/Spring-REST)
6. [Spring整合Apache Shiro框架，实现用户管理和权限控制](https://gitee.com/shenzhanwang/Spring-shiro)
7. [使用Spring security做权限控制](https://gitee.com/shenzhanwang/spring-security-demo)

#### 中级篇

8. [Spring连接mongoDB数据库实现增删改查](https://gitee.com/shenzhanwang/Spring-mongoDB)
9. [Spring连接Redis实现缓存](https://gitee.com/shenzhanwang/Spring-redis)
10. [Spring连接图存数据库Neo4j实现增删改查](https://gitee.com/shenzhanwang/Spring-neo4j)
11. [Spring平台整合消息队列ActiveMQ实现发布订阅、生产者消费者模型（JMS）](https://gitee.com/shenzhanwang/Spring-activeMQ)
12. [Spring整合消息队列RabbitMQ实现四种消息模式（AMQP）](https://gitee.com/shenzhanwang/Spring-rabbitMQ)
13. Spring整合Jasig CAS框架实现单点登录（未开源）
14. Spring框架的session模块实现集中式session管理（未开源）
15. [Spring整合websocket实现即时通讯](https://gitee.com/shenzhanwang/Spring-websocket)
16. 使用Spring boot整合mybatis,rabbitmq,redis,mongodb实现增删改查（未开源）
17. [Spring MVC整合FastDFS客户端实现文件上传](https://gitee.com/shenzhanwang/Spring-fastdfs)

#### 高级篇

18. 搭建zookeeper集群提供目录服务（未开源）
19. 使用ubuntu+apache+SVN+SVNadmin+maven+Nexus+Hudson搭建持续集成环境（未开源）
20. Spring框架整合dubbo框架实现分布式服务治理（SOA架构）（未开源）
21. Spring框架整合dubbox实现微服务架构（MSA架构）（未开源）
22. 使用Spring Cloud实现微服务架构（MSA架构）（未开源）
23. 使用FastDFS搭建分布式文件系统（高可用、负载均衡）（未开源）
24. 搭建高可用nginx集群和Tomcat负载均衡（未开源）
25. 搭建可扩展的ActiveMQ高可用集群（未开源）
26. 实现Mysql数据库的主从复制、读写分离、分表分库、负载均衡和高可用（未开源）
27. 搭建高可用redis集群实现分布式缓存（未开源）
28. [Spring整合SolrJ实现全文检索](https://gitee.com/shenzhanwang/Spring-solr)

### 捐赠
![输入图片说明](https://gitee.com/uploads/images/2017/1217/145453_b639d3db_1110335.png "mm_facetoface_collect_qrcode_1513493342741.png")

![输入图片说明](https://gitee.com/uploads/images/2017/1217/145502_2d4fe513_1110335.jpeg "1513493369523.jpg")
