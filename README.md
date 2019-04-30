# elasticsearch-kibana-docker-sample

```shell
## install & start
$ git clone git@github.com:yoshihir/elasticsearch-kibana-docker-sample.git
$ cd elasticsearch-kibana-docker-sample
$ docker-compose up
```
```shell
## health check
$ curl http://localhost:9201/_cluster/health?pretty
## cluster topology
$ curl http://localhost:9201/_cat/nodes?v
## master node
curl http://localhost:9201/_cat/master?v
```