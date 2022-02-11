# Tauri + Yew Desktop app

A boiling plate with Tauri + Yew to build a Desktop app.

## Installation

```
rustup target add wasm32-unknown-unknown
cargo install trunk
cargo install wasm-bindgen-cli
cargo install tauri-cli --version ^1.0.0-beta
```

## Dev Server

After installing the above, you should be able to run it with

```
 cargo tauri dev
```

## Building the app

You can do a release build with

```
cargo tauri build
```

This should create an installer in src-tauri/target/release/bundle/

## Further reading

<img src="src-tauri/icons/32x32.png" width="20"/>Tauri: https://tauri.studio/en/docs/get-started/intro

<img src="https://yew.rs/img/logo.png" width="15" />Yew: https://yew.rs/docs/getting-started/introduction

## Acknowledgement:

Steve Pryde
