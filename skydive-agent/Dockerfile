FROM golang:latest

RUN go get github.com/tools/godep
RUN go get github.com/redhat-cip/skydive/cmd/skydive_agent

ENTRYPOINT ["/go/bin/skydive_agent"]
CMD ["--conf","/skydive/skydive.ini"]
