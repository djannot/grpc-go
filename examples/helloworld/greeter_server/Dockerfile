FROM golang
WORKDIR /go/src
RUN git clone https://github.com/djannot/grpc-go
WORKDIR /go/src/grpc-go/examples/helloworld/greeter_server
RUN go build .
ENTRYPOINT ["./greeter_server"]
