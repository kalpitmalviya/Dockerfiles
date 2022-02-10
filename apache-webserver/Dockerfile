FROM centos:latest

MAINTAINER Kalpit

RUN yum install httpd -y

RUN yum install net-tools -y

RUN echo It-works! > /var/www/html/index.html

EXPOSE 80

CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
