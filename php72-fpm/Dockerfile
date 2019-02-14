FROM php:7.2-fpm
RUN apt-get update && apt-get upgrade -y
RUN docker-php-ext-install mysqli pdo pdo_mysql mbstring
RUN mkdir -p /var/run/php-fpm
# && \useradd -s /usr/sbin/nologin nginx && \
#chown -R nginx:nginx /var/run/php-fpm
#COPY ./config/php.ini /usr/local/etc/php/php.ini
#COPY ./config/www.conf /usr/local/etc/php-fpm.d/www.conf
#COPY ./config/zz-docker.conf /usr/local/etc/php-fpm.d/zz-docker.conf