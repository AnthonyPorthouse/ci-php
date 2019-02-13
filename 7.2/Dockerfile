FROM php:7.2

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN pecl install xdebug \
  && docker-php-ext-enable xdebug \
  && docker-php-ext-install bcmath
