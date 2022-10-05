#build stage
FROM golang:alpine
LABEL maintainer="Hossam Mostafa"

WORKDIR /go/src/app
ADD . .

RUN  go mod init && go build -o helloworld
CMD ["./helloworld"]
