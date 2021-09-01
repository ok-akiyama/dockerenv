FROM php:7.4-apache

RUN apt-get update && apt-get install -y \
    tzdata \
    libpq-dev \
&& rm -rf /var/lib/apt/lists/* \
&& docker-php-ext-install pdo_pgsql

ENV TZ=Asia/Tokyo