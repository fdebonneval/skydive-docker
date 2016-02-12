FROM golang:latest

RUN go get github.com/tools/godep
RUN go get github.com/redhat-cip/skydive/cmd/skydive_analyzer

ENTRYPOINT ["/go/bin/skydive_analyzer"]
