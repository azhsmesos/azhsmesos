<h1><img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> Hey! Nice to see you.</h1>


<p>Welcome to my page! </br> I'm azhsmesos, Free developer from  <b>Beijin, China</b>
<h3>Things I code with</h3>
<p>
  <img alt="DevStream " src="devstream.png" height="200" width="200">
</p>

<h3>Open source projects 🎁</h3>

- <a href="https://github.com/mosn/layotto"><b>layotto</b></a>
- <a href="https://github.com/apache/rocketmq"><b>Apache RocketMQ</b></a>
- <a href="https://github.com/apache/pulsar"><b>Apache Pulsar</b></a>
- <a href="https://github.com/devstream-io/devstream"><b>DevStream</b>

### 个人项目

- 实现brainfuck的即时编译器 (rust): https://github.com/azhsmesos/jit-Instantaneous-compiling
- 简单基于bitcask模型实现的单机版kv（golang）：https://github.com/azhsmesos/bitcask_db
>- TSDB (golang)：单机版test用：
>   
>  微信公众号：Azhs的技术小屋
   > 
>   github链接：https://github.com/azhsmesos/tsdb
>   - 基于lsm的实现，memtable存储热数据（2h），磁盘存储冷数据
>   - 考虑wisckey kv分离，ssd并行写代替顺序io
>   - lock-free
>   - 基于aep这类的Persistent Memory 代替wal
>   - 读写分离
>   - 实现高效的内存查询数据结构（avltree、skiplist、红黑树）
>   - 基于可插拔式的压缩算法（ZSTD压缩、Snappy压缩）
>   - mmap内存拷贝
>   - 类似es的倒排索引
>   - 垂直写，水平查，序列分流，冷热读写
>   - 自定义Marshal编解码
>   - RoaingBitMap 优化
>   - 优化的正则查询（fastRegexMatcher）