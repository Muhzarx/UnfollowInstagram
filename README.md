# 📊 IG Follower Analyzer

<p align="center">
  <b>Instagram Followers & Following Analyzer</b><br>
  Analyze your Instagram followers without logging in.
</p>

<p align="center">
  <a href="https://muhzarx.github.io/UnfollowInstagram/">
    🚀 OPEN LIVE DEMO
  </a>
  &nbsp; | &nbsp;
  <a href="https://github.com/Muhzarx/UnfollowInstagram">
    📂 VIEW SOURCE CODE
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Web-blue">
  <img src="https://img.shields.io/badge/Mode-100%25%20Offline-success">
  <img src="https://img.shields.io/badge/Language-JavaScript-yellow">
  <img src="https://img.shields.io/badge/License-MIT-purple">
</p>

---

## 📖 About

**IG Follower Analyzer** adalah tools berbasis web untuk menganalisis hubungan followers dan following Instagram menggunakan file JSON hasil ekspor data Instagram.

Tools ini memungkinkan pengguna mengetahui siapa yang tidak follow back, siapa yang unfollow, followers baru, dan akun yang saling mengikuti.

Tidak memerlukan login Instagram, password, API, maupun aplikasi tambahan.

Seluruh proses analisis dilakukan langsung di browser pengguna.

## ✨ Features

| Feature | Description |
|---|---|
| 🔴 Unfollow Tracker | Mendeteksi akun yang berhenti mengikuti |
| 👤 Not Following Back | Menampilkan akun yang tidak follow back |
| 🟢 New Followers | Mendeteksi followers baru |
| 🤝 Mutual Followers | Menampilkan akun yang saling mengikuti |
| 🔍 Search Username | Mencari username dengan cepat |
| 📥 Export CSV | Mengunduh hasil analisis |
| 🌙 Dark Mode | Tampilan dark modern |
| 🔒 Offline Processing | Data diproses langsung di browser |

## 🚀 How to Use

### Step 1 — Download Instagram Data

Sebelum menggunakan tools, kamu perlu mengunduh data Instagram terlebih dahulu.

1. Buka aplikasi Instagram.
2. Masuk ke **Settings and activity**.
3. Pilih **Accounts Center**.
4. Masuk ke **Your information and permissions**.
5. Pilih **Download your information**.
6. Pilih akun Instagram yang ingin dianalisis.
7. Pilih informasi **Followers and following**.
8. Atur format file menjadi **JSON**.
9. Buat permintaan unduhan dan tunggu sampai file tersedia.

### Step 2 — Extract ZIP File

Setelah berhasil mengunduh data Instagram:

1. Extract file ZIP.
2. Buka folder `connections/followers_and_following` atau folder `followers_and_following`, tergantung struktur ekspor.
3. Cari file JSON berikut.

**Followers files:**

```text
followers_1.json
followers_2.json
followers_3.json
...
```

**Following file:**

```text
following.json
```

Important: Jika Instagram membagi data followers menjadi beberapa file, pastikan semua file followers_*.json digunakan agar hasil analisis akurat.

Step 3 — Open the Website

Buka IG Follower Analyzer melalui link berikut:

🚀 OPEN IG FOLLOWER ANALYZER

Kamu juga dapat mengunduh file HTML dari repository dan membukanya langsung menggunakan Google Chrome, Microsoft Edge, atau browser lainnya.

Step 4 — Upload JSON Files

Pada halaman utama tools, terdapat tiga bagian:

1. Followers Saat Ini

Masukkan semua file followers terbaru:

followers_1.json

followers_2.json

File followers lainnya jika tersedia.

2. Following Saat Ini

Masukkan file:

following.json

3. Followers Sebelumnya (Optional)

Masukkan file followers dari hasil ekspor Instagram yang lebih lama.

Bagian ini digunakan untuk mengetahui siapa yang unfollow dan siapa yang baru mengikuti akun kamu.

Setelah semua file dimasukkan, klik tombol Analisis Data.

Step 5 — View Analysis Results

Setelah proses analisis selesai, hasil akan ditampilkan berdasarkan kategori.

Category

Function

Not Following Back

Akun yang kamu ikuti tetapi tidak mengikuti balik

Unfollow

Akun yang sebelumnya mengikuti kamu tetapi sekarang tidak lagi

Followers Baru

Akun yang baru mengikuti kamu

Mutual

Akun yang saling mengikuti

Semua Followers

Menampilkan seluruh followers

Semua Following

Menampilkan seluruh following

Gunakan fitur pencarian untuk menemukan username tertentu.

Step 6 — Export Results

Kamu dapat menyimpan hasil analisis dalam format CSV.

Tersedia dua pilihan:

Export daftar ini (CSV): Mengunduh daftar dari kategori yang sedang dibuka.

Export semua hasil (CSV): Mengunduh seluruh kategori analisis.

File CSV dapat dibuka menggunakan Microsoft Excel, Google Sheets, atau aplikasi spreadsheet lainnya.

⚠️ Important Notes

Gunakan file JSON asli dari Instagram.

Pastikan semua file followers sudah dimasukkan.

Gunakan file following.json untuk membaca daftar akun yang kamu ikuti.

Untuk mendeteksi unfollow, diperlukan data followers lama dan terbaru.

Untuk mendeteksi followers baru, diperlukan perbandingan dua data followers.

Hasil analisis bergantung pada kelengkapan dan waktu pengambilan data ekspor.

Catatan: Tools tidak dapat mengetahui riwayat unfollow sebelum data pembanding tersedia.

🔒 Privacy & Security

IG Follower Analyzer dirancang dengan mengutamakan privasi pengguna.

No Instagram login required.

No password required.

No API required.

No external database.

No data upload.

No server-side processing.

Semua file JSON dibaca dan diproses langsung di browser pengguna. File tidak dikirim ke server.

🛠️ Built With

HTML5

CSS3

JavaScript

JSON

🌐 GitHub Pages

Proyek ini dapat dijalankan melalui GitHub Pages.

Jika ingin menggunakan repository ini sendiri:

Fork repository.

Buka menu Settings.

Pilih Pages.

Pada bagian Build and deployment, pilih Deploy from a branch.

Pilih branch main.

Pilih folder / (root).

Klik Save.

Pastikan file utama bernama index.html.

📂 Project Structure

UnfollowInstagram/
│
├── index.html
├── README.md
└── LICENSE

🤝 Contributing

Contributions, suggestions, and improvements are welcome!

Jika menemukan bug atau memiliki ide fitur baru, silakan membuat Issue atau Pull Request.

📄 License

This project is open-source and intended for personal use and learning.

<p align="center">
  <b>IG Follower Analyzer</b><br>
  Made with ❤️ by <a href="https://github.com/Muhzarx">Muhzarx</a>
</p>
