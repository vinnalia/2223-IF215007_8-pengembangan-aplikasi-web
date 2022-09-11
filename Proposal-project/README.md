# PROPOSAL

## Aplikasi FINCORDS
* Aplikasi pencatat keuangan atau _financial records_ untuk mahasiswa

## Permasalahan
* Mahasiswa yang ngekost dan merantau mengalami kesulitan dalam mencatat keuangannya untuk berhemat sampai akhir bulan

## Rancangan Solusi
* Aplikasi pencatat keuangan yang terdapat income, expenses, dan history pembelian di setiap aktivitas

## Use Case
* User bisa melakukan registrasi mandiri dan login
* User bisa menambah nama aktivitas
* User bisa menginput income yang akan digunakan
* User bisa melihat jumlah expenses yang dikeluarkan
* User bisa melihat history pembelian per aktivitas

## Struktur Data

### User

| Atribut  | Tipe Data | Contoh  |
| -------- | --------- | --------|
| id       | varchar   | A1      |
| username | string    | Vinnalia|
| password | varchar   | vi123   |

### Income

| Atribut  | Tipe Data | Contoh |
| -------- | --------- | ------ |
| id       | varchar   | B1     |
| nominal  | integer   | 300000 |

### Aktivitas

| Atribut  | Tipe Data | Contoh |
| -------- | --------- | ------ |
| id       | varchar   | C1     |
| nama     | varchar   | Ngekos |

### Expenses

| Atribut     | Tipe Data | Contoh      |
| ----------- | --------- | ----------  |
| id          | varchar   | D1          |
| id_aktivitas| varchar   | C1          |
| tanggal     | date      | 2022-09-04  |
| nominal     | integer   | 43000       |

## UX Wireframe
![3](https://user-images.githubusercontent.com/112877296/189534920-704cbaa9-b017-4a09-981c-74ba77c09496.png)
