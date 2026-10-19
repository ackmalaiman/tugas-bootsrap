
# Tugas Modul 5 - Bootstrap 5.3.8

## 1. Pengertian Bootstrap

Bootstrap adalah framework CSS yang digunakan untuk membuat tampilan website dengan lebih mudah dan responsif. Bootstrap menyediakan class siap pakai untuk mengatur layout, tombol, form, navbar, warna, dan komponen lainnya.

## 2. Memasang Bootstrap

Bootstrap dapat digunakan dengan beberapa cara:

1. CDN, yaitu menghubungkan Bootstrap melalui URL internet.
2. Download lokal, yaitu mengunduh file CSS dan JavaScript Bootstrap ke dalam folder project.
3. Package manager seperti npm untuk memasang Bootstrap melalui terminal.

## 3. Grid dan Breakpoint

Grid Bootstrap digunakan untuk mengatur tata letak website menggunakan baris (`row`) dan kolom (`col`). Sistem grid membagi lebar halaman menjadi 12 kolom.

Breakpoint adalah batas ukuran layar yang digunakan untuk menyesuaikan tampilan website pada perangkat yang berbeda. Contohnya `sm`, `md`, `lg`, `xl`, dan `xxl`.

## 4. Class Bootstrap

Beberapa class Bootstrap dan kegunaannya:

1. `container`: mengatur lebar dan posisi konten.
2. `row`: membuat baris pada sistem grid.
3. `col`: membuat kolom.
4. `btn btn-primary`: membuat tombol berwarna biru.
5. `text-center`: membuat teks rata tengah.
6. `mt-3`: memberikan jarak di bagian atas elemen.
7. `img-fluid`: membuat gambar responsif.

## 5. Gambar Responsif

Agar gambar menyesuaikan ukuran layar, gunakan class `img-fluid` pada elemen gambar. Class ini membuat gambar mengikuti lebar wadahnya dan mempertahankan rasio gambar.

Contoh:

    <img src="gambar.jpg" class="img-fluid" alt="Gambar">

## 6. Membuat Tampilan dengan Bootstrap

Membuat halaman login Ruang Baca menggunakan Bootstrap 5.3.8 dengan fitur:

- Navbar berisi menu Beranda, Tentang, dan Bantuan.
- Form login dengan input Username dan Password.
- Checkbox Ingat saya.
- Tombol Masuk dan tautan Lupa password.
- Layout responsif untuk desktop dan perangkat mobile.

Halaman dibuat menggunakan HTML dan Bootstrap 5.3.8 melalui CDN.
