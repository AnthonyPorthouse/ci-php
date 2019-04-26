FROM php:5.6

LABEL maintainer="Anthony Porthouse<anthony@porthou.se>"

RUN pecl install xdebug-2.5.5 rdkafka \
  && docker-php-ext-enable xdebug rdkafka \
  && docker-php-ext-install bcmath
