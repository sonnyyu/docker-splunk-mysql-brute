FROM mysql:5.7
COPY ./mysqld.cnf /etc/mysql/mysql.conf.d
ENV MYSQL_ROOT_PASSWORD=password
RUN ln -fs /usr/share/zoneinfo/America/Los_Angeles /etc/localtime
RUN dpkg-reconfigure -f noninteractive tzdata
