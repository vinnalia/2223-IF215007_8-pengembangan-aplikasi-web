# PROPOSAL

## Aplikasi Vika
* Aplikasi untuk mahasiswa menyusun proses tugas yang akan dikerjakan

## Permasalahan
* Mahasiswa yang banyak tugas, kadang bingung mulai mengerjakan tugasnya darimana dulu

## Rancangan Solusi
* Aplikasi penyusun proses pengerjaan tugas yang akan dilakukan agar lebih terstruktur

## Use Case
* User bisa sign up dan login menggunakan username dan password
* User bisa membuat board berjudul nama kegiatan
* User bisa menambah section di dalam board kegiatan nya
* User bisa menambah detail proses di dalam tiap section
* User bisa menjadikan board kegiatannya menjadi favorite
* User bisa menghapus board kegiatan dan section

## Struktur Data

### boards

| Atribut    | Tipe Data  |
| --------   | ---------  |
| _id        | ObjectId   |
| User       | ObjectId   | 
| icon       | string     |
| title      | string     |
| description| string     |

### sections

| Atribut    | Tipe Data  |
| --------   | ---------  |
| _id        | ObjectId   |
| board      | ObjectId   | 
| title      | string     |

### tasks

| Atribut    | Tipe Data  |
| --------   | ---------  |
| _id        | ObjectId   |
| section    | ObjectId   | 
| title      | string     |
| content    | string     |

## users

| Atribut    | Tipe Data  |
| --------   | ---------  |
| _id        | ObjectId   |
| username   | string     | 
| password   | string     |

## UX Wireframe
## Link YT Video Promosi Aplikasi
* https://youtu.be/5cymWvo9lPI

