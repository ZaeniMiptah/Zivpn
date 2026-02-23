# 🚀 UDP ZIVPN Manager

Script manajemen server UDP untuk aplikasi **ZIVPN** — install, kelola user, dan maintain VPS dengan mudah lewat terminal.

---

## ✅ Tested On
- Ubuntu 20.04
- Ubuntu 22.04
- Ubuntu 24.04

## ⚡ Install & Jalankan

```bash
wget -O zivpn-manager.sh https://raw.githubusercontent.com/ZaeniMiptah/Zivpn/main/zivpn-manager.sh && chmod +x zivpn-manager.sh && bash zivpn-manager.sh
```

> ⚠️ Harus dijalankan sebagai **root**

---

## 📋 Fitur

| No | Fitur |
|----|-------|
| 1 | Tambah User (expired: 7/14/30/60/90 hari / custom / unlimited) |
| 2 | Hapus User |
| 3 | Daftar User + Status |
| 4 | Perpanjang User |
| 5 | Hapus User Expired |
| 6 | Status Service |
| 7 | Restart Service |
| 8 | Update Script |
| 9 | Uninstall |

---

## 📱 Cara Connect di ZIVPN App

1. Buka app **ZIVPN** → pilih **UDP**
2. Masukkan **IP VPS** kamu
3. Port: bebas (misal `5667` atau `1-65535`)
4. Password: sesuai user yang dibuat di script

---

## ⚙️ Setting Cloudflare (jika pakai domain)

- SSL/TLS → **Full**
- SSL/TLS Recommender → **OFF**
- DNS A Record → arahkan ke IP VPS

---

## 📦 Kredit

- Binary ZIVPN UDP oleh [zahidbd2](https://github.com/zahidbd2/udp-zivpn)
- Script manager by **ZaeniMiptah**
