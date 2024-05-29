# PSMF

## Install Dependencies

```bash
rustup target add aarch64-apple-ios x86_64-apple-ios aarch64-apple-ios-sim
cargo install tauri-cli
cargo install tauri-cli --version "^2.0.0-alpha"

```


## Starting the development server

```bash
cargo tauri dev
```
or the iOS version on macOS:

```bash
cargo tauri ios dev
```

## Build

```bash 
cargo tauri build???
```