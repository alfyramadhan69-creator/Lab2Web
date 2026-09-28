# Praktikum 2: HTML Lanjutan

**Nama:** Alfy Ramadhan
**Program Studi:** Teknik Informatika — Universitas Pelita Bangsa
**NIM:** 312510298
**Mata Kuliah:** Pemrograman Web

## Langkah-langkah Praktikum

### 1. Membuat Tabel Data Mahasiswa
Membuat tabel dengan `<table>`, `<tr>`, `<th>`, `<td>` berisi 3 data mahasiswa.


![Langkah 1](screenshots/Langkah%201.PNG)



### 2. Tabel dengan thead, tbody, tfoot
Mengembangkan tabel dengan `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, dan `colspan`.


![Langkah 2](screenshots/Langkah%202.PNG)



### 3. Form Registrasi Mahasiswa
Membuat form dengan input text, email, password, dan date, serta tombol submit dan reset.


![Langkah 3](screenshots/Langkah%203.PNG)



### 4. Radio Button dan Checkbox
Menambahkan pilihan jenis kelamin (radio) dan keahlian (checkbox).


![Langkah 4](screenshots/Langkah%204.PNG)



### 5. Select dan Textarea
Menambahkan dropdown program studi dan kolom alamat.


![Langkah 5](screenshots/Langkah%205.PNG)



### 6. Validasi Form Dasar
Menggunakan `required`, `minlength`, `min`, `max`, dan `type`.


![Langkah 6](screenshots/Langkah%206.PNG)



### 7. Semantic HTML
Menyusun halaman dengan header, nav, main, section, article, aside, footer.


![Langkah 7](screenshots/Langkah%207.PNG)



### 8. Multimedia
Menambahkan elemen audio/video dari folder `media`.


![Langkah 8](screenshots/Langkah%208.PNG)



### 9. Proyek Mini: Biodata Mahasiswa
Menggabungkan semantic HTML, tabel, form, validasi, dan multimedia di `biodata.html`.


![Langkah 9](screenshots/Langkah%209.PNG)



## Jawaban Pertanyaan
1. **Apa fungsi `<table>`, `<tr>`, `<th>`, dan `<td>`?**
   * <table> digunakan untuk mendefinisikan tabel secara keseluruhan.
   * <tr> (*table row*) digunakan untuk membuat baris di dalam tabel.
   * <th> (*table header*) digunakan untuk membuat sel kepala/judul tabel (biasanya tercetak tebal dan berada di tengah).
   * <td> (*table data*) digunakan untuk membuat sel data biasa di dalam tabel.

2. **Apa perbedaan `<th>` dan `<td>`?**
   * <th> digunakan khusus untuk sel judul atau header dengan teks otomatis tebal dan posisi di tengah, sedangkan <td> digunakan untuk sel isi data reguler dengan teks normal dan rata kiri.

3. **Apa fungsi `colspan` pada tabel?**
   * colspan berfungsi untuk menggabungkan beberapa kolom menjadi satu sel secara horizontal.

4. **Apa fungsi `<form>` dalam HTML?**
   * <form> berfungsi untuk menampung dan mengelompokkan elemen-elemen input pengguna (seperti teks, tombol, pilihan) guna dikirimkan ke server atau diproses lebih lanjut.

5. **Apa perbedaan radio button dan checkbox?**
   * **Radio button** (type="radio") hanya mengizinkan pengguna memilih **satu** opsi dari beberapa pilihan yang tersedia dalam satu grup yang sama.
   * **Checkbox** (type="checkbox") mengizinkan pengguna memilih **banyak (lebih dari satu atau bahkan tidak sama sekali)** opsi secara bersamaan.

6. **Mengapa `<label>` sebaiknya terhubung dengan `id` input melalui atribut `for`?**
   * Agar ketika teks pada <label> diklik oleh pengguna, kursor atau fokus akan otomatis berpindah ke kotak input yang sesuai, serta memudahkan pembaca layar (*screen reader*) bagi penyandang disabilitas.

7. **Apa perbedaan `<textarea>` dengan `input type="text"`?**
   * <input type="text"> digunakan untuk teks singkat satu baris (seperti nama atau email), sedangkan <textarea> digunakan untuk memasukkan teks panjang yang terdiri dari banyak baris (seperti alamat atau catatan).

8. **Apa fungsi semantic HTML seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`?**
   * Memberikan makna atau struktur yang jelas pada bagian-bagian dokumen web sehingga mudah dibaca oleh mesin pencari (*SEO*) dan pengembang lain:
     * <header>: Kepala dokumen/bagian atas.
     * <nav>: Menu navigasi tautan.
     * <main>: Konten utama halaman.
     * <section>: Pengelompokan bagian topik tertentu.
     * <article>: Konten mandiri yang bisa berdiri sendiri (seperti berita/artikel).
     * <aside>: Konten pelengkap/samping (sidebar).
     * <footer>: Bagian kaki halaman/bawah.

9. **Apa fungsi `required`, `min`, `max`, dan `minlength`?**
   * required: Memastikan input wajib diisi sebelum form dikirim.
   * min & max: Batasan nilai minimum dan maksimum (biasanya untuk angka atau tanggal).
   * minlength: Batasan jumlah karakter minimum yang harus diketikkan.

10. **Apa perbedaan elemen `<audio>` dan `<video>`?**
    * <audio> digunakan untuk memutar file suara/musik (*audio*), sedangkan <video> digunakan untuk memutar file gambar bergerak bersuara (*video*).

## Struktur Output
Lab2Web/
├── index.html
├── biodata.html
├── media/
│   ├── audio.ogg
│   └── video.mp4
├── screenshots/
│   ├── langkah1.png
│   ├── langkah2.png
│   └── ... (sampai langkah9.png)
└── README.md