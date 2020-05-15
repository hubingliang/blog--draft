---
title: '用 Docker 部署可以打包 Docker 的 Gitlab Webhook + jenkins 构建环境'
date: 2019-07-03 17:44:43
tags: [Docker]
published: false
hideInList: false
feature: 
---
**开始之前确认安装好如下环境**

1. [Docker](https://www.docker.com/)
2. [docker-compose](https://docs.docker.com/compose/)

# 主要流程

1. gitlab push event
2. gitlab webhook => jenkins
3. jenkins 调用 docker 构建项目

# 搭建

