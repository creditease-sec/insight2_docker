# insight2 docker
---
洞察2 一键启动简介
采用docker-compose 启动mysql,redis,服务

---


### 1. 快速开始(Quick Start) 
---
(1) 使用Docker Compose

- [docker-compose](https://docs.docker.com/compose/install/)

```bash
git clone https://github.com/creditease-sec/insight2_docker.git
cd insight2_docker
sudo docker-compose up

```
(2) 系统登录


```bash
地址：http://localhost:8000
帐号：admin
密码：admin!Aa2020
后台地址：http://localhost:8000/#/admin
```
(2) 版本更新

```bash
docker-compose pull && docker-compose up
or
sudo docker-compose pull && sudo docker-compose up

```

