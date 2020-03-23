FROM golang:1.13.3

ADD . /app
WORKDIR /app
RUN go build
ENTRYPOINT ["/app/greeter_client"]
