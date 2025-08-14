FROM golang:1.21-alpine AS builder
WORKDIR /app
COPY . /app
RUN go mod download && go mod verify
RUN cd /app && go build -o frontend
EXPOSE 8080
ENV BACKEND_DNS=backend
ENV BACKEND_PORT=9000
ENTRYPOINT ["./frontend"]
