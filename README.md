# 📊 IG Follower Analyzer

<p align="center">
  <b>Instagram Followers & Following Analyzer</b><br>
  Offline • Free • Privacy Friendly
</p>

<p align="center">
  <a href="https://muhzarx.github.io/UnfollowInstagram/">
    🚀 OPEN LIVE DEMO
  </a>
  &nbsp; | &nbsp;
  <a href="https://github.com/Muhzarx/UnfollowInstagram">
    ⭐ VIEW SOURCE CODE
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Offline-100%25-success">
  <img src="https://img.shields.io/badge/Platform-Web-blue">
  <img src="https://img.shields.io/badge/License-Free-purple">
</p>

# UnfollowInstagram
# 📊 IG Follower Analyzer

Tools sederhana untuk menganalisis hubungan followers dan following Instagram secara **100% offline** menggunakan file JSON hasil ekspor data Instagram.

Tidak perlu login Instagram, tidak menggunakan API, dan tidak mengirimkan data pribadi ke server.

## ✨ Features

- **Unfollow Tracker** — Mendeteksi akun yang sudah berhenti mengikuti kita berdasarkan perbandingan data lama dan terbaru.
- **Not Following Back** — Mengetahui akun yang kita ikuti tetapi tidak mengikuti balik.
- **New Followers** — Mendeteksi akun yang baru mengikuti kita.
- **Mutual Followers** — Menampilkan akun yang saling mengikuti.
- **Search Username** — Mencari username dengan mudah.
- **Export CSV** — Mengunduh hasil analisis dalam format CSV.
- **Offline Mode** — Seluruh proses dilakukan langsung di browser.

## 🚀 How to Use

### 1. Download Data Instagram

Pertama, kamu perlu mengunduh data Instagram milikmu sendiri.

1. Buka Instagram.
2. Masuk ke **Settings and activity**.
3. Pilih **Accounts Center**.
4. Masuk ke **Your information and permissions**.
5. Pilih **Download your information**.
6. Pilih akun Instagram yang ingin dianalisis.
7. Pilih informasi **Followers and following**.
8. Atur format menjadi **JSON**.
9. Buat dan unduh file data Instagram.

### 2. Extract File ZIP

Setelah file ZIP berhasil diunduh:

1. Extract file ZIP.
2. Buka folder `connections/followers_and_following` atau folder `followers_and_following` sesuai struktur ekspor Instagram.
3. Cari file berikut:

**Followers:**
- `followers_1.json`
- `followers_2.json`
- `followers_3.json` (jika tersedia)

Pilih semua file followers yang tersedia.

**Following:**
- `following.json`

### 3. Open IG Follower Analyzer

1. Download file `ig_follower_analyzer_offline.html` dari repository ini.
2. Buka file menggunakan browser seperti Google Chrome, Microsoft Edge, atau Firefox.
3. Tidak perlu menginstal aplikasi tambahan.
4. Tools siap digunakan secara offline.

### 4. Upload JSON Files

Pada halaman utama tools:

1. Masukkan semua file `followers_*.json` ke bagian **Followers saat ini**.
2. Masukkan `following.json` ke bagian **Following saat ini**.
3. Jika ingin mengetahui siapa yang unfollow atau followers baru, masukkan data followers dari ekspor sebelumnya ke bagian **Followers sebelumnya**.
4. Klik tombol **Analisis Data**.

Tunggu hingga proses analisis selesai.

### 5. View Analysis Results

Hasil analisis akan ditampilkan dalam beberapa kategori:

| Menu | Fungsi |
|---|---|
| Not Following Back | Akun yang tidak follow back |
| Unfollow | Akun yang sebelumnya mengikuti tetapi sekarang tidak lagi |
| New Followers | Akun yang baru mengikuti |
| Mutual | Akun yang saling mengikuti |
| Semua Followers | Seluruh daftar followers |
| Semua Following | Seluruh daftar following |

### 6. Export Results

Jika ingin menyimpan hasil analisis:

1. Pilih kategori yang ingin diunduh.
2. Klik **Export daftar ini (CSV)** untuk mengunduh kategori aktif.
3. Atau klik **Export semua hasil (CSV)** untuk mengunduh seluruh hasil analisis.

## ⚠️ Important Notes

- Gunakan file JSON, bukan HTML atau CSV.
- Pastikan semua file followers sudah dimasukkan agar hasil akurat.
- Untuk mendeteksi unfollow dan followers baru, diperlukan dua data followers dari waktu yang berbeda.
- Data lama dan terbaru harus berasal dari akun Instagram yang sama.
- Tools ini hanya membaca data yang tersedia dalam file ekspor. Tools tidak dapat mengetahui unfollow yang terjadi sebelum data pembanding tersedia.

## 🔒 Privacy & Security

- 100% client-side processing.
- No Instagram login required.
- No API required.
- No external server.
- No data collection.
- No data upload.

Seluruh file JSON diproses langsung di browser pengguna.

## 🛠️ Technology

- HTML
- CSS
- JavaScript
- JSON

## 📄 License

Free to use for personal purposes. Please give credit when redistributing or modifying this project.

---

**IG Follower Analyzer**  
Made with ❤️ for Instagram users.
