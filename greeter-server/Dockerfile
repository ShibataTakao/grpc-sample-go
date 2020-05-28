FROM golang:1.14.2

ADD ./greeter-server /app
WORKDIR /app
RUN go build
ENTRYPOINT ["./greeter-server"]
