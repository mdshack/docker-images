FROM php:8.3-fpm-alpine

RUN apk update
RUN apk add --update caddy

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT [ "/entrypoint.sh" ]