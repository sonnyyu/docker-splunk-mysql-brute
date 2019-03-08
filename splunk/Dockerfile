FROM splunk/splunk:latest
USER root
LABEL maintainer "sonnyyuirm@gmail.com"
ENV SPLUNK_START_ARGS="--accept-license" \
    SPLUNK_PASSWORD="password"
RUN mkdir -p /var/log/mysql 
RUN ln -fs /usr/share/zoneinfo/America/Los_Angeles /etc/localtime
RUN dpkg-reconfigure -f noninteractive tzdata
RUN touch /var/log/mysql/all.log 
RUN chmod 777 -R /var/log/mysql
