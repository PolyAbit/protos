# protos

Just use command: `task gen`

Before use, install the necessary deps:

1) `go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.28`

2) `go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.2`

3) `export PATH="$PATH:$(go env GOPATH)/bin"`