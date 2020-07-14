# WASI で Then Then Then 世

## Requirements

- [wabt](https://github.com/WebAssembly/wabt)
- [wasmtime](https://github.com/bytecodealliance/wasmtime)

## Build & Run

```bash
wat2wasm RADWIMPS.wat
wasmtime run RADWIMPS.wasm # => 前前前世
```
