FROM randomdude/gcc-cross-x86_64-elf
FROM ubuntu:focal-20211006

RUN apt-get -y update
RUN apt-get upgrade -y
RUN apt-get install -y build-essential
RUN apt-get install -y nasm
RUN apt-get install -y xorriso
RUN apt-get install -y grub-pc-bin
RUN apt-get install -y grub-common

VOLUME /root/env
WORKDIR /root/env