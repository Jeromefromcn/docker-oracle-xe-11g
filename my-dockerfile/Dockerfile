FROM wnameless/oracle-xe-11g

MAINTAINER Jerome Jiang <jeromefromcn@@gmail.com>

RUN mkdir /XE && mv /u01/app/oracle/oradata/XE/* /XE

CMD mv /XE/* /u01/app/oracle/oradata/XE/ && /usr/sbin/startup.sh && /usr/sbin/sshd -D
