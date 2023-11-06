Generate protoc files running:
```bash
protoc --go_out=. --go-grpc_out=. proto/course_category.proto
```

Run the application with:
```bash
go run cmd/grpcServer/main.go
```

Use evans to call the service:
```bash
evans -r repl
```