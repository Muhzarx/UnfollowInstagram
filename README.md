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

> **Important:** Jika Instagram
