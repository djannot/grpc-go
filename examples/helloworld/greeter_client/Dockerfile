FROM golang
WORKDIR /go/src
RUN git clone https://github.com/djannot/grpc-go
WORKDIR /go/src/grpc-go/examples/helloworld/greeter_client
RUN go build .
ENTRYPOINT ["./greeter_client"]
