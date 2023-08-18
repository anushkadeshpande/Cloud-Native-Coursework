FROM golang:alpine
WORKDIR /go/src/app
COPY . /go/src/app
RUN go mod init && go build -o main
EXPOSE 6111
CMD ["./main"]