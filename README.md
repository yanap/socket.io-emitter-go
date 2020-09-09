# socket.io-emitter-go
Go implementation of socket.io-emitter

## Install

```sh
$ go get github.com/yanap/socket.io-emitter-go
```

## Example

```go
opts := &emitter.Options{}
socket := emitter.NewEmitter(opts)
defer socket.Close()
socket.Broadcast().Emit("message", "Hello World")
```
## License

MIT
