# GateTech

GateTech adalah proyek *landing page* dan *prototype* sistem manajemen tamu lobi serta integrasi parkir gedung berbasis web. Proyek ini dirancang dan dikembangkan secara mandiri (*solo project*) untuk mendemonstrasikan solusi operasional properti komersial modern.

## Latar Belakang & Tujuan

Proyek ini dibuat untuk menjawab tantangan efisiensi di lobi gedung perkantoran:
- Menggantikan pencatatan buku tamu manual dan penahanan KTP fisik dengan QR Code dinamis yang aman.
- Menyediakan alur konfirmasi janji temu (*appointment*) yang terintegrasi langsung dengan pengalaman tamu.
- Menghubungkan sistem akses lobi (*turnstile*) dengan otomatisasi palang parkir (*boomgate*) berbasis *License Plate Recognition* (LPR).

## Fitur Utama

- **Visitor Management System (VMS):** Alur pra-registrasi tamu digital untuk memotong waktu antrean di lobi.
- **Simulasi Live QR Code:** Fitur interaktif berbasis Alpine.js untuk mensimulasikan pembuatan token akses secara *real-time*.
- **Integrasi Parkir LPR:** Penjelasan arsitektur sinkronisasi plat nomor kendaraan dengan gerbang masuk gedung.
- **Portal & Form Interaktif:** Dilengkapi halaman profil perusahaan, pusat kontak, serta halaman pemesanan demo (*Book a Demo*).

## Tech Stack

Proyek ini dibangun menggunakan pendekatan *modern static frontend* tanpa ketergantungan *backend* yang rumit:
- **Markup:** HTML5
- **Styling:** Tailwind CSS (via CDN)
- **Tipografi:** Syne (Headings) & Manrope (Body) via Google Fonts
- **Interaksi UI:** Alpine.js
- **Arsitektur:** Modular Multi-Page Static Site

## Live Demo & Akses

Anda dapat melihat hasil *deployment* proyek ini secara langsung melalui tautan berikut:
👉 [https://billyanz.github.io/gatetech-landing/](https://billyanz.github.io/gatetech-landing/)

## Struktur Direktori

```text
/gatetech-landing
│
├── index.html          # Beranda utama (Sales Funnel & Storytelling)
├── fitur-tamu.html     # Modul Manajemen Tamu + Live QR Simulation
├── fitur-parkir.html   # Modul Integrasi Parkir + CLI Terminal LPR
├── tentang.html        # Latar belakang dan visi pengembangan
├── kontak.html         # Informasi kontak pengembang
├── jadwal-demo.html   # Form interaktif pemesanan demo sistem
├── login-dummy.html    # Mockup antarmuka Portal Tenant / Admin
│
└── js/
    └── config.js       # Konfigurasi terpusat Tailwind (Theme & Colors)
Menjalankan Secara Lokal
Clone repositori ini:

Bash
git clone [https://github.com/billyanz/gatetech-landing.git](https://github.com/billyanz/gatetech-landing.git)
Buka folder menggunakan teks editor (misal: VS Code).

Jalankan menggunakan ekstensi Live Server atau buka file index.html di browser.

Dibuat dan dikembangkan oleh Billianz Yusuf Hema Sasmi Tarja.