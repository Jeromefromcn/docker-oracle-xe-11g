FROM wnameless/oracle-xe-11g:16.04

MAINTAINER Jerome Jiang <jeromefromcn@@gmail.com>

RUN mkdir /temp && mv /u01/* /temp

CMD mv /temp/* /u01/ && /usr/sbin/startup.sh && /usr/sbin/sshd -D
