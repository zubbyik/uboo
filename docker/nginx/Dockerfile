FROM nginx:1.13

RUN apt-get update

ADD files /

RUN usermod -u 1001 www-data

WORKDIR /var/www
