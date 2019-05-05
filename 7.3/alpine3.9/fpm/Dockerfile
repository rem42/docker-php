FROM php:7.3-fpm-alpine

RUN apk add --no-cache libzip-dev

RUN docker-php-ext-configure zip --with-libzip=/usr/include

RUN docker-php-ext-install zip
