
FROM golang:1
ADD main.go /
WORKDIR /
RUN go build -o main .
EXPOSE 3011
ENTRYPOINT ["/main"]
