# Pengecekan  Manual Slot Gacor pada Server

Script ini untuk membaca daftar string untuk melakukan pencarian dari suatu berkas, pencarian string ini dalam direktori tertentu dan subdirektorinya.

## Cara Penggunaan

Untuk menggunakan script ini, silahkan lalukan perintah ini
```bash
git clone https://github.com/chikmonk/slotgacor.git
cd slotgacor
chmod +x scan.sh
bash scan.sh /var/www/html
```
Dalam contoh perintah diatas, script akan mencari string dalam /var/www/html direktori dan subdirektorinya. silahkan ubah perintah /var/www/html sesuai letak direktori yang akan dilakukan pencarian string.

## Contoh Hasil
```
The file /var/www/backdoor.php is a backdoor.
The file /var/www/new_backdoor.php is not a backdoor, please inform this script author for the next investigation.
```

## Kompilasi String

Script membaca string pencarian dari sebuah berkas bernama listgacor.txt. Setiap string pencarian harus berada pada barisnya sendiri dalam berkas ini. Silahkan gunakan atau update string pada listgacor.txt sesuai kebutuhan.

---

## Referensi
https://github.com/luridarmawan/scan-slot-backdoor
