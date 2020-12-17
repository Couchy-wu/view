[toc]

### Golang_coder_interview



#### Algo

##### 1.字符串

- [ ] 如何原地交换两个数
- [ ] 字符串之间保留一个空格之后将字符串翻转
- [ ] 找到字符串的最长无重复字符子串
- [ ] 最短回文串
- [ ] 最长回文子串长度
- [ ] 数组中重复的数据
- [ ] 1到n乱序排列的数据，少了其中一个，找出这个数
- [ ] 26进制字母求和
- [ ] 两个字符串最长公共子串
- [ ] ⼀个40亿的⽆序数字，请找出不存在的数字



##### 2.dp

- [ ] 盛最多水的容器
- [ ] 爬楼梯问题
- [ ] 接雨水
- [ ] 岛屿问题(高频)



##### 3.数组

- [ ] 两个有序数组合并
- [ ] 两个有序数组合并，返回合并之后的中位数
- [ ] 数组中值出现了一次的数字
- [ ] 寻找两个升序数组的第K大值
- [ ] 无序数组找中位数
- [ ] 多数组 笛卡尔积，例：['s',['a', 'b'], [1, 2], 'x']，输出：[["s","a",1,"x"],["s","a",2,"x"],["s","b",1,"x"],["s","b",2,"x"]]
- [ ] ⼀个很⼤的List，⾥⾯都是int类型，如何实现加和？因为电⾯，就说了⼀下思路



##### 4.树

- [ ] 二叉树的右视图
- [ ] 二叉数中序遍历
- [ ] 判断二叉树是否为平衡二叉树
- [ ] 二叉树节点的公共祖先
- [ ] 二叉树的最大深度
- [ ] 通过中序遍历序列和先序序列恢复二叉树
- [ ] 二叉树的中序遍历和层次遍历



##### 5.排列

- [ ] 接口怎么设计，需要实现方实现什么
- [ ] 怎么调用这个通用的排序方法
- [ ] 全排列



##### 6.链表

- [ ] 合并两个有序的单链表
- [ ]  链表奇递增 偶递减，整体递增
- [ ] 单链表逆序
- [ ] LRU缓存机制 （考虑并发访问）(高频) LRU实现--针对hash存储的方式，如何改进
- [ ] 单向链表排序
- [ ] 取单链表的倒数第K个结点
- [ ] ⼀个链表，输⼊k，⽐如k=3，翻转前3个链表值



##### 7.hash

- [ ] 字符串hash算法的实现
- [ ] 敏感词过滤





##### 8.other

- [ ] 25匹马，每次只能比赛5组，最快几次找到前3名
- [ ] 

##### 9.海量数据处理

- [ ] hash
- [ ] 字典树
- [ ] bitmap
- [ ] 布隆过滤器
- [ ] MapReduce
- [ ] 桶
- [ ] 亿级数据，每一行两列，如何按照第一列升序 第二列降序排列？数据分布不均或较为集中的情况又如何处理更好？
- [ ] 几十亿行数据，记录当天的抖音用户 uid 登录时间 登出时间 如何计算出日活峰值在哪个时间（精确到秒），以及持续了几秒。
- [ ] 



#### Redis

##### 1.数据结构

- [ ] zset的底层实现
- [ ] Redis 3.1 都⽤过哪些数据类型？分别介绍下使⽤场景？



##### 2.使用场景

- [ ] 分布式锁
- [ ] 缓存雪崩、缓存击穿、缓存穿透
- [ ] redis超时是什么引起的
- [ ] redis缓存穿透,缓存雪崩





##### 3.架构

- [ ] redis是单线程的吗
- [ ] redis底层网络原理
- [ ] redis的发布/订阅的原理
- [ ] 数据缓存过期策略
- [ ] redis的部署模式
- [ ] redis为什么速度比较快
- [ ] reids的大key、热key的处理
- [ ] 持久化策略及其对比:RDB和AOF区别，AOF重写
- [ ] redis内存淘汰策略（说说 redis 中到期删除是怎么实现的）
- [ ] redis主从复制过程
- [ ] redis哨兵选leader过程、槽相关、redis-cluster和codis扩展
- [ ] redis incr实现
- [ ] redis大key会有什么问题，如何解决
- [ ] redis 的删除策略。定时 定期 惰性 lru(LRU高频)
- [ ]  3.2 持久化机制，AOF、RDB具体区别有哪些？ 
- [ ] 3.3 Redis 主从同步机制是怎么样的，⽐如slave启动之后同步过程？
- [ ]  3.4 Redis Cluster集群如何选主的？ 
- [ ] 3.5 Redis Cluster 跟哨兵模式有什么区别吗？ 
- [ ] 3.6 Sentinel 哨兵模式是如何选主的？
- [ ] 这⾥说跟cluster差不多，追问了下，其实还是有些区别的， sdown odown 主观宕机、客观宕机⽅式不太⼀样





#### MySQL

##### 1.索引

- [ ] 对 a b c 建索引，找 b c 时会不会走索引？ 精准找 a 范围 b 精准 c 呢？ ###3. Redis
- [ ] 创建索引后，查询读取I/O的次数
- [ ] 索引的分类
- [ ] 聚簇索引和非聚簇索引的区别
- [ ] 创建索引后，查询读取I/O的次数
- [ ] 索引的最左前缀原则
- [ ] mysql数据的索引优化以及失效
- [ ] 联合索引怎么存储？
- [ ] 覆盖索引相关问题
- [ ] 假设有⼀个表字段⼏⼗个，索引如何创建的？所有字段都能建吗？区分度、选择性、列基数

##### 2.锁

- [ ] 数据库中的乐观锁悲观锁
- [ ] 排他锁(x锁)
- [ ] 什么是死锁，如何避免
- [ ] mysql的隔离级别？处理什么问题的（脏读、幻读、不可重复读）(高频)
- [ ] 间隙锁坏处，如何避免
- [ ] 说说这些间隙锁的底层实现 ( 我真的学不动了 )



##### 3.日志

- [ ] undo log
- [ ] redo log
- [ ] binlog

##### 4.架构

- [ ] mysql的主从复制过程？
- [ ] mysql的大表优化方式

##### 5.引擎

- [ ] 如果Innodb没主键怎么办？
- [ ] 为什么选择B+树实现索引？一般深度为多少？b+树和红黑树的区别?(高频)
- [ ] MySQL为什么是B + 树的结构，为什么不能是红⿊树呢？优化的是什么，优化的是磁盘IO，减少磁盘寻址。
- [ ] MySQL数据库底层实现结构？B+树结构，也讲了数据⻚，以及⻚⽬录相关的
- [ ] Innodb 默认是哪个隔离级别
- [ ] 说说 innodb 如何避免各种读的
- [ ] 说说 mvcc 的底层实现

##### 6.事务

- [ ] 



##### 7.SQL

- [ ] 从学生表中查询每个班的分数的前3名
- [ ] 写一条sql统计， 统计当天访问量前10的ip ip visit_time url 102.12.12.1 2020-03-25 10:10:10 



#### MQ

##### 1.设计相关

- [ ] kafka使用场景
- [ ] Kafka如何保证消息可靠,Kafak为什么那么快
- [ ] Kafka 4.1 ⽣产端是如何发送⼀条消息到Broker的？
- [ ] 4.2 具体可以调整哪些参数提升吞吐量？
- [ ] 4.3 消费端发⽣rebalance的过程是怎样的？
- [ ] ⽐如有⼀个新的consumer加⼊ 到了Group中是个什么流程？
- [ ] RabbitMQ如何保证⾼可⽤的？queue数据在节点之间如何同步的？死信队列 如何实现的？
- [ ] kafka的offset怎么管理
- [ ] 消息队列消费端的推和拉有什么区别
- [ ] MQ队列⽤了哪些，Kafka，那⾦融场景下，Kafka如何保证消息不丢失？ack = -1，Leader-->ISR写⼊所有的follower
- [ ] 

### 



#### Network

##### 1. TCP/UDP

- [ ] TCP和UDP的区别,TCP三次握手？SEQ 是干什么的？两次握手行不行？　TCP Fast Open了解么,TCP的拥塞控制是怎么做的
- [ ] tcp 拥塞策略(高频)
- [ ] tcp协议栈中TIME_WAIT字段的作用(高频)
- [ ] tcp的time_wait状态和colse_wait状态
- [ ] 如何解决tcp的粘包问题
- [ ] 如何理解网络模型

##### 2.DSN

- [ ] 说说CDN的架构，缓存的实现, 用户的访问流程，调度是怎么选择机房的
- [ ] DSN 查询过程,递归查询和迭代查询的区别

##### 3.HTTP

- [ ] HTTP协议的发展,HTTP缓存实现方式，跟HTTP缓存相关的头部字段，HTTP 302了解么
- [ ] HTTP和HTTPS有什么区别、HTTPS的访问流程、CA中心是什么，确定加密协议过程
- [ ] http的状态码含义：502 504区别 301 302区别，分析一下系统 502 和504 可能的原因
- [ ] http2的优势
- [ ] http header有哪些部分
- [ ] 长连接 http长连接和websocket对比
- [ ] 长轮询和短轮询了解吗
- [ ] rpc和http优劣

##### 4.其他

- [ ] session cookie区别，分别存哪里？跨域问题如何解决
- [ ] 





#### System

#### Nginx

- [ ] nginx反向代理怎么配置
- [ ] nginx平滑重启什么原理



#### Your project



#### Golang

##### 1. 并发

- [ ] sync.map、sync.pool、sync.once 的原理

##### 2.底层原理

- [ ] map 底层实现&sync.Map的区别
- [ ] Context 的使用，用法，底层实现（高频）
- [ ] go内存分配
- [ ] 聊到了内存对齐，说说为什么要内存对齐，原理原因
- [ ] chan 底层实现 、 make(chan struct {})  和 make(chan bool) 在chan的源码实现上有什么区别，chan，什么时候会panic
- [ ] go gc的实现与触发机制
- [ ] go 内存分配
- [ ] go gmp 调度模型实现。从早期1.x版本演进到1.14，做了哪些大改变? time.sleep阻塞时,网络请求阻塞时,调用系统方法时,GMP怎么流转的？
- [ ] go 读写锁和互斥锁的区别和使用场景
- [ ] go panic 的机制。defer,recover的结合使用（golang的panic怎么理解，怎么处理，recover 一般怎么处理）
- [ ] interface 底层实现，怎么判空？
- [ ] reflect 的使用
- [ ] 是否有必要使用协程池?好坏处?举个使用场景
- [ ] go timer底层的实现 .  时间调度可以用哪些数据结构来实现?( 如 回答  时间轮: nginx 。最小堆: go timer 链表等 )
- [ ] 谁负责来标记抢占? 有如下代码 go func(){ for{}}() 死循环，能否被抢占?1.14版本前会有什么问题？
- [ ] etcd 中 watch 底层是如何实现的？
- [ ] for(i<1000000;i++){go fun(){ …time.sleep（10秒）}()} 同时启动100万协程。会有什么问题?影响面: 如(gc 检查,死锁检查) 怎么解决?
- [ ] go 调度模型。发生网络io.会怎么调度。发生阻塞的IO会怎么调度。epoll



##### 3.基本问题

- [ ] goroutine(协程)和线程是什么关系，goroutine是如何调度的？
- [ ] 如何控制goroutine并发数？
- [ ] 逃逸分析能做什么？如何进行逃逸分析？
- [ ] 有缓冲channel和无缓冲channel区别？
- [ ] slice 和 array的区别？
- [ ] slice的底层实现
- [ ] init函数如何使用？
- [ ] []byte{}  string 的区别
- [ ] context 的使用
- [ ] defer关键字的作用, 多个defer的调用顺序？
- [ ] go 内存分配，大小对象内存分配区别？多级分配的优点是什么？
- [ ] new和make的区别(高频)
- [ ] go 性能问题的定位( pprof,各项指标)
- [ ] 讲一下Golang 空结构体
- [ ] golang 的map 插入顺序和输出顺序是一样的吗？随机输出
- [ ] 实现一个并发模型。生产者消费者
- [ ] select和epoll的区别
- [ ] 



#### design

- [ ] 如何设计一个秒杀系统
- [ ] trace了解吗
- [ ] 实时战力前100排行榜怎么设计
- [ ] rank系统怎么设计
- [ ] 有10亿用户，让你设计一个社区架构。包括点赞 发帖 删帖 的积分架构、期间一直在追问设计合不合理
- [ ] 给你1亿个URL 。爬取信息。会遇到什么问题？从 CPU 磁盘 网络 等方面。这个聊了很多。
- [ ] 描述 推送架构设计
- [ ] 线上熔断降级怎么做的
- [ ] 全站Push 的 运营误操作如何防止
- [ ] 亿级帖子，对应的评论表如何设计
- [ ] 设计一个短连（一个长的url地址，转为一个短的）
- [ ] 设计一个高可用的稳定的并发模型处理HTTP请求
- [ ] 一致性hash算法
- [ ] 限流策略
- [ ] 高并发的生产者消费者模式
- [ ] 编码过程中你比较注意哪一些
- [ ] 你负责的系统中，你一般关注哪些点，怎么保证你关注的点不出问题
- [ ] 实现MapReduce中的Map,例如: cat file.txt | ./go-reader　-cmd "${cmd} " > result.txt
  - go-reader为接受cat file.txt的输入lines，将lines给${cmd}处理，最后输出结果
  - 进程间怎么通信，go-reader要考虑协程池吗，为什么
- [ ] 不用定时任务的方式，实现一条消息定时发送或者任务到点执行
- [ ] 说说定时任务系统怎么做的，什么是一个任务，一个任务的生命周期是什么样的
- [ ] 设计一个高并发、高可用的架构
  - 读比较多怎么设计
  - 写比较多怎么设计
  - 服务的负载均衡怎么做
  - MySQL 怎么部署，读写分离怎么做
  - MySQL索引是什么,什么数据结构，MyISAM与InnoDB索引的区别，假设有一张表，有a,b两个索引，索引会怎么选择？(a,b) 是联合索引时会怎么选择
  - MySQL的事物，有什么特征，ACID是怎么实现的，隔离级别有几种，MVCC是怎么实现的，乐观锁，悲观锁
  - 缓存的热Key和大Key怎么处理
  - 简单说说kafka的架构，我要实现消息的顺序消费怎么办



#### 分布式

- [ ] 分布式事务了解
- [ ] 分布式事务讲⼀下？结合项⽬想讲的可靠消息⼀致性实现⽅案 + 最⼤努⼒送达通知⽅案，最后也提到了单应⽤多DB（JPA）、TCC事务以及适⽤场景。
- [ ] 分布式锁
- [ ] 缓存和数据库⼀致性如何保证的？谈到了分布式锁，那详细讲讲分布式锁实现？redis setnx、redisson、zookeeper
- [ ] 介绍平滑负载均衡算法，实现





#### other

- [ ] 对比 mysql redis http 连接池的实现
- [ ] 





#### answer

[go_interview](https://github.com/xiaowei520/go_interview/blob/master/%E9%A2%98%E7%9B%AE%E8%AE%A8%E8%AE%BA/2020-04-14.md)

[gopher_reading](https://github.com/qichengzx/gopher-reading-list-zh_CN)

[go_question](https://github.com/qcrao/Go-Questions)

