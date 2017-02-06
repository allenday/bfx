FROM ubuntu:12.04

MAINTAINER Allen Day "allenday@allenday.com"

ENV BUILD_PACKAGES="bwa"

RUN apt-get -y update
RUN apt-get -y install $BUILD_PACKAGES
RUN apt-get -y remove --purge -y $(apt-mark showauto)
RUN rm -rf /var/lib/apt/lists/*
