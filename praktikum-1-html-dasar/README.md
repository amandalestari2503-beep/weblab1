# Laporan Praktikum HTML Dasar

## 1. Tujuan Praktikum

Praktikum ini bertujuan untuk mengenal struktur dasar HTML, penggunaan tag, atribut, tautan, gambar, serta pembuatan daftar pada halaman web sederhana.

## 2. File `index.html`

File `index.html` berisi latihan dasar HTML, yaitu:

- Judul halaman menggunakan tag `<title>` dan heading `<h1>`, `<h2>`, serta `<h3>`.
- Paragraf dibuat menggunakan tag `<p>`.
- Penekanan teks menggunakan tag `<b>` untuk teks tebal dan `<i>` untuk teks miring.
- Rumus atau penulisan khusus menggunakan tag `<sub>` dan `<sup>`, seperti `H<sub>2</sub>O`.
- Gambar ditambahkan menggunakan tag `<img>` dengan atribut `src`, `width`, `alt`, dan `title`.
- Komentar HTML digunakan untuk memberi keterangan pada bagian kode.

Isi halaman menjelaskan pengertian HTML dan pembelajaran HTML dasar pada mata kuliah Pemrograman Web.

## 3. File `halaman2.html`

File `halaman2.html` berisi latihan navigasi dan penyajian informasi profil mahasiswa, yaitu:

- Navigasi halaman dibuat menggunakan tag `<nav>` dan `<a>`.
- Tautan mengarah ke `index.html`, `halaman2.html`, dan website eksternal Google.
- Daftar keahlian dibuat menggunakan unordered list `<ul>` dan `<li>`.
- Urutan belajar dan target belajar dibuat menggunakan ordered list `<ol>` dan `<li>`.
- Data profil ditampilkan menggunakan heading `<h1>`, `<h2>`, paragraf `<p>`, dan gambar `<img>`.
- Garis pemisah ditambahkan menggunakan tag `<hr>`.

Data yang ditampilkan meliputi nama mahasiswa, program studi Teknik Informatika, keahlian HTML/CSS/JavaScript, serta target pembelajaran.

## 4. Tag dan Atribut yang Dipelajari

| Tag/Atribut | Fungsi |
| --- | --- |
| `<!DOCTYPE html>` | Menentukan bahwa dokumen menggunakan HTML5 |
| `<html>` | Elemen utama dokumen HTML |
| `<head>` | Menyimpan informasi halaman |
| `<title>` | Menentukan judul pada tab browser |
| `<body>` | Menyimpan isi yang ditampilkan browser |
| `<h1>` sampai `<h3>` | Membuat judul dan subjudul |
| `<p>` | Membuat paragraf |
| `<a href="...">` | Membuat tautan |
| `<img src="...">` | Menampilkan gambar |
| `<ul>`, `<ol>`, `<li>` | Membuat daftar tidak berurutan dan berurutan |
| `alt` | Memberikan teks alternatif pada gambar |
| `width` | Mengatur lebar gambar |
| `title` | Memberikan keterangan tambahan saat kursor diarahkan |

## 5. Hasil Praktikum

Setelah file HTML dibuka melalui browser, halaman menampilkan materi dasar HTML, navigasi antarhalaman, profil mahasiswa, daftar keahlian, dan target belajar.

## 6. Catatan Perbaikan

Beberapa bagian source HTML masih perlu dirapikan agar sesuai standar HTML:

- Setiap file sebaiknya hanya memiliki satu struktur `<!DOCTYPE html>`, `<html>`, `<head>`, dan `<body>`.
- Beberapa tag penutup seperti `</body>` dan `</html>` berada sebelum seluruh isi halaman selesai.
- Pada `index.html`, tag `<stong>` seharusnya ditulis `<strong>`.
- Tag `<sup>` untuk contoh luas belum memiliki isi.
- Pastikan file gambar `profil.jpg` tersedia di folder yang sama agar gambar dapat ditampilkan.

## 7. Kesimpulan

Praktikum ini memberikan pemahaman awal tentang struktur dokumen HTML dan penggunaan tag-tag dasar untuk membuat halaman web. HTML berfungsi menyusun struktur dan konten halaman, sedangkan browser menerjemahkan kode tersebut menjadi tampilan yang dapat dilihat pengguna.
