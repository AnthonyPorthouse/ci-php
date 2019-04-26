FROM php:7.3-alpine

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN apk add --no-cache $PHPIZE_DEPS --virtual .deps \
  && pecl install xdebug-beta rdkafka \
  && apk del .deps \
  && docker-php-ext-enable xdebug rdkafka \
  && docker-php-ext-install bcmath
