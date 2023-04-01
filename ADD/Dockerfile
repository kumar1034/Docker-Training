FROM almalinux
ADD https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.73/bin/apache-tomcat-9.0.73.zip /tmp
RUN dnf install -y unzip \
    unzip /tmp/apache-tomcat-9.0.73.zip /tmp/apache_server
CMD ["nginx", "-g", "daemon off;" ]