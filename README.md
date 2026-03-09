# Personal Website - Kadek Aldi Pranata

Proyek ini adalah sebuah website profil pribadi sederhana yang dibuat menggunakan HTML dasar dan CSS. Website ini terdiri dari beberapa halaman, termasuk halaman utama, riwayat pendidikan, daftar skill teknis, dan contoh layout menggunakan tabel HTML.

## Tag HTML yang Digunakan

Berikut adalah daftar tag HTML yang digunakan dalam proyek ini beserta penjelasannya:

* `<html>` : Tag utama yang membungkus seluruh elemen HTML pada halaman. Menandakan bahwa dokumen ini adalah dokumen HTML.
* `<head>` : Bagian kepala dokumen yang berisi informasi meta (tidak ditampilkan langsung di halaman), seperti judul, link ke CSS, dan pengaturan karakter.
* `<title>` : Menentukan judul halaman yang akan muncul di tab browser pengguna.
* `<meta>` : Digunakan untuk memberikan metadata, seperti pengaturan karakter (`charset="UTF-8"`) dan pengaturan tampilan responsif (`viewport`).
* `<link>` : Digunakan untuk menautkan file eksternal, dalam hal ini menautkan file CSS utama (`style.css`) dan library ikon (Font Awesome).
* `<body>` : Bagian tubuh dokumen yang berisi semua konten yang akan ditampilkan di halaman web (teks, gambar, tautan, dll).
* `<header>` : Elemen semantik untuk bagian kepala atau spanduk utama website (judul besar di atas konten utama).
* `<h1>`, `<h2>`, `<h3>` : Tag heading untuk membuat judul dengan tingkatan berbeda. `<h1>` untuk judul utama/terbesar, `<h2>` untuk sub-judul, dan `<h3>` untuk sub-sub-judul.
* `<div>` : Kontainer serbaguna (block-level) yang digunakan untuk mengelompokkan elemen-elemen dan mempermudah pengaturan tata letak (layout) atau penerapan styling dengan CSS (menggunakan atribut `class` atau `id`).
* `<main>` : Elemen semantik yang menunjukkan konten utama yang unik dari dokumen tersebut.
* `<section>` : Elemen semantik yang digunakan untuk membagi konten halaman menjadi beberapa bagian atau kelompok tematik (misal: bagian profil, bagian detail informasi, bagian lokasi).
* `<img>` : Digunakan untuk menampilkan gambar (foto profil) pada halaman. Atribut `src` menunjukkan sumber gambar dan `alt` sebagai teks alternatif.
* `<p>` : Tag paragraf, digunakan untuk menampilkan teks atau keterangan berbentuk paragraf.
* `<a>` : Tag anchor (tautan), digunakan untuk membuat link atau tombol yang mengarahkan ke halaman lain, situs web eksternal, atau lokasi di peta.
* `<i>` : Umumnya digunakan untuk teks miring, namun dalam proyek ini digunakan secara spesifik untuk memuat ikon dari library Font Awesome.
* `<iframe>` : Digunakan untuk menyematkan (embed) dokumen HTML lain atau media pihak ketiga. Di sini, `<iframe`> digunakan untuk menyematkan Google Maps pada bagian Lokasi.
* `<footer>` : Elemen semantik untuk bagian catatan kaki (footer) website, biasanya berisi informasi hak cipta.
* `<ul>` : Unordered List, digunakan untuk membuat daftar item tanpa urutan tertentu (biasanya menggunakan bullet point). Digunakan pada halaman *skil.html*.
* `<ol>` : Ordered List, digunakan untuk membuat daftar item yang memiliki urutan terstruktur (seperti angka atau huruf). Digunakan pada halaman *pendidikan.html* dengan atribut `type="I"` (angka Romawi).
* `<li>` : List Item, elemen yang mewakili setiap item tunggal di dalam daftar `<ul>` maupun `<ol>`.
* `<table>` : Digunakan untuk membuat tabel HTML. Dalam halaman *layout.html*, tabel ini dimanfaatkan untuk membuat struktur tata letak web bergaya klasik.
* `<tr>` : Table Row, mendefinisikan sebuah baris di dalam tabel.
* `<td>` : Table Data, mendefinisikan sebuah sel data di dalam tabel.

## Penggunaan CSS (Simpel)

Website ini menggunakan CSS khusus di dalam file `style.css` untuk mengatur hampir keseluruhan tampilan visualnya beserta sedikit *internal CSS* di bagian `<style>` kepala beberapa halaman baru. Secara sederhana, berikut kegunaan style CSS di proyek ini:

* **Tampilan Warna:** Menggunakan warna biru (`--primary`) untuk tombol, gradient pada *header*, border interaktif saat di-hover, serta warna kontras terang atau gelap untuk teks agar mudah terbaca.
* **Layouting & Jarak:** Membuat kontainer utama berada tepat di tengah halaman dengan elemen grid yang responsif, menentukan ukuran gambar profil (dengan bentuk lingkaran dan diberikan bayangan).
* **Efek Interaktif (Hover):** Menambahkan efek transisi bergeser dan perubahan warna (`hover`) ketika kursor diarahkan ke modul informasi atau tombol.
* **Custom Bullets:** Memodifikasi bullet poin standar pada daftar *Unordered List* di halaman Skill dengan *icon check-circle* melalui penulisan _pseudo-element_ CSS (`::before`).

Website ini ditugaskan untuk tugas Pemrograman Berbasis Web dan dibuat agar tampak bersih serta responsif menyesuaikan perangkat baik tampilan desktop maupun seluler.
