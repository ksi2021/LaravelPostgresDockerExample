FROM php:7.4-fpm

RUN apt-get update

RUN apt-get install -y libpq-dev \
  && docker-php-ext-install pdo pdo_pgsql pgsql

# RUN a2enmod rewrite