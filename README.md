
Build protobuf
https://jbrandhorst.com/post/go-protobuf-tips/
```bash
protoc -I proto/ proto/epl/protobuf/geometry.proto --go_out=$GOPATH/src
protoc -I proto/ proto/epl/grpc/geometry_operators.proto --go_out=plugins=grpc:$GOPATH/src
```



