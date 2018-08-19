FROM registry.cn-hangzhou.aliyuncs.com/bostenai/downloader:base
MAINTAINER Mosaicwang <mosaicwang@gmail.com>
RUN wget https://storage.googleapis.com/kubernetes-helm/helm-v2.10.0-linux-amd64.tar.gz
RUN tar -zxvf helm-v2.10.0-linux-amd64.tar.gz
RUN cp linux-amd64/helm /usr/local/bin/helm
RUN helm init

