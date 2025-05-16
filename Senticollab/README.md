# SentiCollab - Emotional Learning Companion

SentiCollab adalah aplikasi web untuk memantau dan mencatat emosi pengguna secara real-time menggunakan kamera selama pembelajaran daring. Aplikasi ini membantu pengguna untuk lebih memahami kondisi emosional mereka dan memberikan rekomendasi yang sesuai.

## Fitur Utama

1. **Dashboard**
   - Ringkasan grafik emosi harian
   - Total entri emosi
   - Status emosi hari ini

2. **Input Emosi dengan Kamera**
   - Deteksi emosi otomatis menggunakan kamera
   - Analisis ekspresi wajah real-time
   - Penentuan intensitas otomatis (1-5)
   - Catatan tambahan
   - Rekomendasi otomatis untuk emosi negatif

3. **Riwayat Emosi**
   - Tabel riwayat lengkap
   - Opsi hapus entri

4. **Statistik Emosi**
   - Grafik distribusi emosi
   - Tren intensitas emosi

## Teknologi

- HTML5
- CSS3
- JavaScript (Vanilla)
- TensorFlow.js untuk deteksi wajah
- Chart.js untuk visualisasi data
- WebRTC untuk akses kamera
- Local Storage untuk penyimpanan data

## Cara Penggunaan

1. Buka file `index.html` di browser modern (Chrome/Firefox)
2. Berikan izin akses kamera saat diminta
3. Tunggu model deteksi emosi dimuat
4. Posisikan wajah Anda di depan kamera
5. Emosi akan terdeteksi secara otomatis
6. Tambahkan catatan jika diperlukan dan simpan
7. Lihat statistik dan riwayat di halaman terkait

## Persyaratan Sistem

- Browser modern dengan dukungan WebRTC (untuk akses kamera)
- Koneksi internet (untuk memuat model TensorFlow.js)
- Kamera web yang berfungsi

## Penyimpanan Data

Semua data disimpan secara lokal di browser menggunakan Local Storage. Data tidak akan hilang saat menutup browser, namun akan hilang jika Local Storage dibersihkan.

## Catatan Privasi

Aplikasi ini menggunakan kamera hanya untuk deteksi emosi secara real-time. Tidak ada gambar atau video yang disimpan atau dikirim ke server manapun. Semua pemrosesan dilakukan secara lokal di perangkat pengguna.
#