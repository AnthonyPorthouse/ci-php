FROM php:7.3-rc-alpine

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN apk add --no-cache $PHPIZE_DEPS --virtual .deps \
  && pecl install xdebug-beta \
  && apk del .deps \
  && docker-php-ext-enable xdebug
