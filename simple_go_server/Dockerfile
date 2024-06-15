FROM golang:1.22.4-alpine3.20
COPY . .
RUN go build -o server .
CMD ["./server"]