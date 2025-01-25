immyhu@hujiamingdeMacBook-Pro Redis-Cluster % docker exec -it redis-cluster-redis-node-1-1 bash             
root@redis-node-1:/data# redis-cli --cluster create \
redis-node-1:7001 redis-node-2:7002 redis-node-3:7003 \
redis-node-4:7004 redis-node-5:7005 redis-node-6:7006 \
--cluster-replicas 1
>>> Performing hash slots allocation on 6 nodes...
Master[0] -> Slots 0 - 5460
Master[1] -> Slots 5461 - 10922
Master[2] -> Slots 10923 - 16383