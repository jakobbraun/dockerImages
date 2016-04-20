FROM php:5.6-apache
RUN apt-get update && docker-php-ext-install mysql
COPY apache2.conf /etc/apache2/apache2.conf
