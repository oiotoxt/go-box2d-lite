go-box2d-lite
=============

Golang port of [Box2d Lite](http://code.google.com/p/box2d/downloads/detail?name=Box2D_Lite.zip), originally written in C++.


## Install

```bash
# Ubuntu
sudo apt install libsdl2-dev

go get github.com/neguse/go-box2d-lite/box2dlite
go get github.com/veandco/go-sdl2/sdl

cd examples
go run main.go
```

## Usage

`
import "github.com/neguse/go-box2d-lite/box2dlite"
`

also see [Examples](examples/main.go)

## License

see [LICENSE](LICENSE)

## Notice

If you want 2D physics library for golang, Check https://github.com/ByteArena/box2d and https://github.com/vova616/chipmunk.
