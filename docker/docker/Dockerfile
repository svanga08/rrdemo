FROM ubuntu:16.04

MAINTAINER "RollsRoyce Corporation"
RUN apt-get update
RUN apt-get install -y apache2 telnet iputils-ping
ADD index.html /var/www/html/
EXPOSE 80
CMD ["apache2ctl","-D","FOREGROUND"]
