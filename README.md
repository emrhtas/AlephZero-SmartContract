# AlephZero-SmartContract
## 1) Gerekli Kurulumları Yapıyoruz.
### Rust yüklüyoruz
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh    (fotoekle 1 yazılması lazım)
source ~/.cargo/env
```
### Sürümü değiştiriyoruz.
```
rustup toolchain install nightly
rustup component add rust-src --toolchain nightly
rustup target add wasm32-unknown-unknown --toolchain nightly
```
### Kontrol ediyoruz.-----------------
```
cargo --help
```
###
```
sudo apt install binaryen
```
###
```
cargo install --git https://github.com/paritytech/cargo-contract.git --rev 4f831bc2e4b8f3fa5a6a4d1b3fa673e99807af8f
```
### ilerleyen zamanlarda
```
cargo install cargo-contract
```
## 2) Kontrat Oluşturuyoruz
```
cargo contract new TOKENADI
cd TOKENADI
```



