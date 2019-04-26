FROM php:7.3

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN pecl install xdebug-beta rdkafka \
  && docker-php-ext-enable xdebug rdkafka \
  && docker-php-ext-install bcmath
