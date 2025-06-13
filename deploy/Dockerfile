FROM php:8.2-apache

RUN docker-php-ext-install pdo_mysql

RUN a2enmod rewrite

COPY ./html /var/www/html
COPY ./php/000-default.conf /etc/apache2/sites-enabled/000-default.conf
