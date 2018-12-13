FROM hub.c.163.com/library/golang:latest

MAINTAINER longfei "test@163.com"

RUN echo "Asia/Shanghai" > /etc/timezone
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN dpkg-reconfigure -f noninteractive tzdata



WORKDIR $GOPATH/src/trade




