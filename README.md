# 🛡️ TSE v2.2 Scanner

TSE (Tools SQLi Exploiter) adalah alat otomatis untuk mendeteksi dan mengeksploitasi berbagai jenis kerentanan keamanan web seperti SQL Injection, XSS, LFI, RFI, SSRF, dan lainnya. Dirancang untuk keperluan edukasi dan pengujian penetrasi dengan izin.

> ⚠️ PERINGATAN: Hanya gunakan tools ini pada sistem milik Anda sendiri atau sistem yang Anda miliki izin eksplisit untuk menguji. Penyalahgunaan dapat melanggar hukum.

---

## ✨ Fitur

- Deteksi SQLi: `UNION`, `BOOLEAN`, `TIME`
- Deteksi dan eksploitasi: `XSS`, `LFI`, `RFI`, `SSRF`
- Obfuscasi payload dengan `TAMPER` dan `TAMPER_SUFFIX`
- Crawl halaman dan otomatis scan semua URL
- Mendukung proxy dan bypass SSL
- Mode verbose
- Laporan hasil dalam format log

---

## 🛠️ Instalasi

### 🔹 Persyaratan

- Python 3.7 atau lebih baru
- OS: Linux (Termux/Ubuntu), Windows
- Tools tambahan: `pip`, `git`

### 🔸 Instalasi di Termux/Linux

```bash
pkg install python git -y
git clone https://github.com/username/tse-scanner.git
cd tse-scanner
pip install -r requirements.txt
