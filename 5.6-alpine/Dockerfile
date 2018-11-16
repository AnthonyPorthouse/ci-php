FROM php:5.6-alpine

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN apk add --no-cache $PHPIZE_DEPS --virtual .deps \
  && pecl install xdebug \
  && apk del .deps \
  && docker-php-ext-enable xdebug
