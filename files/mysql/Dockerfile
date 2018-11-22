FROM mysql:5.7

#  set timezome
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt-get update 
RUN apt-get install -y sphinxsearch 
RUN apt-get install -y cron  
RUN apt-get install -y vim
