FROM ubuntu:18.04

RUN apt-get update && apt-get upgrade --yes && apt-get --yes install \
    apt-utils \
    curl \
    gnupg \
    wget

RUN ["wget", "https://dl.influxdata.com/influxdb/releases/influxdb-1.7.9_linux_armhf.tar.gz"]
RUN ["tar", "xvfz", "influxdb-1.7.9_linux_armhf.tar.gz"]
