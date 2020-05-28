FROM golang:1.14.2

ADD . /app
WORKDIR /app
RUN go build
ENTRYPOINT ["/app/greeter_client"]
