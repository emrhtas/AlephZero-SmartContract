# AlephZero-SmartContract

## Rust yüklüyoruz
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source ~/.cargo/env
```
## Sürümü değiştiriyoruz.
```
rustup toolchain install nightly
rustup component add rust-src --toolchain nightly
rustup target add wasm32-unknown-unknown --toolchain nightly
```
## Kontrol ediyoruz.
```
nano docker-compose.yaml
```




