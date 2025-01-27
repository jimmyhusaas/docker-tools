可以用這兩個指令測試rediscluster是否啟動成功
docker exec -it redis-cluster-redis-node-1-1 redis-cli -c -p 7001 CLUSTER INFO
docker exec -it redis-cluster-redis-node-1-1 redis-cli -c -p 7001 CLUSTER nodes
