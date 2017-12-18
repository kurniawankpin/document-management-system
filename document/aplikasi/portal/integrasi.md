---
layout: document
title:  Integrasi dan Pengujian Portal
description: Portal adalah aplikasi  e-goverment dengan sasaran agar maysarakat dapat dengan mudah memperoleh akses informasi 
group: aplikasi
cat: portal
toc: true
---

## Daftar Isi

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

### Integrasi dan Pengujian Portal
Pada laporan ini akan membahas tentang Pengujian dan Integrasi Portal Banten, untuk pengujiannya menggunakan *User Acceptance Test*.

#### Integrasi
Portal adalah aplikasi  e-goverment dengan sasaran agar maysarakat dapat dengan mudah memperoleh akses informasi. Untuk mencapai sasaran tersebut maka semua informasi perlu dikumpulkan dalam satu wadah portal web yang dapat dengan mudah diakses oleh masyarakat. dengan adanya web portal pemerintah ini dapat memudahkan masyarakat dalam mencari informasi tentang kegiatan dan info yang terdapat dipemerintah.

Untuk memulai akses User terhadap aplikasi Portal Banten. Buka web browser (IE, Mozila Firefox atau yang lainnya) dengan menulis alamat url : http://portal-01.dev.bantenprov.go.id kemudian tekan Enter pada tombol keyboard atau klik tombol Go pada browser.

##### Tampilan pelayanan
[![Tampilan pelayanan portal](../images/integrasi/pelayanan-portal.jpeg)](../images/integrasi/pelayanan-portal.jpeg)

Pada page ini terdapat method yang berupa tombol **GET** dan link url untuk konten pelayanan get all data, method ini digunakan untuk menambahkan data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi field, type dan description. Terdapat 2 response didalam page ini yaitu:
1. Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

##### Tampilan perijinan
[![Tampilan perijinan portal](../images/integrasi/perijinan-portal.jpeg)](../images/integrasi/perijinan-portal.jpeg)

Pada page ini terdapat method yang berupa tombol **GET** dan link url untuk konten pelayanan get all data perijinan, method ini digunakan untuk menambahkan data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi field, type dan description. Terdapat 2 response didalam page ini yaitu:
1. Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

##### Tampilan produk hukum
[![Tampilan perijinan portal](../images/integrasi/produk-hukum.jpeg)](../images/integrasi/produk-hukum.jpeg)

Pada page ini terdapat method yang berupa tombol **GET** dan link url untuk konten produk hukum get all data, method ini digunakan untuk menambahkan data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi field, type dan description. Terdapat 2 response didalam page ini yaitu:
1. Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

#### pengujian

Sistem informasi saat ini semakin berkembang pesat membuat semua pekerjaan dikehidupan ini banyak yang sudah beralih dibantu oleh teknologi informasi. Teknologi yang dapat membantu lebih mudah, cepat, aman dan efektif jelas sangatlah membantu siapa saja yang memanfaatkannya, document dibuat untuk memberikan panduan penggunaan aplikasi Portal, Portal adalah aplikasi  e-goverment dengan sasaran agar maysarakat dapat dengan mudah memperoleh akses informasi. Untuk mencapai sasaran tersebut maka semua informasi perlu dikumpulkan dalam satu wadah portal web yang dapat dengan mudah diakses oleh masyarakat. dengan adanya web portal pemerintah ini dapat memudahkan masyarakat dalam mencari informasi tentang kegiatan dan info yang terdapat dipemerintah.

Untuk memulai akses User terhadap aplikasi Portal Banten. Buka web browser (IE, Mozila Firefox atau yang lainnya) dengan menulis alamat url : http://portal-01.dev.bantenprov.go.id kemudian tekan Enter pada tombol keyboard atau klik tombol Go pada browser.

##### Tampilan awal portal
| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Awal     | [![Tampilan utama portal](../images/integrasi/01-tampilan-utama.png)](../images/integrasi/01-tampilan-utama.png) |      |       |

tampilan ini menampilkan konten home, layanan, produk hukum, perijinan, contact us

##### Tampilan anggaran penyerapan
| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Awal     | [![Tampilan utama portal](../images/integrasi/02-anggaran-penyerapan.png)](../images/integrasi/02-anggaran-penyerapan.png) |      |       |

tampilan ini menampilkan konten 4 jalur yang terdiri dari : 
1.G2E goverment to enironent
2.G2G goverment to goverment
3.G2C costumer
4.G2B bussines
dan anggaran penyerapan.

##### Tampilan 10 sektor
| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Awal     | [![Tampilan utama portal](../images/integrasi/tampilan-10-sektor.png)](../images/integrasi/tampilan-10-sektor.png) |      |       |

tampialn ini menampilkan konten 10 yang terdiri dari :
1. Sektor sarana dan perasaan
2. Sektor pemerintahan
3. Sektor pembangunan
4. Sektor pelayanan
5. Sektor legislasi
6. Sektor kewilayahan
7. Sektor keuangan
8. Sektor kepegawaian
9. Sektor kemasyarakatan
10. Sektor administrasi dan manajemen

##### Tampilan 9 layanan
| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Awal     | [![Tampilan 9 layanan portal](../images/integrasi/tampilan-layanan.png)](../images/integrasi/tampialn-layanan.png) |      |       |

tampilan ini menampilkan konten 9 layanan terdiri dari :
1. Layanan umum ketiga
2. Layanan tambahan G2B
3. Layanan umum keenam
4. Layanan umum kedua
5. Layanan umum pertama
6. Layanan umum kelima
7. Layanan umum keempat
8. Pergub no. 47 tahun 2017
9. Penyerapan anggaran 2017