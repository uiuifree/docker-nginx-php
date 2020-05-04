FROM php:7.4.5-fpm-alpine3.11

# install pdo
RUN docker-php-ext-install pdo_mysql

# install composer
RUN curl -sS https://getcomposer.org/installer | php
RUN mv composer.phar /usr/local/bin/composer

