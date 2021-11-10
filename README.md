<center>大家好,我是石臻臻,这是  「kafka专栏」     连载中的第「<font color=red>N </font>」篇文章...</font> </center>

最近一段时间比较忙,原创写的有点慢,实战系列的文章也没有怎么写(实战系列文章写一篇至少要花费我周末满满的2天时间)
我又不想随便水水原创文章,所以干脆就一直拖更...  不过接下来我会尽量多花点时间来写写文章, 
在这之前,我总结了一下我将要写的kafka相关的内容, 也就总结出来了这么一份
<center> <font color=red size=5> <b>Kafka知识图谱</b> </font></center>

![](https://img-blog.csdnimg.cn/a7f242673a134df99c35951ac1feae98.png#pic_center)

图中写了已完成的部分可以直接点击链接跳转访问
kafka知识图谱访问链接 
<center>
<font color=red>
<a href="https://www.processon.com/view/link/618b2f20e0b34d73f7ed3fd5">kafka知识图谱点击这里</a>
</font>
</center>

当然这份图谱还有很多遗漏的知识点,欢迎大家联系我在图谱里面加上它
里面很多内容都是没有完成的, 也有一些部分内容
比如 <font color=red size=4> <b>【群友常见问题系列】</b> </font>是在 <font color=red size=4> <b>【滴滴技术交流群】</b> </font>里面都回答过的。
这些问题有的可能几句话就可以讲清楚,但是我并不想只是单纯的跟你说问题答案就是XX
而是我再回答了你答案之后,我还能给你发出来一个链接让你自己看下为什么是这样

所以这一份知识图谱,我会把<font color=red size=4> <b>【原理源码分析系列】</b> </font>和<font color=red size=4> <b>【实战系列】</b> </font> 作为第一优先级来完成。

我会在未来的时间慢慢的把这份知识图谱补齐, 文章会首发在 公众号：【石臻臻的杂货铺】, 欢迎订阅

水平有限,如果文章有误还请欢迎批评指正!~


# kafka知识图谱

当前正在连载kafka系列专栏, 我列出来了一份kafka知识图谱
总共分为以下几个模块

## 原理源码分析系列

> kafka各个模块 深入源码去分析 并总结原理

|文章标题  | 链接 |是否完成|
|--|--|--|
| 创建Topic的源码解析 | [创建Topic的源码解析](https://www.szzdzhp.com/kafka/Source_code/source-create-topic.html )|
|分区副本的分配规则|[分区副本的分配规则](https://www.szzdzhp.com/kafka/Source_code/source-fenpei-rule.html)|
|删除Topic源码解析(附教学视频)|[删除Topic源码解析(附教学视频)](https://www.szzdzhp.com/kafka/Source_code/source-del-topic.html)|
|分区扩容源码解析|[分区扩容源码解析](https://www.szzdzhp.com/kafka/Source_code/source-alert-topic.html)|
|分区副本重分配源码原理分析(附配套教学视频)|[分区副本重分配源码原理分析(附配套教学视频)](https://www.szzdzhp.com/kafka/Source_code/source-code-pr.html)
|/log_dir_event_notification的LogDir脱机事件通知|[/log_dir_event_notification的LogDir脱机事件通知](https://www.szzdzhp.com/kafka/Source_code/log-dir-event.html)
|Controller中的状态机|[Controller中的状态机]()|
|Controller启动过程以及选举流程源码分析|[Controller启动过程以及选举流程源码分析]()|
|Controller与Brokers之间的网络通信源码分析|[Controller与Brokers之间的网络通信源码分析]()|
|优选副本逻辑源码分析|[优选副本逻辑源码分析]()|
|协调器作用|[协调器作用]()|
|Broker上线源码分析|[Broker上线源码分析]()|
|Broker下线源码分析|[Broker下线源码分析]()|
|副本同步限流机制|[副本同步限流机制]()|
|副本同步机制|[副本同步限流机制]()|
|Kafka中的动态配置源码分析|[Kafka中的动态配置源码分析]()|
|LogManager 日志管理源码分析 .|[LogManager 日志管理源码分析 .]()|
|过期Log清理机制|[过期Log清理机制]()|
|Log数据存储|[Log数据存储]()|
|一文了解Kafka ACK 权限控制|[Kafka ACK 权限控制]()|
|一文理解什么是kafka 事务|[一文理解什么是kafka 事务]()|
|一文链接kafka生产者生产消息全过程|[一文链接kafka生产者生产消息全过程]()|
|生产者生产消息的分区分配策略|[生产者生产消息的分区分配策略]()|
|生产者序列化方式|[生产者序列化方式]()|
|一文详解消费者消费全流程|[一文详解消费者消费全流程]()|
|消费组如何提交消费的|[消费组如何提交消费的]()|
|消费组重平衡|[消费组重平衡]()|


## 运维手册系列
> 包含所有运维人员常用命令
> 和各种排查问题手册


|文章标题  | 链接 |是否完成|
|--|--|--|
|全网最全最详细运维命令合集!!!|[全网最全最详细运维命令合集!!! =>所有命令都在这里](https://www.szzdzhp.com/kafka/op/op-for-kafka-all.html)||
|kafka-reassign-partitions.sh分区副本重分配、数据迁移、副本扩缩容(附教学视频)|[kafka-reassign-partitions.sh分区副本重分配、数据迁移、副本扩缩容](https://www.szzdzhp.com/kafka/op/op-partition-reasignment.html)|
|kafka在zookeeper 中的存储结构讲解|[kafka在zookeeper 中的存储结构讲解](https://www.szzdzhp.com/kafka/other/kafka-zk-data.html)|
|server配置文件大全|[server配置文件大全]()|
|producer配置文件大全|[producer配置大全]()|
|consumer配置文件大全|[consumer配置大全]()|



## 实战问题总结系列
> 该系列会将群友们生产环境碰到的实际问题,总结成文章,给出 <font color=red font=6 >**排查过程->问题原因->如何解决->问题涉及到的原理和知识点**</font>。

|文章标题  | 链接 |是否完成|
|--|--|--|
|【实战】分区重分配可能出现的问题和排查问题思路(生产环境实战,附视频)|[【实战】分区重分配可能出现的问题和排查问题思路(生产环境实战,附视频)]()|
|【实战】删除Topic失败常见异常和排查思路和解决方案|[【实战】删除Topic失败常见异常和排查思路和解决方案]()|
|【实战】数据重分区执行完成之后,忘记了执行-verify 将限流信息移除,后续如何才能移除限流信息呢？|[【实战】数据重分区执行完成之后,忘记了执行-verify 将限流信息移除,后续如何才能移除限流信息呢？]()|
|TODO...|TODO...|



## 群友问题合集系列
> 该系列会将<font color=red font=6 > **滴滴技术交流群群友**</font> 们经常问比较典型的问题, 给出 **问题** 和 **答案**, 该部分可能是属于 Q&A 的短篇幅形式
> 但是对应的原理和知识 会给出链接,方便理解和系统性的学习。

|问题描述  | 链接 |是否完成|
|--|--|--|
|Kafka磁盘满了会导致什么异常?||
|一不小心删除了/broker/topic下的某个topic节点会有什么影响？||
|kafka 中一个消费组不再使用后,它的消费元数据(消费的offset信息)会自动删除么?)||
|【实战】数据重分区执行完成之后,忘记了执行-verify 将限流信息移除,后续如何才能移除限流信息呢？||
|如果kafka没有消费者,消息一直堆积,会不会导致kafka挂掉?||
|kafka生产者的key值,如果不需要设置,采用默认的round-bobin策略写的话,是设置为null或者空值都可以吗?||
|分区分配的策略？||
|ack=-1，是min.Insync.replica中的follower落盘成功就发ack还是全部的follower都要落盘成功？||
|_consumer_offset中的数据是如何保留的,有的说是通过Compact策略只保留每个key最新的位移,但是这个策略还有控制时间的参数 offsets.retention.minutes来控制删除过期位移数据,现在比较疑惑,麻烦不忙的时候帮忙解答一下这个问题？||
|kafka消费慢,你们一般遇到有哪些原因？||
|kafka集群一般在不影响性能的情况下? 建议多少个topic合适？||
|限制迁移Topic的时候throttle是50M为什么网卡流量上的是600M? 是一批次12个分区一起迁移吗？||
|topic切换新leader的时候会丢失数据吗？||
|Kafka的分区和副本数量是由什么决定的, 怎么设置比较合理？||
|一个Broker节点上的某块数据盘坏了,需要更换,有什么最佳实践吗？||
|有遇到过topic过期时间,但是到了过期时间却没有正常删除的情况吗?||
|Kafka有个消费组堆积了.有什么好的解决方法吗？一直在重新平衡||
|使用kafka生产者怎么实现重试机制？||


## 面试集锦系列
> 总结常问的kafka面试题,并给出简单答案,最终会引导到相关具体的知识点。

|问题描述  | 链接 |是否完成|
|--|--|--|
|Kafka中ISR、AR是什么？ISR的伸缩又是指什么？||
|Kafka中的HW、LEO、LSO、LW等分别代表什么？||
|如何保证消息的顺序性?||
|简单描述一下生产者发送消息的过程?||
|有哪些情形会造成重复消费?||
|那些情景下会造成消息漏消费?||
|简单描述一下创建/删除Topic的整个流程?||
|优先副本是什么？它有什么特殊的作用？||
|简述Kafka的日志目录结构。Kafka中有那些索引文件?||
|简述kafka过期数据清理策略和简单流程?||
|Kafka的那些设计让它有如此高的性能？||
|Kafka中的事务是怎么实现?||
|TODO....|待补充.... |


## 设计方案和思考系列
> 该部分属于 对kafka里面的一些设计做一些思考, 还有本人在对kafka二开和LogiKM开发过程中碰到的一些问题和设计方案。
> 

|文章标题  | 链接 |是否完成|
|--|--|--|
|如何修改分区的指定副本为Leader 设计方案| [如何修改分区的指定副本为Leader 设计方案](https://www.szzdzhp.com/kafka/other/perrfer-leader.html)|
|关于分区副本分配相关的Bug…|[关于分区副本分配相关的Bug…](https://www.szzdzhp.com/kafka/other/maybe-bug1.html)|

## kafka监控系列 
> 主要讲解 如何用[滴滴开源Kafka一站式运维管控平台](https://github.com/didi/LogiKM) 来管控我们的kafka集群
> 
|文章标题  | 链接 |是否完成|
|--|--|--|
|Kafka的灵魂伴侣LogIKM1)之集群的接入及相关概念讲解|[Kafka的灵魂伴侣LogIKM(1)之集群的接入及相关概念讲解](https://www.szzdzhp.com/Logi_Kafka/logikm1.html)|
|Kafka的灵魂伴侣LogIKM(2)之kafka针对Topic粒度的配额管理(限流)|[Kafka的灵魂伴侣LogIKM(2)之kafka针对Topic粒度的配额管理(限流)](https://www.szzdzhp.com/Logi_Kafka/logikm2.html)||
|Kafka的灵魂伴侣LogIKM(3)之运维管控--集群列表|[Kafka的灵魂伴侣LogIKM(3)之运维管控--集群列表]()|
|Kafka的灵魂伴侣LogIKM(4)之运维管控–集群运维(数据迁移和集群在线升级)|[Kafka的灵魂伴侣LogIKM(4)之运维管控–集群运维(数据迁移和集群在线升级)]()|
|Kafka的灵魂伴侣LogIKM(5)之运维管控–平台管理(用户管理和平台配置)|[Kafka的灵魂伴侣LogIKM(5)之运维管控–平台管理(用户管理和平台配置)]()|


## 常见异常
> 该系列会列出一些常见的异常 以及如何解决

|文章标题  | 链接 |是否完成|
|--|--|--|
|【kafka异常】kafka 常见异常处理方案(持续更新! 建议收藏)|[【kafka异常】kafka 常见异常处理方案(持续更新! 建议收藏)](https://www.szzdzhp.com/kafka/other/kafka-errors.html)|



# 归档
文章会首发在公众号：【石臻臻的杂货铺】
所有文章会在我个人网站:  [szzdzhp.com 石臻臻的杂货铺](szzdzhp.com/kafka) 存档
同时也会在 GitHub上备份, 想要收藏的同学可以帮忙Star一下:  [kafka知识图谱](https://github.com/shirenchuang/kafkadoc)
也欢迎进由滴滴工程师创建的<font color=red size=4>【kafka中文社区】</font>知识星球,<font color=red size=4>限时免费</font>

# 进滴滴技术交流群
需要进【高质量滴滴技术交流群】的, 请扫码二维码加我微信
群内有多位滴滴技术专家值班答疑,技术氛围浓厚,不可闲聊。

 备注：<font color=red size=4> <b>称呼-岗位方向-公司-进群</b> </font>

及时获取推文,和领取后续的PDF请扫码并关注。

<center> 
 <img src="https://img-blog.csdnimg.cn/3cc7341b79cd41e7a8bd2a0c5f8bf2df.png" height="160" width="160"> 
  <img src="https://img-blog.csdnimg.cn/d26e6a994afc42128f330363b17869a6.png" height="160" width="160"> 
</center>





