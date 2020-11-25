# redis-tutorials
redis-tutorials

set key value

get key value

keys *

del key

mset key value key value

mget key key key

ttl key

flushall

set key value

expire key second

setex key sec value

setex name2 40 "Vikki"

setnx key value

setnx name "Sunil"



incr key

decr key

incrby key value

decrby key value

psetex key milliseconds value

append key value

strlen key

msetnx key value [key value ...] 


 hset key field value  
 
 hget key field  
 
 hmset key field value [field value ...]
 
 hmget key field [field ...]
 
 hgetall key 
 
 hlen key 
 
 hstrlen key field  
 
 hkeys key 
 
 hvals key 

 hdel key field [field ...]

hsetnx key field value

hexists key field 

hincrby key field increment 
 
hincrbyfloat key field increment  

lpush key value [value ...]

rpush key value [value ...] 

lpop key 

rpop key

llen key

linsert key BEFORE|AFTER pivot value

sadd key member [member ...] 

scard key

sunion key [key ...] 

sinter key [key ...]    

sdiff key [key ...]   

smembers key  

srem key member [member ...]

spop key [count]

sdiffstore destination key [key ...] 

sinterstore destination key [key ...]

sunionstore destination key [key ...]

sismember key member

zadd key score member

zcard key 

zcount key min max 

zrange key start stop

zrange key start stop [WITHSCORES] 

zrem key member [member ...] 

zrank key member 

zrevrank key member

zrangebyscore key min max

zrangebyscore key min max [WITHSCORES]
