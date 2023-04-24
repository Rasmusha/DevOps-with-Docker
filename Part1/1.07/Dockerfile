FROM ubuntu:20.04

WORKDIR /usr/src/app

COPY scripti.sh .

RUN apt update; apt install -y curl

CMD ./scripti.sh