[![.github/workflows/deploy-to-pages.yml](https://github.com/Diamondlord/roguelike/workflows/.github/workflows/deploy-to-pages.yml/badge.svg)](https://github.com/Diamondlord/roguelike/actions?query=workflow%3A%22Build+and+Deploy+to+GitHub+Pages%22)

# Roguelike

- ```cargo build --release --target wasm32-unknown-unknown```
- ```wasm-bindgen target/wasm32-unknown-unknown/release/roguelike.wasm --out-dir wasm --no-modules --no-typescript```
