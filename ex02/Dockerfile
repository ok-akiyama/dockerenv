FROM php:7.4-apache

RUN apt-get update && apt-get install -y \
    tzdata \

ENV TZ=Asia/Tokyo

WORKDIR /usr/local/etc/php

COPY php.ini ${PWD}

ARG WORKDIR

WORKDIR $wdir