# docker-2048
Docker化2048 game

## 镜像特点

- 2015/7/3 继承基础镜像docker-apache

## 使用方法

- 获取代码并构建

        git clone https://github.com/Dockerlover/docker-2048.git
        cd docker-2048
        docker build -t docker-2048 .

- 运行容器

        docker run -d -it --name g2048 -p 8080:80 docker-2048
