
# Tutorial Testnet ALEO Pools HAMP 

- [Website](https://hamp.app/)
- [Discord](https://discord.com/channels/700454073459015690/1050128925164064878)
- [Doc offcial](https://hamp.app/getting_started)
- [Github](https://github.com/harukama/aleo-prover)
- [Dashbord Node](https://hamp.app/) 

### WARNING
- Balance di Dashbord tidak bisa di tranfer saat ini
- Jika bergabung denga pool address tidak bisa di scan di [Explorer](https://explorer.hamp.app/)
- Pool HAMP menggunakan skema PPLNS Semua jumlah yang ditampilkan di Dashbord adalah Reward testnet
- Sebelum menjalankan Testnet perlu di ketahui provers saat ini sangat sulit untuk mendapatkan reward
- Untuk melihat Status Node anda silahkan check  [Dashbord Node](https://hamp.app/)
- Untuk kalkulator rata-rata reward check [HAMPapp](https://explorer.hamp.app/calc)

### Instal Rust

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
run
```
source "$HOME/.cargo/env"
```

### Install dependencies 

```
sudo apt update
sudo apt install git clang libssl-dev pkg-config --no-install-recommends
```
```
git clone https://github.com/HarukaMa/aleo-prover -b testnet3-new
```
masuk folder
```
cd aleo-prover
```
Membuat wallet (skip jika sudah punya wallet ALEO)
```
target/release/aleo-prover --new-address
```
### install screen & Screen 
```
apt install screen
```
```
screen -R prover
```
### Build cargo 
```
cargo build --release
```
### RUN Node
```
cargo run --release -- -a ALEO-Address -p pool.hamp.app:4444
```
- di bagian `ALEO-Address ` ganti address ALEO  
- `ctrl A D` untuk Menyimpan Screen
- untuk membuka Screen Yang Sedang Jalan, Gunakan Perintah `screen -Rd prover`
- Untuk menajalakan Screen `screen -R prover`

 ### -[Tutorial ALEO SOLO MINE](https://github.com/Art-Sy5team/Aleo/blob/main/README.md)-
 
## INFO
Anda dapat menjalankan banyak **Miner** dengan Address Aleo yang sama | Anda tidak bisa check **saldo atau address** explorer official (soon) | rewards **Incentivized Testnet** te;ah dimuali 2 Desember 2022 hingga 26 Januari 2023 ! 


### Art-Team INFO
noted: **art team** here does not have any specific goals or intentions, they only collect data and share it with everyone.

untuk INFO Testnet lainya Silahkan join Discord 👇

[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ArtSy5team)
[![Discord](https://img.shields.io/badge/discord-7289d9?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/EAKEdZU6c8)
[![Github](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/Art-Sy5team)
[![trakteer](https://img.shields.io/badge/trakteer.id-e31e1e?style=for-the-badge&logo=ko-fi&logoColor=white)](https://trakteer.id/Art-Sy5team/tip)
