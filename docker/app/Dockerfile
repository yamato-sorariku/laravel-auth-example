FROM php:7-fpm

RUN apt-get update && apt-get install -y zip unzip && \
    docker-php-ext-install pdo_mysql && \
    curl -sS https://getcomposer.org/installer | php && \
    mv composer.phar /usr/local/bin/composer

