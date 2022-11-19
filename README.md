# My-Java-Interview-Road





## 写在前面

一名转码的半科班研究生的面试问答记录贴。方向是Java开发。一年的时间（2021年11月 - 2022年11月），从日常实习到暑期实习，再到秋招拿了10家左右的offer，最终选择了某世界排名靠前独角兽，我深刻感受到了其中的艰难以及面试过程中带给我的成长。我将其记录分享出来，希望对你有所帮助~

别忘记点一颗star喔，谨防丢失~





## 目录

主要包含：实习（日常 + 暑期）、秋招、他人面经分享四个部分

时间只记录一面的时间，难度满星为★★★★★（主要靠自己的感受）

（点击公司名称直接跳转喔）

### 实习

| 公司                                                     | 岗位               | 时间       | 难度  |
| -------------------------------------------------------- | ------------------ | ---------- | ----- |
| [0 广东马上信息科技有限公司](#0广东马上信息科技有限公司) | Java开发实习生     | 2021-11-9  | ★★    |
| [1 字节跳动](#1 字节跳动)                                | 测试开发实习生     | 2021-11-18 | ★★★   |
| [10 爱奇艺](#10 爱奇艺)                                  | Java开发实习生     | 2021-11-19 | ★★★   |
| [11 搜款网](#11 搜款网)                                  | Java研发实习生     | 2021-12-8  | ★★★★★ |
| [100 视源股份（CVTE）](#100 视源股份（CVTE）)            | Web后台开发实习生  | 2021-12-8  | ★★★★  |
| [101 蚂蚁金融](#101 蚂蚁金融)                            | Java开发实习生     | 2022-3-14  |       |
| [110 美团](#110 美团)                                    | Java开发实习生     | 2022-3-17  |       |
| [111 快手](#111 快手)                                    | Java开发实习生     | 2022-4-2   |       |
| [1000 华为](#1000 华为)                                  | 应用软件开发实习生 | 2022-4-16  |       |
| [1001 OPPO](#1001 OPPO)                                  | Java开发实习生     | 2022-4-11  |       |
| [1010 阿里巴巴-本地生活](#1010 阿里巴巴-本地生活)        | Java开发实习生     | 2022-4-11  |       |





### 秋招

| 公司                   | 岗位           | 时间     | 难度 |
| ---------------------- | -------------- | -------- | ---- |
| [0x00 4399](0x00 4399) | 后端开发工程师 | 2022-9-3 |      |
|                        |                |          |      |
|                        |                |          |      |







### 他人面经分享

本着开源的精神，本人收集了他人在网上的面试记录。

**若不便公开或者侵权，请联系本人第一时间删除！**



| 公司                                         |
| -------------------------------------------- |
| [蚂蚁支付宝实习一面](#1、蚂蚁支付宝实习一面) |
| [字节暑期实习一面](#2、字节暑期实习一面)     |
| [京东暑期实习一面](#3、京东暑期实习一面)     |







## 0 广东马上信息科技有限公司

### 一面

为什么学习Java？

JVM的运行时内存结构？

怎么设置堆的大小？

Java线程池的几个参数？

阿里巴巴开发手册关于线程池的规定？

Redis用途有哪些，项目中是怎么使用的？

Redis缓存一致性问题？

聊一下MySQL索引？

SpringCloud哪些组件？

什么是分布式锁？

Dubbo知道吗？

有了解过消息队列吗？



### 二面

问项目（一个电商项目）

为什么要使用多线程？

Java内存模型？

说一下volatile关键字？

说一下Redis，为什么要使用Redis，使用本地内存不可以吗？

说一下Nginx？

SpringCloud中各大组件有哪些？

为什么要使用服务注册中心呢？



### HR面

可以实习多久？

期望的实习薪资？

住在哪里？

介绍了公司的基本情况



## 1 字节跳动

### 一面

问项目

为什么要学习Java呢？

宿舍同学是做什么方向的？

Java中有哪些数据类型？

使用Redis有哪些好处？

你了解Redis过期删除策略？

谈一下你对MQ的理解，了解哪些MQ?

MQ有什么优点和缺点？

浏览器输入url，访问的具体流程？

SpringBoot框架的优点？

说一说对多线程的理解，为什么要使用多线程？

面向对象的理解？

Java、python、go的区别？

算法：找出字符串中第一个只出现一次的字符



## 10 爱奇艺

### 一面（50分钟）

Java集合容器

HashMap、ArrayList、LinkedList、迭代器

HashMap的底层结构

HashMap，put一个元素会发生什么

ArrayList删除一个元素remove操作会发生什么

MySQL数据库group by、给一个表查询年龄大于30的员工

MySQL的联合索引，以及where a = 1 and b = 1是否会走索引，where b = 1呢？

LinkedList的链表是什么结构吗？

JVM垃圾回收有哪些算法，为什么要有垃圾回收算法

怎么判断是否是垃圾

分代收集算法

新生代有哪几个区

为什么eden ： survivor01 ： survivor02 是 8 ：1 ：1

一个 i = 0，两个线程都进行 i++ 的操作，最后 i 大概是多少

考察多线程volatile、synchronized、Lock

Spring注解说一个常用的注解。@Autowired 依赖注入

@Autowired注入的方式，byType

SpringCloud介绍一下？

你觉得 MyBatis 和 JPA 有什么区别？

最后：爬楼梯、冒泡排序、快速排序



### 二面（55分钟）

equal 和 hashcode 为什么要重写？（结合HashMap来说会比较清晰）

线程安全的HashMap，ConcurrentHashMap

ConcurrentHashMap中Sychronized加锁是全部加还是局部加？

MySQL的explain命令？

MySQL回表了解过吗？

说一下覆盖索引？

HTTP状态码？

什么是死锁？解决死锁有哪些办法？

JVM中对象的过程，新生代、老年代这些怎么变化的？

JDK1.8用的什么垃圾回收器？

类加载的过程？

双亲委派机制？

引导类加载器加载的是哪里的class文件？

线程池的原理，几种创建线程池的方式？

创建线程池的六大参数？

核心线程数的底层原理？

为什么推荐使用ThreadPoolexecutor？

了解哪些并发工具？

Redis有哪些数据结构？

Redis主从复制是怎么实现的？

String的底层结构？

ResultMap 和 ResultType 有什么区别？

Spring怎么解决循环依赖的？

SpringAOP出现在Spring生命周期的哪一个阶段？

SpringBoot为什么好用？

如何实现自定义starter？

SpringCloud用过哪些组件？

ElasticSearch介绍一下，怎么用的？

聊研究生课题组相关的事情。



## 11 搜款网

### 一面

数组和链表的区别

链表除了树这种进化形式，还有什么形式

数组是怎么通过下标访问的，底层原理

用位运算实现加法

字符串匹配 KMP

给一个二进制组成的01串，将其倒置有哪些方法

算法题：环形链表找到切入点

进程和线程区别

同步和异步区别

生产者与消费者模型

pv操作怎么实现锁

死锁的四个必要条件

银行家算法

什么是缺页中断

有哪几种进程调度方式

多级反馈队列调度算法中：一个进程运行后进行了上下文切换，那么这个进行没有运行完的部分保存到哪里。

三次握手、四次挥手

滑动窗口

什么是粘包和拆包

AQS底层原理

synchronized 和 Lock 的区别

Redis的数据结构

String底层结构SDS

B树和B+树有什么区别？

什么是CAS

什么是反射



### 二面

如果让你设计一个数据库，你打算怎么设计

hashmap底层原理

怎么实现一个hashmap



### HR面

期望的实习工资是多少？

你觉得这里的氛围怎么样?（线下面试）

你可以实习多久？



## 100 视源股份（CVTE）

### 一面（45分钟）

数组和链表的区别？

说一下hashmap 和 concurrentHashMap？

ArrayList的结构？

Java中的异常体系？

哪里有用到finally（lock解锁的时候）？

为什么要使用线程池？

核心线程数有什么缺点？

线程池拒绝策略？

Synchronized 锁升级的过程？

MySQL索引的结构？

MySQL题目：给一个商品表，自己写字段，模糊查询

死锁的四个必要条件？

JVM垃圾回收算法？

分代收集理论中对象的变化过程？

Bean的生命周期？

AOP在Bean生命周期的什么阶段？

Bean的循环依赖，为什么要使用到三级缓存，可以只用两级缓存吗？

设计模式：单例模式和工厂模式？

工厂模式的优点，为什么要使用这种模式？

平时会看书吗，哪些技术书？



### 二面（44分钟）

做项目中过程中有没有需要什么困难？（Redis）

Redis除了用来做缓存还可以用来做什么？

项目中有没有用到什么设计模式？

为什么要使用MVC三层架构，知不知道有其它的架构？

 运行一个方法很慢，有哪些可能性，怎么排查？

统计调用一个方法的次数？（回答了hashmap）

怎么去做一个定时任务？

定时任务怎么唤醒？

最近在学习什么技术？（回答了微服务）

你是怎么理解微服务的？

微服务有什么缺点？

平时是怎么学习的？

算法题：反转链表



### HR面（30分钟）

你拿过其它公司的offer没有，为什么要选择CVTE？

你人生中面临最大压力是什么时候？

你理想中的工作和生活是什么样子？

对于下班时间有什么要求？

你老家是哪的？父母是做什么工作的？

和父母平时是怎么沟通的？

父母对你的未来有没有什么要求？

反问：实习生进公司担任什么角色？



## 101 蚂蚁金融

### 一面（简历面）





## 110 美团

### 一面

问项目

分别介绍MySQL、Redis、ES的使用场景？

进程同步的方法有哪些？

说一下分页和分段算法？

进程调度算法？

TCP三次握手和四次挥手？

TCP和UDP下面分别有哪些协议？

Cookie 和 Session 有什么区别？

Java数据类型以及分别占用多少字节？

ArrayList扩容原理？

Java异常说一下？

OutOfMemory怎么发生的？

Java8的垃圾回收器？（这里面试官非说的G1，但是明明是Sca + Old）

JVM的组成？

类加载过程？

java线程池的工作原理？

有过MySQL优化经验吗？

MySQL为什么要使用B+树？

B+树和B树有什么区别？

MySQL四种隔离级别？

算法题：用栈实现汉诺塔（递归调用）



## 111 快手

### 一面（50min）

问项目相关

说一下final关键字

用final关键字修饰的map能增加元素吗（可以，当时说的有点含糊，final修饰的变量不可被修改说的是 **引用** 不可被修改）

ArrayList 最多能存储多少元素？（ArrayList的size方法返回的是一个int，所以它最多能放Integer.MAX_VALUE（(2^31)-1）个元素。）

两个ArrayList集合取交集？

一个实际应用编程题，学生有一个兴趣属性，一个学生可以有一个或多个兴趣，在一个学生集合中，找到兴趣有打乒乓球和踢球的学生。

两道MySQL编程：1、求工资倒数第二高的人 2、求前十工资的和



感受：需要多练习MySQL编程



## 1000 华为







## 1001 OPPO

### 一面（50min）

项目提问

Redis用途有哪些？（缓存、分布式锁、分布式事务）

如何保证Redis和MySQL数据库数据的一致性？

Dubbo框架的流程？

关于Dubbo版本的改变，比如后端新增了字段，要更改版本什么的？

md5加密相关，有哪些可逆的加密算法？（我说我忘了，面试官说了AES，安全的东西都忘了）

前后端对接口用的什么平台？回答：Yapi ，面试官引伸出Swagger

Swagger常用的注解有哪些？

HTTP状态码？

MySQL场景题--通过日期查找一系列手机的销量？

反问：问了一下公司的技术栈



## 0x00 4399

### 一面

问项目

用户态和内核态的区别？

什么是零拷贝？

HTTP和HTTPS的S是什么？

评价系统（我的项目）增加可以回复评价的功能，应该怎么设计数据库？

以图搜款的准确率怎么获得？

接口优化是怎么进行的？

接口优化主要还是SQL优化。

阿里云图搜的流程？

可以转游戏后端开发吗？

平时是怎么学习的？



### HR面

班级干部经历

为什么要转专业

你觉得本科和硕士有什么区别

老家是哪里的，以后想在哪里发展

期望薪资是多少（我说的太高，HR面直接挂掉了）









## 1、蚂蚁支付宝实习一面

1. 面向对象的三大特性，讲一下封装
2. mysql 索引怎么选择？索引的优缺点？还有什么缺点
3. mysql 事务的特性？什么是持久性
4. 业务里 redis 的过期策略设置
5. HashMap 的扩容机制？为什么扩容选择 2 倍。ConcurrentHashMap 是线程安全的吗？怎么保证是线程安全的
6. 线程的创建方式
7. 进程间的通信方式讲一下
8. 讲一下 tcp 和 udp 区别
9. tcp 建立连接后怎么保证可靠传输的
10. 说一下快排，快排是稳定的吗？归并的稳定的吗？哪些排序算法是稳定哪些是不稳定的
11. jvm 垃圾回收机制，怎么找到垃圾、怎么回收垃圾
12. redis 的缓存击穿、穿透、雪崩各是什么情况
13. 乐观锁、悲观锁、讲一下 cas，典型场景
14. 读过开源项目源码吗？当项目领导你会怎么安排前后端人员工作
15. 业务中的对象存储隐私问题怎么解决





## 2、字节暑期实习一面

1. 讲一下索引的你的理解
2. 事务的特性
3. 讲一下存储引擎，各有什么区别
4. MyISAM 与 InnoDB 的区别
5. 数据库隔离级别
6. 讲一下三次握手、四次分手具体
7. 如何保证可靠传输
8. 点击一个 url 如何处理
9. http 状态码讲一下
10. 进程和线程的区别
11. 进程间的通信，具体应用场景
12. 写 sql，查出总成绩排名 3-10 名的 id
13. 行升序二维数组的 top k
14. 最长不重复子字符串





## 3、京东暑期实习一面

1. 一道回溯题
2. String 是不是基本类型、与 StringBuffer、与 StringBuilder 区别
3. 索引失效的场景、场景题的索引设计
4. oss 数据库与 mysql 数据库不一致怎么解决
5. hashmap 原理、数组和链表的区别
6. redis 使用场景
7. 异常和错误的区别







