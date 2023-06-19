FROM php:8-apache

RUN a2enmod rewrite
RUN docker-php-ext-install mysqli pdo pdo_mysql
#RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

#COPY --from=composer:latest /usr/bin/composer /usr/bin/composer
#
#RUN pecl install xdebug \
#    && docker-php-ext-enable xdebug
#
#COPY conf.d/* "${PHP_INI_DIR}/conf.d"
