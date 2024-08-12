# Pengecekan  Manual Slot Gacor pada Server

Script ini untuk membaca daftar string untuk melakukan pencarian dari suatu berkas, pencarian string ini dalam direktori tertentu dan subdirektorinya.

## Cara Penggunaan

Untuk menggunakan script ini, silahkan download terlebih dahulu dengan cara git clone
```bash
git clone https://github.com/chikmonk/slotgacor.git
```
To use this script, you need to call it with the path to the directory you want to search as an argument. For example:

```bash
bash scan.sh /var/www/html
```

In this example, the script will search for the strings in the `/var/www/html` directory and its subdirectories.

## Example Output
```
The file /var/www/backdoor.php is a backdoor.
The file /var/www/new_backdoor.php is not a backdoor, please inform this script author for the next investigation.
```

## Input File

The script reads the search strings from a file named `list.txt`. Each search string should be on its own line in this file.

---
