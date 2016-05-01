FROM mysql:5.7
MAINTAINER "n.matayoshi" <n.matayoshi@gmail.com>
RUN usermod -u 1000 mysql
RUN mkdir -p /var/run/mysqld && \
  chmod -R 777 /var/run/mysqld
