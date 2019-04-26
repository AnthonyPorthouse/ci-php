FROM php:7.1

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN pecl install xdebug rdkafka \
  && docker-php-ext-enable xdebug rdkafka \
  && docker-php-ext-install bcmath
