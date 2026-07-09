````md
# Aplikasi Perpustakaan Digital Laravel

## Gambaran Umum
Aplikasi ini merupakan sistem informasi perpustakaan berbasis web yang dibuat untuk membantu pengelolaan operasional perpustakaan secara lebih rapi dan efisien. Sistem ini mendukung pengelolaan data buku, data anggota, transaksi peminjaman, pengembalian, serta penyajian informasi ringkas melalui dashboard.

## Fitur Utama

### 1. Login dan Autentikasi
Sistem menyediakan fitur login untuk membatasi akses pengguna dan menjaga keamanan data aplikasi.

![Tampilan Login](isi_dengan_path_atau_link_gambar_login)

### 2. Manajemen Data Buku
Pengguna dapat menambahkan, melihat, mengubah, dan menghapus data buku yang tersedia di perpustakaan.

![Tampilan Data Buku](isi_dengan_path_atau_link_gambar_buku)

### 3. Manajemen Data Anggota
Aplikasi menyediakan pengelolaan data anggota perpustakaan, mulai dari penambahan anggota baru sampai pembaruan informasi anggota.

![Tampilan Data Anggota](isi_dengan_path_atau_link_gambar_anggota)

### 4. Transaksi Peminjaman dan Pengembalian
Fitur ini digunakan untuk mencatat aktivitas peminjaman buku oleh anggota serta proses pengembalian buku ke perpustakaan.

![Tampilan Transaksi](isi_dengan_path_atau_link_gambar_transaksi)

### 5. Dashboard dan Ringkasan Data
Dashboard menampilkan informasi penting secara singkat, misalnya jumlah buku, jumlah anggota, dan data transaksi.

![Tampilan Dashboard](isi_dengan_path_atau_link_gambar_dashboard)

### 6. Laporan
Sistem dapat menampilkan data laporan yang membantu proses pemantauan aktivitas perpustakaan.

![Tampilan Laporan](isi_dengan_path_atau_link_gambar_laporan)

## Teknologi yang Digunakan
Aplikasi ini dibangun menggunakan beberapa teknologi berikut:

- Laravel 12
- MySQL
- Bootstrap 5
- PHP
- JavaScript

## Cara Menjalankan Project

Berikut langkah-langkah untuk menjalankan aplikasi di komputer lokal.

### 1. Clone repository
```bash
git clone <url_repository_anda>
cd Pertemuan15
````

### 2. Install dependency backend

```bash
composer install
```

### 3. Install dependency frontend

```bash
npm install
npm run build
```

### 4. Konfigurasi file environment

Salin file `.env.example` menjadi `.env`.

```bash
cp .env.example .env
```

Setelah itu, buka file `.env` lalu sesuaikan konfigurasi database, misalnya:

```env
DB_DATABASE=perpustakaan_laravel
DB_USERNAME=root
DB_PASSWORD=
```

### 5. Generate application key

```bash
php artisan key:generate
```

### 6. Jalankan migrasi dan seeder

```bash
php artisan migrate --seed
```

Perintah ini akan:

* membuat tabel ke database
* mengisi data awal untuk kebutuhan pengujian aplikasi

### 7. Menjalankan server Laravel

```bash
php artisan serve
```

Setelah server aktif, aplikasi bisa dibuka melalui browser pada alamat:

```bash
http://127.0.0.1:8000
```

## Catatan

Pastikan beberapa hal berikut sudah tersedia sebelum project dijalankan:

* PHP dan Composer sudah terpasang
* Node.js dan NPM sudah tersedia
* MySQL aktif
* database untuk aplikasi sudah dibuat terlebih dahulu
* konfigurasi `.env` sudah sesuai dengan database lokal Anda

```
```
