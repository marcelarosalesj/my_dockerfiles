#
# Dockerfile for fm-common
#

FROM ubuntu:16.04

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
    unzip

# For compilation
RUN apt-get install -y \
    uuid-dev \
    libpq-dev \
    python-dev

RUN pip install \
    pyyaml \
    SQLAlchemy
