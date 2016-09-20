FROM php:7-apache
RUN apt-get update \
  && apt-get install -y apt-utils libfreetype6-dev libjpeg62-turbo-dev libpng12-dev libmcrypt-dev php-soap \
  && docker-php-ext-install pdo_mysql mysqli mbstring gd iconv mcrypt
