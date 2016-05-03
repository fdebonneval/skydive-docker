FROM golang:latest

RUN apt-get update && \
    apt-get install -y libpcap-dev

RUN mkdir -p /go/src/github.com/redhat-cip && \
    cd /go/src/github.com/redhat-cip && \
    git clone https://github.com/redhat-cip/skydive && \
    cd /go/src/github.com/redhat-cip/skydive && \
    make install

#ENTRYPOINT ["/go/bin/skydive_agent"]
