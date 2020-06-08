# ansible-redis-cluster
MÔ HÌNH REDIS CLUSTER 6 NODE: 1 Master, 2 Slave, 3 Sentinal
# deploy 
+ ansible-playbook -i redis.hosts redis.yml --tags setup
+ ansible-playbook -i redis.hosts redis.yml --tags config
+ ansible-playbook -i redis.hosts redis_bootstrap.yml

