## GO gRPC - Example
- For study purposes only.
#### Dependencies

```shell
go mod tidy
```

#### Server Start

```shell
  go run cmd/grpcServer/main.go 
```

#### For create new services/responses

```shell
  rotoc --go_out=. --go-grpc_out=. proto/course_category.proto 
```