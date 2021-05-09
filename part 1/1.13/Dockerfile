FROM golang:1.16

WORKDIR /go/src/app

COPY . .

RUN go build

RUN go test

CMD ./server

EXPOSE 8080
