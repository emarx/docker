FROM ubuntu:latest
MAINTAINER Elliot Marx "elliot.marx@affirm.com"

RUN apt-get update
RUN apt-get install -y python python-pip wget

ADD hello.py /home/hello.py

RUN mkdir /platform
WORKDIR /platform
VOLUME /platform
