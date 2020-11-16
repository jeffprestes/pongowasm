# Pongo - Golang & Wasm

## Copy wasm_exec

```bash
cp $(go env GOROOT)/misc/wasm/wasm_exec.js ./site/wasm_exec.js
```

## Compilar wasm

```bash
GOOS=js GOARCH=wasm go build -o ./html/main.wasm ./wasm/.
```

## To run Go web server

```bash
go run main.go
```
