# redis

#### 全局命令
### 集合
添加
~~~
sadd key element [element ...]
~~~
删除
~~~
srem key element
~~~
计算成员个数
~~~
scard key
~~~
是否在集合中
~~~
sismember key element
~~~
计算成员排名
~~~
zrank key member
zrevrank key member
~~~
返回随机
~~~
srandmember key [count]
~~~
集合中弹出
~~~
spop key
~~~
所有元素
~~~
smembers key
~~~
###### 集合间操作
交集
~~~
sinter key 
~~~
并集
~~~
suinon key
~~~
差集
~~~
sdiff key
~~~
结果保存
~~~
sinterstore destination key [key ...]
sunionstore destination key 
sdiffstore destination key
~~~
#### 使用场景
标签
~~~
sadd
~~~
抽奖
~~~
spop
srandmember
~~~
社交
~~~
sadd
sinter
~~~

