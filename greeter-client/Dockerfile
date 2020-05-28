FROM golang:1.14.2

ADD ./greeter-client /app
WORKDIR /app
RUN go build
ENTRYPOINT ["./greeter-client"]
