FROM php:fpm

LABEL maintainer = 'Bayu Bimantara <bayubimantarar@gmail.com>'

RUN apt-get install curl && \
    docker-php-ext-install pdo pdo_mysql && \
    curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

EXPOSE 9000
