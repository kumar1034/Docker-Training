FROM ubuntu
ADD https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.73/bin/apache-tomcat-9.0.73.zip /tmp
RUN apt-get update && \
    apt-get install -y unzip \
    unzip /tmp/apache-tomcat-9.0.73.zip /tmp/apache_server