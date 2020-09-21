FROM golang:1.15-alpine
ADD main.go main.go
RUN apk add git
RUN go get -u github.com/gin-gonic/gin
CMD ["go", "run", "main.go"]