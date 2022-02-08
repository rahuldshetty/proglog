How to compile Protobuf structs?
Install protobuf:  https://github.com/protocolbuffers/protobuf/releases

Install Protobuf package for GO: go install google.golang.org/protobuf/cmd/protoc-gen-go

Compile:
protoc api/v1/*.proto --go_out=. --go_opt=paths=source_relative --proto_path=.

