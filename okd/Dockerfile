FROM ubuntu:18.04

ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update \
&& apt-get install -y rsync vagrant virtualbox

COPY Vagrantfile /var/tmp
