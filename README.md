# Sample for ASP.NET Core 1.0 with Mysql and Docker 

This is a sample application for showing ASP.NET Core 1.0 with MYSQL backend and deployed using Docker and Docker-Compose

## How to run?

Make sure you have the following tools installed 
- Docker for Mac/Windows
- ASP.NET Core 1.0 
- Visual Studio Code 
- node, npm, bower, gulp

Make sure you have ready to connect dockerized host, connect your host 

- on macOS: eval $(docker-machine env {machine-name})
- on Windows: @FOR /f "tokens=*" %i IN ('docker-machine env {machine-name}') DO @%i

## Run the code 

- cd src/aspnet-mysql
- docker-compose build
- docker-compose up -d
- docker-machine ip {machine-name}

Open your browser and navigate to http://{docker-machine ip}:5000 

## Docker Image Url

[ups216/aspnetmysql](https://hub.docker.com/r/ups216/aspnetmysql/)

## Detailed instructions can ben found on my blog

-[docker4dotnet #1 前世今生 & 世界你好](http://devopshub.cn/2016/07/08/docker4dotnet-1-overview-and-helloworld/)

-[docker4dotnet #2 容器化主机](http://devopshub.cn/2016/07/13/docker4dotnet-2-docker-machine-create-dockerized-hosts/)

-[docker4dotnet #3 .net猿和小鲸鱼的苹果山之旅](http://devopshub.cn/2016/07/27/docker4dotnet-3-macos-aspnet-mysql-docker-compose/)

![](/images/qrcode-devopshub.jpg)

## Video Demo

[http://v.qq.com/x/page/b031665qwth.html](http://v.qq.com/x/page/b031665qwth.html)




