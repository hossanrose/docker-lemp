FROM php:fpm-alpine
RUN echo http://dl-2.alpinelinux.org/alpine/edge/community/ >> /etc/apk/repositories
RUN apk --no-cache add shadow && usermod -u 1001 www-data
RUN docker-php-ext-install mysqli
