#
# Dockerfile to build deb pkgs
#

FROM ubuntu:16.04

RUN useradd -ms /bin/bash marce

WORKDIR /localdisk

RUN apt-get update -y

# For development
RUN apt-get install -y \
    build-essential \
    git \
    make \
    vim \
    unzip \
    sudo \
    debmake \
    dh-make \
    devscripts


ENV DEBEMAIL "marcelarosalesj@gmail.com"
ENV DEBFULLNAME "Marcela Rosales"
