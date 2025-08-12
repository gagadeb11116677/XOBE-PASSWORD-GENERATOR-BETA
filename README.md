# 🔐 XOBE Password Generator — v0.1

[![Version](https://img.shields.io/badge/version-0.1-blue)](https://github.com/gagadeb11116677/XOBE-PASSWORD-GENERATOR-BETA)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Open Source](https://img.shields.io/badge/open--source-yes-green.svg)](https://github.com/gagadeb11116677/XOBE-PASSWORD-GENERATOR-BETA)

**Open‑source password generator** yang ringan dan mudah digunakan — dibuat untuk menghasilkan password kuat serta menyimpannya secara praktis.

---

## 📌 Ringkasan singkat

* **Versi:** `0.1`
* **Lisensi:** MIT (open source)
* **Fokus:** Generate password kuat, simpan lokal, dan cek kekuatan secara real-time.

---

## 🧭 Daftar Isi

1. [Deskripsi](#deskripsi)
2. [Fitur Utama](#fitur-utama)
3. [Quick Start](#quick-start)
4. [Contoh Penggunaan](#contoh-penggunaan)
5. [Konfigurasi & Kustomisasi](#konfigurasi--kustomisasi)
6. [Keamanan & Catatan Penting](#keamanan--catatan-penting)
7. [Changelog](#changelog--v01)
8. [Kontribusi](#kontribusi)
9. [Lisensi](#lisensi)
10. [Kontak](#kontak)

---

## 📖 Deskripsi

XOBE Password Generator membantu kamu membuat password yang **sulit ditebak** dan **mudah dikelola**. Semua proses berjalan secara lokal — data tidak dikirim ke server manapun.

Dirancang agar mudah dipakai oleh pengguna umum dan developer yang ingin mengintegrasikan generator ini ke workflow mereka.

---

## ✨ Fitur Utama

* 🔑 Generate password acak dengan panjang yang dapat disesuaikan
* 🔡 Kombinasi huruf besar, huruf kecil, angka, dan simbol
* 💾 **5 slot penyimpanan** untuk menyimpan password hasil generate
* 🛡 **Pengecekan kekuatan password secara real-time** (entropy & estimasi crack-time)
* 🚀 Cepat, ringan, dan berjalan sepenuhnya lokal
* 📂 Open source (MIT) — mudah dimodifikasi oleh siapa saja

---

## 🚀 Quick Start

Ikuti langkah singkat ini untuk mulai pakai:

1. Clone repository:

```bash
git clone https://github.com/gagadeb11116677/XOBE-PASSWORD-GENERATOR-BETA.git
cd XOBE-PASSWORD-GENERATOR-BETA
```

2. (Opsional) Install dependensi jika ada:

```bash
npm install
# atau
pip install -r requirements.txt
```

3. Jalankan program (contoh):

```bash
node index.js
# atau
python generate.py
```

---

## 🧾 Contoh Penggunaan

* Generate password baru lewat UI/CLI.
* Simpan ke salah satu dari 5 slot.
* Lihat indikator strength secara real-time untuk mengetahui seberapa aman password tersebut.

**Contoh output CLI:**

```text
Generated password: gH7#kLm!2zQ
Strength: STRONG (entropy: 58 bits, est. crack time: 10^14 years)
Saved to slot: 3
```

---

## ⚙️ Konfigurasi & Kustomisasi

* Semua warna & tema mudah diatur lewat satu variabel CSS (jika ada UI).
* Ubah charset (karakter yang digunakan) pada file konfigurasi untuk menyesuaikan kebutuhan (mis. menghilangkan simbol jika diperlukan).
* Slot penyimpanan saat ini default 5 — dapat diubah pada source jika ingin di-expand.

---

## 🔒 Keamanan & Catatan Penting

* Aplikasi berjalan secara lokal; tetap jaga file penyimpanan password (backup terenkripsi direkomendasikan).
* Hindari menyimpan password sensitif di mesin publik.
* Versi ini **belum** memiliki enkripsi storage otomatis — rencana enkripsi (mis. AES-GCM) dapat ditambahkan di rilis berikutnya.

---
# 📜 Changelog  v0.2

## ✨ Fitur Baru
- Menambahkan **10 slot penyimpanan password** untuk memudahkan pengelolaan lebih banyak akun.
- Menambahkan fitur **popup tampilan password** saat ingin melihat password yang tersimpan.
- Penambahan **tombol hapus slot** untuk menghapus password yang tidak diperlukan.
- UI diperbarui menjadi **lebih modern, rapi, dan responsif**.

## 🛠 Perbaikan
- Perbaikan bug pada proses generate password.
- Optimalisasi kinerja saat memuat data password.
- Penyimpanan slot kini lebih stabil dan cepat diakses.

## 🔄 Pembaruan Lain
- Ikon tombol diperbarui agar lebih mudah dipahami.
- Penataan ulang tata letak agar lebih intuitif.
- Animasi transisi pada popup untuk pengalaman yang lebih halus.


## 🤝 Kontribusi

Kontribusi sangat dihargai:

* Laporkan bug dan fitur lewat **Issues** di GitHub
* Kirim **Pull Request** untuk perbaikan / penambahan fitur
* Sertakan deskripsi perubahan dan langkah uji coba pada setiap PR

---

## 📝 Lisensi

MIT License — lihat file `LICENSE` untuk detail. Kamu bebas menggunakan, memodifikasi, dan mendistribusikan ulang dengan menyertakan atribusi.

---

## ✉️ Kontak

**XOBE DEVELOPMENT**

* Repo: [https://github.com/gagadeb11116677/XOBE-PASSWORD-GENERATOR-BETA](https://github.com/gagadeb11116677/XOBE-PASSWORD-GENERATOR-BETA)

---

*Dibuat dengan ❤️ oleh XOBE DEVELOPMENT*
