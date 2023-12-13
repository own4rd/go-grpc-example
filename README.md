## GO gRPC - Example
- For study purposes only.
- To test the gRPC API, it is recommended to use [Evans](https://github.com/ktr0731/evans), a gRPC command-line REPL.

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
  protoc --go_out=. --go-grpc_out=. proto/course_category.proto 
```