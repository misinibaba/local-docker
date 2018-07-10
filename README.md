# local-docker
### 准备工作：
1.本地安装docker && docker-compose


2.docker 添加国内镜像加快下载速度


3.docker本地环境目录盘符 在docker中设置share drives 


### 使用：
1.clone 仓库到本地


2.进入files目录，执行
```
docker-compose up
```
命令，如需要守护进程运行，则需要加上-d参数
```
docker-compose up -d
```


### PHP版本切换
默认为7.1版本，还支持5.6和5.4，需要切换则到files目录下执行

```
$ docker-compose -f docker-compose54.yml up --build
$ docker-compose -f docker-compose56.yml up --build
```
第一次切换构建后，则可以回到正常使用
```
docker-compose up
```


### 注意事项：

1.连接数据库或redis的地方，将数据库IP或域名改为mysql-db 或 redis-db


2.本地端口与docker端口冲突问题


3.命令行在管理员模式下操作

