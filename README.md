# 镜像仓库使用方法

[**images.txt**](https://github.com/fuzhengwei/docker-image-pusher/blob/main/images.txt)

```java
mysql:8.0.32
redis:6.0.6
rediscommander/redis-commander:latest
rabbitmq:3.12.9
nacos/nacos-server:v2.0.4
bladex/sentinel-dashboard:1.8.7
apache/rocketmq:5.1.0
apacherocketmq/rocketmq-dashboard:latest
registry:latest
elasticsearch:7.17.1
kibana:7.17.1
logstash:7.17.1
nginx:latest
seataio/seata-server:2.0.0
zookeeper:3.8
bitnami/kafka:3.6.2
nickzurich/kafka-eagle:3.0.1
apache/skywalking-oap-server:10.0.1
apache/skywalking-ui:10.0.1
bitnami/prometheus:2.53.1
grafana/grafana:11.1.1
jenkins/jenkins:2.469
portainer/portainer:latest
logstash:8.14.3
canal/canal-server:v1.1.7
slpcat/canal-adapter:v1.1.4
vulhub/xxl-job:2.2.0-executor
vulhub/xxl-job:2.2.0-admin
```

1. 在 `images.txt` 添加你需要的镜像（PR方式提交），你可以从 [https://hub.docker.com/](https://hub.docker.com/) 搜索需要的镜像后添加。
2. 新添加镜像，需要等待1分钟同步。之后通过命令 `docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/mysql` 拉取你需要的镜像，如果有版本号，可以添加。如；`mysql:8.0.32`

---

- 参考仓库 [@tech-shrimp/docker_image_pusher](https://github.com/tech-shrimp/docker_image_pusher)
