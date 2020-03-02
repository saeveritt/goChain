# goChain
Simple Blockchain in golang
```
go get golang.org/x/net/context
go get google.golang.org/grpc
go get github.com/golang/protobuf/proto
```


First,
`go run main.go`

`go run client/main.go --list`
When running --list for the first time the genesis block will be created.
![](https://i.imgur.com/JkjgRq9.png)

`go run client/main.go --add`
Running --add will create a new block
![](https://i.imgur.com/WJycswi.png)

`go run client/main.go --list`
Will return all blocks
![](https://i.imgur.com/fDMJwph.png)
