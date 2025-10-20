# Ujian Praktikum Flutter POS SQLite

**Nama:Nisa Eka Kholifaturrizkiah**
**NIM:362458302018**
**Kelompok:6**

## Deskripsi Fitur yang Ditambahkan
* Menambahkan validasi input login agar pengguna tidak bisa menekan tombol Login jika kolom Username atau Password masih kosong.
Fitur ini memastikan proses login lebih aman dan menghindari error saat field belum diisi.

## File yang Dimodifikasi
* lib/screens/auth/login_screen.dart. Menambahkan kode validasi input sebelum proses login. Jika kolom kosong, aplikasi menampilkan pesan peringatan menggunakan SnackBar.

## Cara Menjalankan Aplikasi
* flutter pub get
* flutter run
* Buka halaman Login.
* Kosongkan salah satu atau kedua kolom (Username dan Password).
* Tekan tombol Login.
* Aplikasi akan menampilkan pesan error: "Username dan Password tidak boleh kosong"

## Catatan Tambahan
* Kendala: Saat dijalankan di browser (Chrome), tombol Login tidak berfungsi karena proyek menggunakan sqflite yang hanya mendukung Android/iOS.