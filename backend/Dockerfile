FROM golang:1.21-alpine AS builder
WORKDIR /app
COPY go.mod go.sum ./
RUN go mod download
RUN go mod verify

COPY . .

FROM alpine:latest
RUN apk --no-cache add ca-certificates
WORKDIR /root/
CMD ["go", "run", "main.go"]