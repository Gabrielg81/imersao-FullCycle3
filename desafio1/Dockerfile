FROM golang:1.16-alpine

RUN mkdir /app
ADD . /app
WORKDIR /app
EXPOSE 8000
RUN go build main.go
COPY . .
CMD ["/app/main"]