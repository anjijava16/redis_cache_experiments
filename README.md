# redis_cache_experiments
Redis cache experiment's

## Install 
1. brew install redis

##  Start Redis
1. brew services start redis
2. redis-server

## Test Redis

You can test if Redis is running by opening another Terminal window and typing:

redis-cli

redis-cli -h 127.0.0.1 -p 6379

```
welcome@jaisairams-Laptop ~ % redis-cli -h 127.0.0.1 -p 6379
127.0.0.1:6379> hi
(error) ERR unknown command 'hi', with args beginning with:
127.0.0.1:6379> ping
PONG
127.0.0.1:6379>
127.0.0.1:6379>
127.0.0.1:6379>


```
