# gRPC learning

Using protoc version: libprotoc [3.13.0](https://github.com/protocolbuffers/protobuf/releases/tag/v3.13.0)

**NOTE** Make sure that your $GOPATH/bin is in $PATH, else the protoc generator won't work.

## Generate go code

Assuming that you have stored the proto files under third_party

```protoc --proto_path=proto --proto_path=third_party --go_out=plugins=grpc:proto service.proto```

## Test the app

go in to the server folder and start main.go

Open another terminal, go in to the client folder and start main.go

```bash
curl http://localhost:8080/add/10/1

curl http://localhost:8080/mult/10/2
```
