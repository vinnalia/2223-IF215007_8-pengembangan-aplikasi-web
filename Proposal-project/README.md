# PROPOSAL

## Aplikasi FINCORDS
* Aplikasi pencatat keuangan atau _financial records_ untuk mahasiswa

## Permasalahan
* Mahasiswa yang ngekost dan merantau mengalami kesulitan dalam mencatat keuangannya untuk berhemat sampai akhir bulan

## Rancangan Solusi
* Aplikasi pencatat keuangan yang terdapat income, expenses, dan history pembelian di setiap aktivitas

## Use Case
* User bisa melakukan registrasi mandiri dan login
* User bisa menambah nama aktivitas yang dilakukan per harinya
* User bisa menginput income yang akan digunakan
* User bisa melihat jumlah expenses yang dikeluarkan
* User bisa melihat history pembelian per aktivitas

## Struktur Data

### User

| Atribut  | Tipe Data | Contoh |
| -------- | --------- | ------ |
| id       | varchar   | A1     |
| username | string    | vinna  |
| password | varchar   | vi123  |

### Income

| Atribut  | Tipe Data | Contoh |
| -------- | --------- | ------ |
| id       | varchar   | B1     |
| nominal  | integer   | 300000 |

### Aktivitas

| Atribut  | Tipe Data | Contoh |
| -------- | --------- | ------ |
| id       | varchar   | C1     |
| nama     | varchar   | Makan  |

### Expenses

| Atribut     | Tipe Data | Contoh |
| ----------- | --------- | ------ |
| id          | varchar   | D1     |
| id_aktivitas| varchar   | C1     |
| nominal     | integer   | 150000 |

## UX Wireframe
