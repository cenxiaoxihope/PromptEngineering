# Java 学习计划 📚

## 第一阶段：基础入门（4-6周）
### Java 语言基础
#### 数据类型与变量
- 基本数据类型（int, long, double, boolean等）
- 引用数据类型
- 类型转换与包装类
#### 运算符与控制流
- 算术、逻辑、比较运算符
- if-else、switch 条件语句
- for、while、do-while 循环
#### 数组与字符串
- 一维数组、多维数组
- String 类常用方法
- StringBuilder 与 StringBuffer
### 面向对象编程（OOP）
#### 类与对象
- 类的定义与对象的创建
- 构造方法
- this 关键字
#### 封装、继承、多态
- 访问修饰符（public, private, protected）
- 继承与 super 关键字
- 方法重写与重载
- 抽象类与接口
#### 其他OOP特性
- 静态成员与静态代码块
- 内部类
- 枚举类型
### 异常处理
#### 异常体系
- 受检异常 vs 非受检异常
- try-catch-finally 语句
- throw 与 throws
#### 自定义异常
- 创建自定义异常类
- 异常链
### 常用工具类
#### 集合框架基础
- List（ArrayList, LinkedList）
- Set（HashSet, TreeSet）
- Map（HashMap, TreeMap）
#### IO基础
- File 类操作
- 字节流与字符流
- 序列化与反序列化

## 第二阶段：进阶提升（6-8周）
### 集合框架深入
#### 源码分析
- ArrayList 扩容机制
- HashMap 底层原理（哈希表、红黑树）
- ConcurrentHashMap 线程安全实现
#### 高级集合类
- Queue 与 Deque
- PriorityQueue
- 不可变集合
### 多线程与并发
#### 线程基础
- Thread 类与 Runnable 接口
- 线程状态与生命周期
- 线程同步（synchronized）
#### 并发工具类
- Executor 框架
- Callable 与 Future
- 线程池（ThreadPoolExecutor）
#### JUC 包
- Lock 与 Condition
- CountDownLatch、CyclicBarrier、Semaphore
- Atomic 原子类
- BlockingQueue
### JVM 基础
#### 内存模型
- 堆、栈、方法区
- 垃圾回收机制
- 垃圾收集器（G1, CMS, ZGC）
#### 性能调优
- JVM 参数配置
- 内存泄漏排查
- 性能监控工具（JVisualVM, JConsole）
### 设计模式
#### 创建型模式
- 单例模式
- 工厂模式
- 建造者模式
#### 结构型模式
- 代理模式
- 装饰器模式
- 适配器模式
#### 行为型模式
- 观察者模式
- 策略模式
- 模板方法模式

## 第三阶段：Web开发（8-10周）
### Java Web 基础
#### Servlet 与 JSP
- Servlet 生命周期
- 请求与响应处理
- 会话管理（Cookie, Session）
#### 过滤器与监听器
- Filter 实现
- Listener 类型与应用
### Spring 框架
#### Spring Core
- IOC 容器与依赖注入
- Bean 生命周期
- 作用域与循环依赖
#### Spring AOP
- 面向切面编程概念
- 切点表达式
- 通知类型
#### Spring 数据访问
- Spring JDBC
- 事务管理
- 声明式事务
### Spring Boot
#### 快速入门
- 自动配置原理
- Starter 依赖
- 配置文件（application.yml/properties）
#### Web 开发
- Spring MVC
- RESTful API 设计
- 参数校验与异常处理
- 拦截器与跨域处理
#### 数据持久化
- Spring Data JPA
- MyBatis 整合
- 数据库连接池（HikariCP, Druid）
### 常用中间件
#### 缓存
- Redis 基础数据类型
- Spring Cache 整合
- 缓存穿透、击穿、雪崩解决方案
#### 消息队列
- RabbitMQ / Kafka 基础
- 生产者与消费者模式
- 消息可靠性保证

## 第四阶段：微服务与云原生（8-10周）
### Spring Cloud
#### 服务注册与发现
- Eureka / Nacos
- 服务提供者与消费者
#### 配置中心
- Spring Cloud Config
- Nacos Config
#### 服务网关
- Gateway 路由配置
- 过滤器链
- 限流与熔断
#### 服务治理
- Ribbon 负载均衡
- Feign 声明式调用
- Hystrix / Sentinel 熔断降级
- Sleuth + Zipkin 链路追踪
### 容器化技术
#### Docker
- 镜像与容器概念
- Dockerfile 编写
- Docker Compose
#### Kubernetes
- Pod、Deployment、Service
- 配置管理（ConfigMap, Secret）
- 持久化存储
### 数据库进阶
#### MySQL 高级
- 索引优化与执行计划
- 事务隔离级别
- 分库分表策略
- 读写分离
#### NoSQL 数据库
- MongoDB 文档数据库
- Elasticsearch 搜索引擎

## 第五阶段：项目实战与持续学习
### 实战项目
#### 项目一：企业级后台管理系统
- RBAC 权限管理
- 前后端分离架构
- 接口文档（Swagger/OpenAPI）
#### 项目二：分布式电商系统
- 商品、订单、支付模块
- 秒杀系统设计
- 分布式事务（Seata）
#### 项目三：微服务架构改造
- 单体应用拆分
- 服务治理实践
- CI/CD 流水线
### 持续学习方向
#### 性能优化
- 代码层面优化
- 数据库优化
- 系统架构优化
#### 新技术探索
- GraalVM 原生镜像
- Project Loom（虚拟线程）
- Spring Boot 3.x + Java 17+
#### 软技能提升
- 代码审查（Code Review）
- 技术文档写作
- 开源项目贡献

## 学习资源推荐
### 官方文档
- [Oracle Java 文档](https://docs.oracle.com/javase/)
- [Spring 官方文档](https://spring.io/projects)
- [Spring Boot 文档](https://spring.io/projects/spring-boot)
### 推荐书籍
- 《Java 核心技术》
- 《Effective Java》
- 《深入理解 Java 虚拟机》
- 《Spring 实战》
### 在线平台
- 极客时间 Java 系列课程
- 慕课网实战项目
- LeetCode 算法练习
- GitHub 开源项目学习
### 实践建议
- 每天编码至少 2 小时
- 每周完成一个小功能
- 每月总结学习心得
- 参与技术社区讨论
