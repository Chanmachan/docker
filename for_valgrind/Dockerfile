FROM ubuntu:14.04

RUN apt-get -y update && apt-get -y install valgrind build-essential emacs

# create volume
RUN mkdir -p /root/build
VOLUME /root/build
