# Redis on docker swarm

``` 
$ docker swarm init

$ docker network create -d overlay --scope swarm chrissoft

$ docker stack deploy -c redis.yml redis

```
