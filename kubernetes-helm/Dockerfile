FROM ubuntu:16.04
MAINTAINER Mosaicwang <mosaicwang@gmail.com>
RUN apt-get update 
RUN apt-get install -y wget 
RUN wget https://storage.googleapis.com/kubernetes-helm/helm-v2.10.0-linux-amd64.tar.gz
RUN tar -zxvf helm-v2.10.0-linux-amd64.tgz & cp linux-amd64/helm /usr/local/bin/helm
RUN helm init

