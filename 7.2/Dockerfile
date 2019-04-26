FROM php:7.2

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN pecl install xdebug rdkafka \
  && docker-php-ext-enable xdebug rdkafka \
  && docker-php-ext-install bcmath
