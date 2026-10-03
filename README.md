# PRAKTIKUM 2 - HTML LANJUTAN

## Identitas Mahasiswa

**Nama:** Anggun Kusuma  
**NIM:** 312510045  
**Program Studi:** Teknik Informatika  

---

# A. Tujuan Praktikum

Praktikum 2 HTML Lanjutan bertujuan untuk mempelajari penggunaan
tabel pada HTML, form dan berbagai jenis input, semantic HTML,
multimedia, serta validasi form dasar menggunakan atribut HTML.

Pada praktikum ini HTML menjadi fokus utama dalam pembuatan halaman
web. Materi yang dipelajari meliputi tabel, form, input, semantic
HTML, audio, video, dan validasi form dasar.

---

# B. Persiapan Praktikum

Praktikum dilakukan menggunakan:

- Visual Studio Code sebagai text editor.
- Web browser untuk menjalankan dan melihat hasil halaman HTML.
- Git dan GitHub untuk menyimpan hasil praktikum.

Repository yang digunakan dalam praktikum ini adalah:

**Lab2Web**

Struktur folder project:

```text
Lab2Web/
├── index.html
├── biodata.html
├── media/
│   ├── audio.mp3
│   └── video.mp4
├── Screenshot/
│   ├── 01-tabel-data-mahasiswa.png
│   ├── 02-tabel-lanjutan.png
│   ├── 03-form-pendaftaran.png
│   ├── 04-radio-checkbox.png
│   ├── 05-select-textarea.png
│   ├── 06-validasi-form.png
│   ├── 07-semantic-html.png
│   ├── 08-multimedia.png
│   └── 09-biodata.png
└── README.md

C. HASIL PRAKTIKUM

1. Tabel HTML

Pada praktikum pertama dibuat tabel HTML untuk menampilkan data
mahasiswa dalam bentuk baris dan kolom.

Elemen yang digunakan dalam tabel adalah:

<table> digunakan untuk membuat struktur tabel.
<tr> digunakan untuk membuat baris tabel.
<th> digunakan untuk membuat header atau judul kolom.
<td> digunakan untuk membuat sel yang berisi data.

Data mahasiswa yang digunakan:

No	NIM	Nama	Program Studi
1	312510011	Marisa	Teknik Informatika
2	312510461	Kensha	Teknik Informatika
3	312510045	Anggun	Teknik Informatika

Tabel digunakan untuk menyajikan data dalam bentuk baris dan kolom
sehingga data dapat ditampilkan secara lebih terstruktur.

2. Struktur Tabel Lanjutan

Pada praktikum kedua dibuat tabel yang memiliki struktur lebih
lengkap menggunakan elemen:

<caption>
<thead>
<tbody>
<tfoot>

<caption> digunakan untuk memberikan judul atau keterangan pada
tabel.

<thead> digunakan untuk bagian kepala tabel.

<tbody> digunakan untuk bagian isi atau data utama tabel.

<tfoot> digunakan untuk bagian bawah tabel, misalnya untuk
menampilkan hasil atau rata-rata.

Selain itu digunakan atribut colspan untuk menggabungkan beberapa
kolom menjadi satu.

3. Form HTML

Pada praktikum ketiga dibuat form pendaftaran mahasiswa.

Form digunakan untuk menerima input atau data dari pengguna.

Jenis input yang digunakan antara lain:

Nama
Email
Password
Tanggal lahir
Tombol Submit
Tombol Reset

Contoh input yang digunakan:

<input type="text">
<input type="email">
<input type="password">
<input type="date">

Tombol submit digunakan untuk mengirim data form, sedangkan tombol
reset digunakan untuk mengembalikan atau mengosongkan kembali data
yang telah dimasukkan.

4. Radio Button dan Checkbox

Pada praktikum keempat digunakan radio button dan checkbox.

Radio button digunakan untuk memilih satu pilihan dari beberapa
pilihan dalam satu kelompok.

Contohnya adalah pilihan jenis kelamin:

Laki-laki
Perempuan

Sedangkan checkbox dapat digunakan untuk memilih satu atau beberapa
pilihan.

Contohnya adalah pilihan hobi:

Membaca
Musik
Olahraga

Dengan demikian, radio button digunakan untuk satu pilihan dalam
satu kelompok, sedangkan checkbox dapat digunakan untuk beberapa
pilihan.

5. Select dan Textarea

Pada praktikum kelima digunakan elemen <select> dan <textarea>.

<select> digunakan untuk membuat daftar pilihan yang dapat dipilih
oleh pengguna.

Contohnya adalah pilihan program studi:

Teknik Informatika
Sistem Informasi

Sedangkan <textarea> digunakan untuk menerima teks yang lebih
panjang dan dapat terdiri dari beberapa baris.

Contohnya adalah input alamat mahasiswa.

6. Validasi Form Dasar

Pada praktikum keenam dilakukan validasi form dasar menggunakan
atribut HTML.

Atribut yang digunakan adalah:

required
minlength
min
max
type="email"

Fungsi atribut tersebut antara lain:

required digunakan untuk membuat input wajib diisi.

minlength digunakan untuk menentukan panjang minimum teks.

min digunakan untuk menentukan nilai minimum.

max digunakan untuk menentukan nilai maksimum.

type="email" digunakan untuk input alamat email dan memberikan
validasi terkait format email.

Validasi dilakukan dengan mencoba mengirim form tanpa mengisi data
untuk melihat pesan validasi yang diberikan oleh browser.

7. Semantic HTML

Pada praktikum ketujuh digunakan Semantic HTML.

Semantic HTML menggunakan elemen yang memiliki makna jelas dalam
struktur halaman.

Elemen semantic yang digunakan:

<header>

Digunakan untuk bagian kepala halaman atau bagian tertentu.

<nav>

Digunakan untuk bagian navigasi.

<main>

Digunakan untuk menunjukkan konten utama halaman.

<section>

Digunakan untuk mengelompokkan konten berdasarkan bagian tertentu.

<article>

Digunakan untuk konten yang dapat berdiri sendiri.

<aside>

Digunakan untuk informasi tambahan atau konten pelengkap.

<footer>

Digunakan untuk bagian kaki halaman atau bagian tertentu.

Penggunaan semantic HTML membuat struktur halaman menjadi lebih
jelas dan terorganisasi.

8. Multimedia HTML

Pada praktikum kedelapan ditambahkan multimedia berupa audio dan
video.

Audio ditampilkan menggunakan elemen <audio>:

<audio controls>
    <source src="media/audio.mp3" type="audio/mpeg">
    Browser tidak mendukung audio.
</audio>

Video ditampilkan menggunakan elemen <video>:

<video controls width="480">
    <source src="media/video.mp4" type="video/mp4">
    Browser tidak mendukung video.
</video>

File audio dan video disimpan di dalam folder media.

Struktur folder:

media/
├── audio.mp3
└── video.mp4

Atribut controls digunakan agar browser menampilkan kontrol untuk
memutar audio atau video.

9. Proyek Mini - Biodata Mahasiswa

Pada praktikum kesembilan dibuat proyek mini berupa halaman biodata
mahasiswa.

Proyek mini ini menggabungkan materi yang telah dipelajari
sebelumnya, yaitu:

Tabel
Form
Validasi dasar
Semantic HTML
Multimedia

File proyek mini dibuat dengan nama:

biodata.html

Halaman biodata berisi data mahasiswa, form biodata, pilihan
program studi, jenis kelamin, alamat, serta elemen multimedia.

Proyek mini ini bertujuan untuk menerapkan beberapa materi HTML
Lanjutan ke dalam satu halaman web.


10 Pertanyaan beserta jawabannya
1. Apa fungsi <table>, <tr>, <th>, dan <td>?

Jawaban:  
Tag <table> digunakan untuk membuat struktur tabel pada halaman HTML. Tabel digunakan untuk menyajikan data dalam bentuk baris dan kolom.

Tag <tr> (table row) digunakan untuk membuat baris pada tabel.

Tag <th> (table header) digunakan untuk membuat sel header atau judul kolom pada tabel. Biasanya digunakan untuk memberikan keterangan mengenai data yang berada di bawahnya.

Tag <td> (table data) digunakan untuk membuat sel yang berisi data pada tabel.

2. Apa perbedaan <th> dan <td>?

Jawaban:
Perbedaan <th> dan <td> terletak pada fungsi penggunaannya.

<th> digunakan untuk membuat header atau judul kolom, sedangkan <td> digunakan untuk membuat isi atau data tabel.
secara sederhana:
<th> = judul/header tabel
<td> = data tabel

3. Apa fungsi colspan pada tabel?

Jawaban:
Atribut colspan digunakan untuk menggabungkan dua atau lebih kolom menjadi satu sel pada tabel. Dalam praktikum, colspan digunakan pada bagian tabel untuk menggabungkan sel, dan modul juga meminta mahasiswa melakukan eksperimen dengan atribut tersebut.

4. Apa fungsi <form> dalam HTML?

Jawaban:
Tag <form> digunakan untuk membuat formulir pada halaman web yang berfungsi menerima input atau data dari pengguna.
Di dalam <form> dapat digunakan berbagai jenis input, misalnya:
text untuk teks
email untuk alamat email
password untuk kata sandi
number untuk angka
date untuk tanggal
radio untuk pilihan tunggal
checkbox untuk satu atau beberapa pilihan
submit untuk mengirim form
reset untuk mengatur ulang form

5. Apa perbedaan radio button dan checkbox?

Jawaban:
Radio button digunakan untuk memilih satu pilihan dari beberapa pilihan dalam satu kelompok.
Sedangkan checkbox digunakan ketika pengguna dapat memilih satu atau beberapa pilihan.

6. Mengapa <label> sebaiknya terhubung dengan id input melalui atribut for?

Jawaban:
Tag <label> digunakan untuk memberikan keterangan atau nama pada sebuah input.
Atribut for pada <label> digunakan untuk menghubungkan label dengan elemen input yang memiliki id yang sama.

7. Apa perbedaan <textarea> dengan <input type="text">?

Jawaban:
<input type="text"> digunakan untuk menerima input teks dalam satu baris.
Sedangkan <textarea> digunakan untuk menerima teks yang lebih panjang dan dapat terdiri dari beberapa baris. Dalam modul, <textarea> digunakan untuk memasukkan alamat, sedangkan input teks digunakan untuk memasukkan data seperti nama

8. Apa fungsi semantic HTML seperti <header>, <nav>, <main>, <section>, <article>, <aside>, dan <footer>?

Jawaban:
Semantic HTML adalah penggunaan elemen HTML yang mempunyai makna yang jelas dalam struktur halaman.
Fungsi masing-masing elemen adalah:

<header>
Digunakan untuk membuat bagian kepala halaman atau kepala suatu bagian.
<nav>
Digunakan untuk membuat bagian navigasi, biasanya berisi link untuk berpindah halaman atau bagian.
<main>
Digunakan untuk menunjukkan konten utama halaman.
<section>
Digunakan untuk mengelompokkan konten berdasarkan bagian atau topik tertentu.
<article>
Digunakan untuk membuat konten yang dapat berdiri sendiri, misalnya artikel atau informasi tertentu.
<aside
Digunakan untuk konten tambahan atau pelengkap dari konten utama
<footer
Digunakan untuk membuat bagian kaki halaman atau bagian tertentu.

9. Apa fungsi required, min, max, dan minlength?

Jawaban:
Atribut tersebut digunakan untuk melakukan validasi form dasar pada HTML.

required
Digunakan untuk membuat suatu input wajib diisi.
minlength
Digunakan untuk menentukan jumlah karakter minimum yang harus dimasukkan pada input teks.
min
Digunakan untuk menentukan nilai minimum.
min
Digunakan untuk menentukan nilai minimum.

10. Apa perbedaan elemen <audio> dan <video>?

Jawaban:
Elemen <audio> digunakan untuk menampilkan atau memutar file audio pada halaman HTML.
Sedangkan elemen <video> digunakan untuk menampilkan atau memutar file video.
tribut controls digunakan agar browser menampilkan kontrol untuk multimedia, seperti tombol Play/Pause dan kontrol lainnya.

Dalam modul, audio menggunakan file media/audio.mp3, sedangkan video menggunakan media/video.mp4.

Jadi perbedaannya adalah:
<audio> → untuk multimedia berupa suara/audio.
<video> → untuk multimedia berupa video.
