GateTech | Enterprise Visitor Management & Smart Parking System

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=flat-square&logo=alpinedotjs&logoColor=white)](https://alpinejs.dev/)
[![Status](https://img.shields.io/badge/Status-Production%20Ready-emerald?style=flat-square)]()

**GateTech** adalah platform Software-as-a-Service (SaaS) skala *enterprise* yang dirancang untuk mengotomatisasi operasional properti komersial modern. Sistem ini mengintegrasikan manajemen tamu lobi (Visitor Management System) dengan sistem pengenalan pelat nomor kendaraan (License Plate Recognition / LPR) untuk akses parkir VIP secara *seamless*.

---

## 🚀 Fitur Utama

1. **Visitor Management System (QR Code Dinamis)**
   - Pre-registrasi tamu secara online via undangan digital.
   - Pembuatan QR Code dinamis berbasis kriptografi untuk akses *Turnstile* (Flap Barrier) lobi tanpa KTP fisik.
   - Simulasi *live* pembuatan token akses *real-time*.

2. **Smart Parking Integration (LPR System)**
   - Sinkronisasi data plat nomor tamu dengan kamera pengawas gerbang masuk (*Boomgate*).
   - Alokasi otomatis slot parkir khusus tamu VIP/direksi.

3. **Enterprise Dashboard & Tenant Portal**
   - Pusat kendali bagi manajemen gedung dan tim sekuriti untuk memantau log aktivitas.
   - Manajemen data tenant dan rekapitulasi data kunjungan harian.

---

## 🛠️ Tech Stack

- **Markup & Styling:** HTML5 Semantic, Tailwind CSS (via CDN)
- **Typography:** Syne (Headings) & Manrope (Body) via Google Fonts
- **Interactions:** Alpine.js (untuk state UI dinamis dan simulasi QR Code)
- **Architecture:** Modular Multi-Page Static Site (Separation of Concerns)

---

## 📂 Struktur Direktori Proyek

```text
/gatetech-landing
│
├── index.html          # Beranda utama (Sales Funnel & Storytelling)
├── fitur-tamu.html     # Modul Manajemen Tamu + Live QR Simulation
├── fitur-parkir.html   # Modul Integrasi Parkir + CLI Terminal LPR
├── tentang.html        # Profil perusahaan & standar privasi data
├── kontak.html         # Informasi pusat bantuan dan peta lokasi
├── jadwal-demo.html   # Form interaktif pemesanan demo sistem (B2B)
├── login-dummy.html    # Mockup antarmuka Portal Tenant / Admin
│
└── js/
    └── config.js       # Konfigurasi terpusat Tailwind (Theme & Colors)
📦 Menjalankan Proyek Secara Lokal
Karena menggunakan pendekatan static html murni, proyek ini tidak memerlukan instalasi database atau compiler yang rumit:

Clone repository ini ke komputer lokal Anda:

Bash
git clone [https://github.com/billyanz/gatetech-landing.git](https://github.com/billyanz/gatetech-landing.git)
Buka folder proyek menggunakan Code Editor (seperti VS Code).

Jalankan menggunakan ekstensi Live Server di VS Code, atau langsung buka file index.html di peramban web modern Anda.

📄 Lisensi
Hak Cipta Dilindungi © 2026 PT GateTech Solusi Indonesia. Dikembangkan untuk kebutuhan transformasi digital properti komersial.