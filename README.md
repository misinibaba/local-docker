# local-docker
### 准备工作：
1.本地安装docker && docker-compose


2.docker 添加国内镜像加快下载速度


3.docker本地环境目录盘符 在docker中设置share drives 


### 使用：
1.clone 仓库到本地


2.进入files目录，执行docker-compose up 命令，如需要守护进程运行，则是docker-compose up -d


### 注意事项：

1.连接数据库或redis的地方，将数据库IP或域名改为mysql-db 或 redis-db


2.本地端口与docker端口冲突问题


3.命令行在管理员模式下操作

