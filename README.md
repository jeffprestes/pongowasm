# Pongo - Golang & Wasm

Example of Go & Wasm. Based on https://github.com/dstoiko/go-pong-wasm but with improved JS and Web server initialization.

## Copy wasm_exec

```bash
cp $(go env GOROOT)/misc/wasm/wasm_exec.js ./site/wasm_exec.js
```

## Compile wasm

```bash
GOOS=js GOARCH=wasm go build -o ./html/main.wasm ./wasm/.
```

## To run local Go web server

```bash
go run main.go
```
