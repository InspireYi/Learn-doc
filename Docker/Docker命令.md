docker run  -- 运行一个docker容器  

docker images -- 查看docker 镜像  

docker ps -- 查看正在运行的docker  

docker container ls -- 查看正在运行的docker  

docker build -t [name] . --创建一个docker镜像，名字为name，文件上下文为当前目录  

docker history  -- 查看该镜像的构建历史  

docker push  -- 推送docker镜像至docker仓库  

docker pull  -- 从docker仓库中获取docker镜像  

docker stop -- 停止一个docker镜像的运行  

docker tag  -- 给docker镜像打tag  

docker rm -- 删除docker容器  

docker rmi  -- 删除docker host中的镜像  

docker search  -- 从docker hub中查询镜像  

docker attach  -- 不开启新终端进入容器，一般用于查看开启容器后的输出  

docker exec  -- 开启新终端进入容器，可在容器内部做别的操作  

docker logs -f  -- 持续显示容器中的log   