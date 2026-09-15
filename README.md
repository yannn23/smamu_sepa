# Sistem Absensi SMA Manba'ul Ulum

Aplikasi Absensi Berbasis Web menggunakan Google Apps Script dan Google Sheets

Dibuat oleh: **Yann**

## 📌 Fitur
- **3 Role**: Admin, Guru, Siswa
- **Login**: Validasi data dari Google Sheet
- **Absensi Siswa**: Otomatis mencatat Tanggal, Jam, Kelas
- **Absensi Guru**: Otomatis mencatat Jam Masuk
- **Riwayat**: Cek riwayat absensi siswa
- **Database**: Semua data tersimpan di Google Sheet

## 🛠️ Teknologi
- HTML5, CSS3, JavaScript
- Google Apps Script
- Google Sheets

## 🚀 Cara Penggunaan

### 1. Untuk Admin/Guru
- Role: `Admin` atau `Guru`
- Username & Password: Lihat di tab `Data_Guru` pada Google Sheet

### 2. Untuk Siswa  
- Role: `Siswa`
- NIS: Lihat di tab `Data_Siswa`
- Password: Tanggal Lahir format DDMMYYYY

## 📊 Struktur Google Sheet
Pastikan ada 4 tab:
1. `Data_Guru` : username, password, nama, role
2. `Data_Siswa` : NIS, password, nama, kelas
3. `Absen_Siswa` : Riwayat absen siswa
4. `Absen_Guru` : Riwayat absen guru

## 🔗 Link Penting
- **Aplikasi**: [Link Github Pages Kamu]
- **Database**: Google Sheet SMA Manba'ul Ulum

## 📄 Lisensi
Project ini menggunakan lisensi MIT. Bebas digunakan untuk keperluan sekolah.

---
© 2026 Yann - SMA Manba'ul Ulum
