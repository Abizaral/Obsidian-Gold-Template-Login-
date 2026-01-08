# Obsidian Gold - Hotspot Template

![Mikrotik](https://img.shields.io/badge/Platform-Mikrotik-red?style=for-the-badge&logo=mikrotik)
![Design](https://img.shields.io/badge/Style-Glassmorphism-gold?style=for-the-badge)
![License](https://img.shields.io/badge/License-Free-green?style=for-the-badge)

> **Obsidian Gold** adalah template Hotspot Mikrotik berkelas tinggi (*High-End*) yang memadukan warna hitam obsidian, aksen emas metalik, dan efek kaca (*Glassmorphism*). Dirancang khusus untuk memberikan pengalaman login yang mewah, profesional, dan eksklusif.

---

## ✨ Fitur Utama

* **💎 Obsidian & Gold Aesthetic**: Palet warna mewah (Dark Navy Black & Champagne Gold) dengan font premium (*Cinzel* & *Inter*).
* **🌫️ Real Glassmorphism**: Efek kaca buram (*frosted glass*) yang halus pada setiap kartu login dan status.
* **🎬 Smooth Animations**:
    * *Gold Pulse Logo*: Animasi detak jantung emas pada halaman login.
    * *Radar Scan Alert*: Animasi radar merah delima pada halaman error.
    * *Floating Orbs*: Latar belakang bola cahaya yang bergerak perlahan (hidup).
* **🧠 Smart Dashboard**: Halaman status otomatis menyembunyikan baris "Sisa Kuota" atau "Sisa Waktu" jika user bertipe *Unlimited*.
* **📱 Mobile-Lock Layout**: Tampilan terkunci (*Fixed Viewport*) agar tidak bergeser/zoom sembarangan di HP.
* **🔄 Dual Login System**: Tab perpindahan mode Voucher dan Member yang *fluid* dan responsif.

---

## 📂 Struktur Folder

/hotspot
├── login.html      # Halaman Login (Animasi Gold Pulse)
├── status.html     # Dashboard Smart Status (Auto-hide quota)
├── logout.html     # Halaman Logout (Ringkasan sesi)
├── error.html      # Luxury Error Alert (Animasi Radar)
├── alink.html      # Universal Redirect (Akses Diterima)
├── rlink.html      # Universal Redirect (Ke Link Tujuan)
├── alogin.html     # Universal Loader (Memproses Login)
└── md5.js          # Library Enkripsi (Wajib disertakan)

## 🚀 Cara Pasang
1. Download semua script/file template ini.
2. Pastikan file md5.js (bawaan Mikrotik atau dari repo ini) ada di dalam folder.
3. Upload seluruh file ke dalam folder baru di File List Mikrotik (misal: hotspot/obsidian).
4. Masuk ke menu IP > Hotspot > Server Profile.
5. Pilih profil hotspot yang aktif, lalu ubah HTML Directory ke folder hotspot/obsidian.
6. Opsional: Untuk hasil font terbaik, pastikan Walled Garden mengizinkan akses ke:
  fonts.googleapis.com
  fonts.gstatic.com.

## Credits
Dibuat dengan Gemini AI WOWOWK
