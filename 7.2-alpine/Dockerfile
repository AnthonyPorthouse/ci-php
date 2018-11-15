FROM php:7.2-alpine

RUN apk add --no-cache $PHPIZE_DEPS --virtual .deps \
  && pecl install xdebug \
  && apk del .deps
