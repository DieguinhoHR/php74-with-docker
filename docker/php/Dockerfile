FROM php:7.4-fpm-alpine

RUN apk update && apk add bash

RUN docker-php-ext-install pcntl
RUN docker-php-ext-install pdo_mysql

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
