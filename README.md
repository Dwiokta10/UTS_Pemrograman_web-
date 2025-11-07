# Projek UTS Pemrograman_web Semester 3
|                |                    |
| -------------- | ------------------ |
|      _Nama_    | Dwi Okta Ramadhani |
|      _NIM_     |      312410056     |
|     _Kelas_    |      TI.24.A1      |
|  _Mata Kuliah_ | Pemrograman Web 1  |
| _Dosen Pengampu_ | Bapak Agung Nugroho, S.Kom., M.Kom. |
|  _Youtube_ | ..................|

## Deskripsi
Proyek ini merupakan tugas Ujian Tengah Semester pada mata kuliah Pemrograman Web 1 dengan tujuan untuk mengimplementasikan kemampuan mahasiswa dalam membangun aplikasi web front-end interaktif menggunakan HTML, CSS, dan JavaScript DOM.

Aplikasi ini meniru sistem pemesanan buku secara online, di mana pengguna dapat login, melihat katalog buku, melakukan pemesanan, serta melacak status pengiriman pesanan.
Seluruh data disimpan menggunakan variabel JavaScript dalam format Array JSON (tanpa koneksi ke database/server).

## Tujuan
1. Menerapkan struktur HTML yang semantik dan valid di setiap halaman website agar mudah dibaca, terorganisir, serta sesuai dengan standar pengembangan web.

2. Mendesain tampilan antarmuka (UI) menggunakan CSS eksternal dan internal supaya halaman web terlihat menarik, responsif di berbagai perangkat, dan memiliki gaya visual yang konsisten.

3. Menggunakan JavaScript DOM untuk membuat halaman menjadi lebih interaktif, seperti menambahkan data secara dinamis, menampilkan pop-up/modal, dan mengubah elemen halaman tanpa perlu reload.

4. Melatih kemampuan validasi form dan pemberian umpan balik (alert) agar pengguna mendapatkan notifikasi atau peringatan yang sesuai ketika terjadi kesalahan input.

5. Mengembangkan kreativitas dan kemampuan analisis logika dalam menyusun alur aplikasi, membangun interaksi antarhalaman, serta menampilkan data secara menarik dan mudah dipahami.

6. Menunjukkan pemahaman menyeluruh terhadap konsep front-end web development, mulai dari struktur HTML, desain CSS, hingga manipulasi DOM menggunakan JavaScript secara terintegrasi.

## Fitur-Fitur Aplikasi Web
1. Halaman Login (index.html)
Input Email dan Password dengan validasi menggunakan JavaScript.
Jika data salah muncul alert: “Email/Password yang anda masukkan salah”.
Tersedia tombol “Lupa Password” dan “Daftar” dalam bentuk modal box (popup).

### Data Pengguna
Aplikasi ini memiliki tiga pengguna simulasi yang disimpan di file data.js:
```
var dataPengguna = [
  { id: 1, nama: "Rina Wulandari", email: "rina@gmail.com", password: "rina123", role: "User" },
  { id: 2, nama: "Agus Pranoto", email: "agus@gmail.com", password: "agus123", role: "User" },
  { id: 3, nama: "Siti Marlina", email: "siti@gmail.com", password: "siti123", role: "Admin" }
];
```

Penjelasan:
Rina Wulandari dan Agus Pranoto berperan sebagai User.
Mereka bisa login untuk melihat katalog buku, melakukan pemesanan, dan melacak status pesanan mereka.
Siti Marlina berperan sebagai Admin,
yang memiliki akses tambahan seperti menambah data buku baru atau mengelola stok buku di halaman stok.html.
Data login ini menjadi dasar validasi pada halaman index.html, di mana JavaScript akan memeriksa apakah kombinasi email dan password cocok dengan data yang tersimpan.

3. Dashboard Menu (dashboard.html)
Menampilkan greeting otomatis sesuai waktu (Selamat Pagi/Siang/Sore).
Menu navigasi ke halaman Stok Buku, Tracking Pengiriman, Laporan, dan History Transaksi.

4. Informasi Stok / Katalog (stok.html)
Menampilkan data dari dataKatalogBuku dalam file data.js.
Fitur Tambah Stok Baru menggunakan JavaScript DOM yang memperbarui tabel secara dinamis.

5. Halaman Pemesanan (checkout.html)
Pengguna dapat mengisi data pemesan (nama, alamat, metode pembayaran).
Fitur edit dan hapus data pesanan secara langsung di tabel.
Validasi input untuk memastikan data tidak kosong, disertai alert feedback.

6. Informasi Pengiriman (tracking.html)
Input Nomor Delivery Order untuk melacak pesanan.
Menampilkan:
Nama Pemesan
Status Pengiriman (disimulasikan dengan progress bar dan warna)
Detail ekspedisi, tanggal kirim, jenis paket, total pembayaran.

## Kesimpulan
Dari pembuatan website ini, Saya jadi lebih paham gimana cara kerja dasar dari sebuah aplikasi web. Proyek UTS ini bukan cuma tentang menulis kode HTML, CSS, dan JavaScript, tapi juga belajar menyatukan semuanya jadi satu tampilan yang menarik dan bisa digunakan dengan baik.
selama prosesnya, saya belajar menyusun struktur HTML yang rapi dan semantik, mendesain tampilan supaya responsif dan enak dilihat, serta menggunakan JavaScript DOM untuk bikin elemen di halaman bisa berubah secara dinamis. Saya juga belajar bikin validasi form, menampilkan alert dan pop-up, jadi pengguna bisa tahu kalau ada data yang salah atau berhasil dikirim.
