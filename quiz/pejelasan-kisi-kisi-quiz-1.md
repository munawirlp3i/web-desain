📢 KISI-KISI RESMI QUIZ 1: PEMROGRAMAN WEB DASAR
Tema Quiz: Portal Kemahasiswaan / Kampus

Sifat Ujian: Open Book & Open Google.

Format: Live Coding Mandiri di Lab (Hasil akhir wajib di-commit ke Git).

Berikut adalah materi-materi krusial dari Pertemuan 1 s/d 3 yang wajib kalian kuasai untuk menyelesaikan proyek Quiz:

1. HTML Dasar & Struktur Data (Pertemuan 1)
Kalian harus bisa menyusun konten dasar sebuah halaman web tanpa bantuan CSS terlebih dahulu.

Hierarki Judul: Memahami penggunaan tag <h1> sampai <h6> untuk struktur teks yang benar.

Media & Tautan: Cara menampilkan gambar lokal/internet (<img>) dan membuat link aktif (<a>) yang membuka di tab baru (target="_blank").

Daftar (Lists): Bisa membedakan kapan harus menggunakan daftar berpoin (<ul>) dan daftar berurutan (<ol>).

Tabel Data: Mampu membuat tabel informasi lengkap dengan kepala tabel (<th>), baris (<tr>), dan kolom (<td>), serta menggunakan atribut border dan cellpadding.

2. Semantic HTML & Form Input (Pertemuan 2)
Quiz ini akan menguji apakah kalian bisa membuat web yang "cerdas" dan interaktif secara pasif.

Layout Blok (Semantic): Wajib membagi halaman web menggunakan tag <header>, <nav>, <main>, <section>, dan <footer>. Jangan gunakan <div> untuk semua hal!

Formulir Interaktif: Mampu membuat wadah <form> yang rapi menggunakan bantuan kerangka <table> di dalamnya agar posisi input sejajar.

Variasi Tipe Input: Wajib menguasai pembuatan input teks biasa (type="text"), pemilihan tanggal (type="date"), pilihan lingkaran (type="radio"), dan menu jatuh/dropdown (<select> & <option>).

Aksesibilitas: Menghubungkan teks petunjuk dengan kotak input menggunakan <label for="..."> dan id="...".

3. CSS Dasar & Box Model (Pertemuan 3)
Kerangka yang sudah dibuat harus diberi "bumbu" visual agar menarik dilihat.

External CSS: Menghubungkan file HTML dengan file .css terpisah menggunakan tag <link> di dalam elemen <head>.

Targeting (Selectors): Tahu kapan harus menggunakan Tag Selector, Class Selector (.), dan ID Selector (#).

The Box Model Mastery: Paham betul bedanya Padding (jarak ke dalam) dan Margin (jarak ke luar) untuk mengatur kerapian form dan tombol.

Trik Menengahkan Kotak: Bisa membuat kotak konten utama berada persis di tengah layar laptop menggunakan kombinasi max-width dan margin: auto.

Interaksi Dinamis: Bisa mengubah warna atau tampilan tombol saat kursor mouse menyentuhnya menggunakan efek :hover.

💡 Tips Sukses Menghadapi Quiz:
Manajemen Waktu: Jangan habiskan waktu 30 menit hanya untuk memilih warna CSS. Buat dulu seluruh struktur HTML-nya dari atas sampai bawah, setelah semua fitur muncul, baru hias menggunakan CSS.

Sintaks Mandiri: Karena AI dilarang, pastikan kalian tahu cara mencari dokumentasi tag di Google (misal lewat MDN Web Docs atau W3Schools) jika tiba-tiba lupa nama atributnya.

Pahami Kodemu: Dosen akan melakukan pemeriksaan acak. Jika kodemu berjalan lancar tapi kamu tidak bisa menjelaskan fungsi dari baris kode yang kamu tulis, akan ada pengurangan nilai secara signifikan.

📘 Panduan Tambahan: Mengenal float & :hover
Sebelum masuk ke kode, berikut konsep super simpel untuk dua materi baru ini:

1. Apa itu float?
Secara alami, elemen HTML akan menumpuk dari atas ke bawah. float digunakan untuk memaksa suatu elemen (biasanya gambar) bergeser ke kanan (float: right) atau ke kiri (float: left), sehingga teks di sekitarnya bisa mengalir rapi di sampingnya (seperti artikel koran).

2. Apa itu :hover?
Ini disebut Pseudo-class. Fungsinya adalah mengubah gaya CSS hanya ketika kursor mouse berada di atas elemen tersebut. Sangat sering dipakai pada tombol (button) atau link (a) agar website terasa hidup dan interaktif