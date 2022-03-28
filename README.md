# jenkins_docker-compose   
* 2021-4-14 jianshulinux   
* 开始部署
```yaml   
docker-compose up -d    
```   
* 访问地址   
```yaml   
localhost:8080 or 8081   
```   
* 管理员密码进入容器中查看   
```shell   
docker exec -it 容器id /bin/bash   
cat <jenkins提供的路径>   
```   
收工！
