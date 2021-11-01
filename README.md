# go-wasmer-example

## Create Rust pure wasm lib

```Rust
cargo new simple --lib
cd simple
rustup target add wasm32-unknown-unknown
cargo check --target wasm32-unknown-unknown
cargo build --target wasm32-unknown-unknown
```