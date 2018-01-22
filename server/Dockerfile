FROM golang:1.8

WORKDIR /go/src/go-udp
COPY . .

RUN go install

ENTRYPOINT /go/bin/go-udp

EXPOSE 10001