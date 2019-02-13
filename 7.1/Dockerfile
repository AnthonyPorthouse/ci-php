FROM php:7.1

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN pecl install xdebug \
  && docker-php-ext-enable xdebug \
  && docker-php-ext-install bcmath
