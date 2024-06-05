# Using Golang as Base Image
FROM golang:1.16-alpine

# Expose Port
EXPOSE 8080

# Working Directory
WORKDIR /usr/src/app

# Copying Source
COPY . .

# Building Binary
RUN go build

# Run Server
CMD ["./server"]

