# 🏢 Alfi HRIS — Human Resource Information System

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tech-HTML%20%2F%20CSS%20%2F%20JS-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Dependency-Zero-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge"/>
</p>

Alfi HRIS adalah aplikasi **Human Resource Information System** berbasis web yang lengkap, modern, dan siap pakai — dibangun dengan HTML, CSS, dan JavaScript murni **tanpa framework atau dependensi eksternal**.

## 🔐 Sistem Login & Multi-Role Akses

| Role | Email | Password | Akses |
|------|-------|----------|-------|
| 👑 **Super Admin** | admin@alfi.co.id | admin123 | **Penuh — semua fitur + pengaturan** |
| 🛡️ Admin HR | hr@alfi.co.id | hr1234 | Kelola karyawan, gaji, rekrutmen, laporan |
| 💼 Manager | manager@alfi.co.id | mgr123 | Dashboard, absensi, approve cuti, laporan |
| 👤 Karyawan | rizky@alfi.co.id | karyw123 | Dashboard personal, absensi, cuti diri sendiri |

## ✨ Fitur Lengkap

| Modul | Fitur |
|-------|-------|
| 🔐 **Login System** | Multi-role, session management, remember me, autofill demo |
| 🏠 **Dashboard** | Statistik realtime, grafik kehadiran, distribusi departemen |
| 👥 **Data Karyawan** | CRUD lengkap, filter, NIP otomatis, detail profil |
| 📅 **Absensi** | Absensi manual, kalender bulanan, rekap kehadiran |
| 🌴 **Cuti & Izin** | Pengajuan cuti, approval workflow, kuota per karyawan |
| 💰 **Penggajian** | Slip gaji, BPJS & PPh21, proses massal, export |
| 🎯 **Rekrutmen** | Manajemen lowongan, tracking pelamar, pipeline kanban |
| 📚 **Pelatihan** | Program training, tracking peserta |
| ⭐ **Penilaian Kinerja** | KPI, grade otomatis, top performer |
| 📢 **Pengumuman** | Buat & kelola pengumuman |
| 📊 **Laporan** | Export CSV, ringkasan eksekutif |
| ⚙️ **Pengaturan** | Hanya Super Admin |

## 📁 Struktur File
```
alfi-hris/
├── index.html        # Landing page & login
├── alfi-hris.html    # Dashboard utama HRIS
└── README.md
```

## 🚀 Cara Menjalankan
```bash
git clone https://github.com/username/alfi-hris.git
cd alfi-hris
# Buka index.html di browser — atau gunakan live server
python -m http.server 8080
# Buka: http://localhost:8080
```

> ⚡ **Penting:** Jalankan dengan server (bukan double-click file) agar redirect antar halaman bekerja dengan benar.

## 🌐 Deploy ke GitHub Pages
1. Push ke GitHub
2. Settings → Pages → Source: `main`
3. Akses: `https://username.github.io/alfi-hris/`

---
Made with ❤️ by Alfi Team
