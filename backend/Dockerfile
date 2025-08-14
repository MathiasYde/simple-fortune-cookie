FROM golang:1.21-alpine
WORKDIR /app
COPY go.mod /app
RUN go mod download \ \
    && go mod verify \
    && go mod tidy \
