FROM golang:alpine

WORKDIR /app

COPY . .

RUN go build -o main .

EXPOSE 8001

CMD ["./main"]