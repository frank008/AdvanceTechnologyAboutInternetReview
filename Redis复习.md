# Redis复习

## 数据类型

1.redis的5种数据类型：
string 字符串（可以为整形、浮点型和字符串，统称为元素）
list 列表（实现队列,元素不唯一，先入先出原则）
set 集合（各不相同的元素）
hash hash散列值（hash的key必须是唯一的）
sort set 有序集合

2.string类型的常用命令：
自加：incr
自减：decr
加： incrby
减： decrby

3.list类型支持的常用命令：
lpush:从左边推入
lpop:从右边弹出
rpush：从右变推入
rpop:从右边弹出
llen：查看某个list数据类型的长度

4.set类型支持的常用命令：
sadd:添加数据
scard:查看set数据中存在的元素个数
sismember:判断set数据中是否存在某个元素
srem:删除某个set数据中的元素

5.hash数据类型支持的常用命令:
hset:添加hash数据
hget:获取hash数据
hmget:获取多个hash数据

6.sort set和hash很相似,也是映射形式的存储:
zadd:添加
zcard:查询
zrange:数据排序



# 