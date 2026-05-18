# MyDataApp - UTS Pemrograman Android

Aplikasi Android "MyDataApp" adalah proyek Ujian Tengah Semester (UTS) untuk mata kuliah Pemrograman Android. Aplikasi ini berfungsi untuk mengelola data pengguna dengan fitur login aman dan entri data dinamis.

## Fitur Utama

### 1. Halaman Login
- **Verifikasi Kredensial:** Login menggunakan username dan password yang di-hardcode.
- **Session Management:** Status login disimpan menggunakan `SharedPreferences`.
- **Fitur Keamanan:** 
    - Toggle visibilitas password (ikon mata) untuk membuka/tutup tampilan password.
    - Menampilkan Toast Error jika kredensial salah atau data kosong.
- **Tombol Cancel:** Menghapus input username dan password secara cepat.

### 2. Dashboard & Entri Data
- **Pesan Selamat Datang:** Mengambil data username dari session.
- **Form Input Lengkap:**
    - NIM
    - Nama Lengkap
    - Program Studi
    - Kelas
    - Alamat
    - E-Mail
- **List Data Dinamis:** Data yang diinput akan muncul di bawah form menggunakan `ListView`.
- **Fitur Logout:** Menghapus status login dan kembali ke halaman awal.

## Kredensial Login (Hardcoded)
- **Username:** `admin`
- **Password:** `admin123`

## Teknologi yang Digunakan
- **Bahasa Pemrograman:** Java
- **UI Framework:** Material Design 3 (Android)
- **Penyimpanan Lokal:** SharedPreferences
- **Layouting:** XML (LinearLayout, TextInputLayout, ListView)

## Cara Menjalankan
1. Clone repository ini.
2. Buka proyek menggunakan Android Studio.
3. Tunggu proses Gradle Build selesai.
4. Jalankan aplikasi di Emulator atau Perangkat Fisik (Android API 24+).

---
**Dosen Pengampu:** Dr. Sopian Alviana, S.Kom., M.Kom  
**Mata Kuliah:** Pemrograman Android  
**Sifat Ujian:** Take Home Test (UTS)
