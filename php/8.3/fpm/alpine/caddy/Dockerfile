FROM php:8.3-fpm-alpine

RUN apk update
RUN apk add --update caddy

COPY ./bin/* /usr/local/bin/

# Run scripts in this directory on initialization
RUN mkdir /docker-init

# PHP related configuration
RUN mkdir /etc/php.d/