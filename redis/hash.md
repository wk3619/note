# redis

#### 全局命令
### 哈希
设置值
~~~
hset key field value
~~~
获取
~~~
het key field
~~~
删除
~~~
hdel key field [field]
~~~
计算fieid 个数
~~~
hlen key
~~~
批量
~~~
hmset key field value [field value ...]
hmget key field [field]
~~~
判断key是否存在
~~~
hexists key field 
~~~
获取所有field
~~~
hkeys key
~~~
所有value
~~~
hvals key
~~~
或有field-value
~~~
hgetall key
~~~
增长
~~~
hincrby key field
hincrbyfloat key field
~~~
计算value长度
~~~
hstrlen key field
~~~
#### 使用场景

