# README

## Website Profil Pribadi – Proyek Pemrograman Web

Halo! Saya **Lovien Najla Dhafiyah**, mahasiswi **Universitas Bengkulu** Program Studi **Informatika** Angkatan **2024** dengan **NPM G1A024055**. Website ini dibuat sebagai bagian dari pemenuhan tugas mata kuliah **Proyek Pemrograman Web**.

Website ini berisi informasi mengenai data diri saya, yang mencakup:
- Riwayat pendidikan yang telah dan/atau sedang saya tempuh
- Hobi dan minat
- Keahlian
- Informasi kontak
- Curriculum Vitae (CV) dalam format PDF yang dapat diunduh

---

## Struktur Folder dan File

### Bagan Struktur Folder

├── index.html  
├── about.html  
├── hobby.html  
├── contact.html  
├── CV-Lovien.pdf  
├── image  
│   ├── foto-profil.jpg  
│   └── logo.jpg  
└── video  
    └── halo.mp4  

### Penjelasan Struktur

1. Folder image  
Folder ini berisi foto profil yang digunakan pada halaman Home serta logo website yang digunakan sebagai ikon (favicon) pada tab browser.

2. Folder video  
Folder ini berisi video sapaan halo.mp4 yang digunakan pada halaman About Me.

3. File CV  
File CV-Lovien.pdf berisi Curriculum Vitae yang dapat diakses dan diunduh melalui halaman Download CV.

4. File HTML  
Terdapat empat file utama dengan format .html, yaitu:  
- index.html sebagai halaman utama (Home)  
- about.html sebagai halaman About Me  
- hobby.html sebagai halaman Hobi  
- contact.html sebagai halaman Kontak  

---

## Kode yang Dihighlight

Berikut beberapa bagian kode HTML penting yang digunakan dalam website ini.

### 1. Menampilkan Ikon (Favicon) pada Tab Browser

<link rel="icon" type="image/jpg" sizes="16x16" href="image/logo.jpg">
<link rel="manifest" href="site.webmanifest">

Kode ini digunakan untuk menampilkan logo sebagai ikon pada tab browser website.

---

### 2. Menampilkan Header dengan Posisi Rata Tengah

<header style="text-align: center;">

Kode ini digunakan untuk mengatur tampilan header agar berada di tengah halaman sehingga terlihat lebih rapi dan proporsional.

---

### 3. Menampilkan Video pada Halaman About Me

<p>
  <video width="320" height="240" controls>
    <source src="video/halo.mp4" type="video/mp4">
  </video>
</p>

Kode ini digunakan untuk menampilkan video sapaan pada halaman About Me.

---

### 4. Menautkan dan Mengunduh CV

<a href="CV-Lovien.pdf" target="_blank">Download CV</a>

Kode ini digunakan untuk menautkan file CV agar dapat dibuka di tab baru serta diunduh oleh pengunjung website.

---

## Tujuan Pembuatan Website

Website ini dibuat sebagai media untuk memperkenalkan profil diri secara digital sekaligus sebagai sarana pembelajaran dalam menerapkan konsep dasar pengembangan web menggunakan HTML, pengelolaan struktur folder, serta penggunaan elemen multimedia seperti gambar, video, dan file PDF.

---

Terima kasih telah mengunjungi dan membaca README ini.
