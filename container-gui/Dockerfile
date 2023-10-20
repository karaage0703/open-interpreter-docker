# FROM ubuntu:22.04
FROM fredblgr/ubuntu-novnc:22.04

RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y git python3 python3-pip

# Japanese Environment
RUN apt-get install -y language-pack-ja-base language-pack-ja locales ibus-mozc
RUN locale-gen ja_JP.UTF-8
ENV LANG ja_JP.UTF-8

RUN pip install open-interpreter==0.1.10
RUN pip install numpy matplotlib pandas

WORKDIR /root
