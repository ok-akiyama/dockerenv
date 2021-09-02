FROM php:7.4-apache

RUN apt-get update && apt-get install -y \
    tzdata\
  && pecl install xdebug \
  && rm -rf /var/lib/apt/lists/*

ENV TZ=Asia/Tokyo