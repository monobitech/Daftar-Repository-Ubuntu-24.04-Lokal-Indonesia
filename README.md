# Daftar Repository Ubuntu 24.04 LTS Lokal Indonesia (Noble Numbat)

Repository ini berisi **daftar lengkap mirror repository lokal Indonesia** untuk **Ubuntu 24.04 LTS (Noble Numbat)**.  
Dapat digunakan sebagai **pengganti repository default Ubuntu** agar proses update dan instalasi paket menjadi **lebih cepat dan stabil**, khususnya untuk pengguna di Indonesia.

Repository ini cocok digunakan oleh:
- Sysadmin
- DevOps
- Pengguna Ubuntu Desktop
- Pengguna Ubuntu Server
- Pelajar & praktisi Linux

---

## 🎯 Tujuan
- Mengumpulkan mirror **Ubuntu 24.04 LTS lokal Indonesia** dalam satu tempat
- Memudahkan pengguna memilih repository tercepat
- Menyediakan contoh konfigurasi **APT format terbaru (`ubuntu.sources`)**
- Dokumentasi ringan & siap pakai

---

## 🚀 Fitur
- ✅ Mirror **lokal Indonesia**
- ✅ Format **APT modern (`ubuntu.sources`)**
- ✅ Cocok untuk **Desktop & Server**
- ✅ Siap copy–paste
- ✅ Dokumentasi jelas & ringkas
- ✅ Open & gratis untuk komunitas

---

## 📌 Format Repository Ubuntu 24.04

Sejak Ubuntu 24.04, APT menggunakan format file **`ubuntu.sources`**.

Contoh format dasar:
```text
Types: deb
URIs: URL_REPOSITORY
Suites: noble noble-updates noble-security noble-backports
Components: main universe restricted multiverse
Signed-By: /usr/share/keyrings/ubuntu-archive-keyring.gpg
