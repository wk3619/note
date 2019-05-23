# redis

#### 全局命令
### 有序集合
添加
~~~
zadd key score member 
-ch
-incr 
~~~
计算成员个数
~~~
zcard key
~~~
计算成员分数
~~~
zscore key member
~~~
计算成员排名
~~~
zrank key member
zrevrank key member
~~~
删除 
~~~
zrem key member
~~~
增加成员分数
~~~
zincrby key increment member
~~~
返回指定排名范围的成员,withscores 选项会同时返回分数
~~~
zrange    key start end [withscores]
zrevrange key start end 
~~~
返回指定分数范围的成员,limit offset count 限制输出的起始位置和个数
~~~
zrangebyscore    key min max [withscores][limit offset count]
zrevrangebyscore key min max ...
~~~
同时min和max还支持开区间，闭区间，-inf和+inf 代表无限小和无限大。
~~~
zrangebyscore user:ranking (200 +inf withscores
~~~
#### 
