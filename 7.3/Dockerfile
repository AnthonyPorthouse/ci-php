FROM php:7.3

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN pecl install xdebug-beta \
  && docker-php-ext-enable xdebug \
  && docker-php-ext-install bcmath
