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

# 