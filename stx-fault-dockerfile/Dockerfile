#
# Dockerfile for stx-fault
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
    python-pip \
    gdb \
    unzip \
    netcat \
    debmake \
    sudo

# For building
RUN apt-get install -y \
    uuid-dev \
    libpq-dev \
    python-dev \
    libsnmp-dev

# For building fm-mgr
RUN apt-get install -y \
    debhelper

RUN pip install \
    pyyaml \
    SQLAlchemy

ENV DEBEMAIL "marce@mail.com"
ENV DEBFULLNAME "Marcela"
