FROM ubuntu:16.04

MAINTAINER Ghifari160 <ghifari160@ghifari160.com>

# disable interactive functions
ENV DEBIAN_FRONTEND noninteractive

# install some utilities
RUN apt update && apt install -y software-properties-common \
language-pack-en-base nano

# cleanup after apt
RUN rm -rf /var/lib/apt/lists/*
