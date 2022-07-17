# grpcBasic

## 環境構築
### Protocol Buffersのコンパイラをインストール
`brew install protobuf`  
#### インストール確認
`protoc --version`
### Go pluginをインストール
`go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.28`  
`go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.2`    

##### 参考URL
- gRPC Quick Start  
https://www.udemy.com/course/go-grpc-x/learn/lecture/30988814#overview

## 参考URL
- Udemy Go言語で学ぶ実践gRPC入門  
https://www.udemy.com/course/go-grpc-x/
