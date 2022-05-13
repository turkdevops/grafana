
FROM golang:1.18-bullseye 
ADD main.go /
WORKDIR /
RUN go build -o main . 
EXPOSE 3010
ENTRYPOINT ["/main"]
