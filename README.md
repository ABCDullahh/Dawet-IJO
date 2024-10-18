---

# **Dawet-IJO 🍵 - Auto Commit Scheduler**

![GitHub Actions](https://img.shields.io/github/actions/workflow/status/ABCDullahh/Dawet-IJO/commit-scheduler.yml?branch=main&label=Auto%20Commit%20Status&style=for-the-badge)

**Dawet-IJO** adalah repository otomatis yang menggunakan **GitHub Actions** untuk membuat commit harian secara otomatis. Setiap hari, workflow ini akan memodifikasi file, membuat commit, dan push ke repository tanpa intervensi manual.

## 🚀 Fitur Utama
- **Commit otomatis setiap hari** dengan **GitHub Actions**.
- **Push otomatis** menggunakan **Personal Access Token (PAT)**.
- **Cron job** untuk penjadwalan tepat waktu.

## 📅 Jadwal Workflow
Saat ini berjalan setiap hari pada **10:40 UTC**. Anda bisa menyesuaikan jadwal menggunakan cron syntax.

```yaml
- cron: '40 10 * * *'  # Setiap hari pukul 10:40 UTC
```

## ⚙️ Cara Kerja
1. **Modifikasi file `random_file.txt`** dengan timestamp.
2. **Commit dan push** ke branch utama (`main`).

## 📋 Konfigurasi
1. Buat **Personal Access Token (PAT)** dengan izin **repo**.
2. Tambahkan token sebagai **secret** dengan nama `GH_TOKEN`.

## 📞 Kontak
- **GitHub**: [@ABCDullahh](https://github.com/ABCDullahh)  
- **Email**: faizal2jz@gmail.com

---

Beri ⭐ jika Anda suka proyek ini! 🎉
