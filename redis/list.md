# redis

#### 全局命令
### 列表
添加
~~~
rpush key value [value ...]
lpush key value
linsert key before|after pivot value
~~~
查找,end包含自身
~~~
lrange key start end
~~~
获得索引下标元素
~~~
lindex key index
~~~
列表长度
~~~
llen key
~~~
删除
~~~
lpop key
rpop key
lrem key count value
ltrim key start end
count>0 左到右
count<0 右到左
count=0 所有
~~~
修改
~~~
lset key index newValue
~~~
阻塞
~~~
blpop key [key] timeout
brpop key [key] timeout
~~~
#### 使用场景
消息队列
文章分页

