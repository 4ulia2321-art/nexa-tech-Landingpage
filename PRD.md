# 📋 PRODUCT REQUIREMENTS DOCUMENT (PRD)
## SPMB SMK Budi Bakti Ciwidey — Website Pendaftaran Peserta Didik Baru
**Versi**: 1.0 | **Tanggal**: Mei 2026 | **Status**: ✅ Final Draft  
**Pemilik Produk**: SMK Budi Bakti Ciwidey | **Tim Pengembang**: Nexa Tech  

---

## 🎯 1. EXECUTIVE SUMMARY
### 1.1 Latar Belakang
SMK Budi Bakti Ciwidey membutuhkan platform digital terpusat untuk:
- Meningkatkan visibilitas sekolah di kalangan calon siswa & orang tua
- Mempermudah akses informasi program keahlian & prosedur pendaftaran
- Mengotomatisasi pengumpulan data pendaftar secara digital
- Memperkuat branding sekolah sebagai SMK berbasis industri

### 1.2 Tujuan Produk
| Tujuan | Indikator Keberhasilan |
|--------|----------------------|
| 📈 Meningkatkan konversi pendaftaran | ≥ 15% visitor → submit form |
| ⚡ Mempercepat proses registrasi | Form selesai dalam ≤ 3 menit |
|  Memberikan pengalaman mobile-first | ≥ 70% traffic dari mobile, bounce rate < 40% |
| 🔐 Mengamankan data pendaftar | 100% data terenkripsi, compliant UU PDP |

### 1.3 Scope Produk

---

## 👥 2. USER PERSONAS & USER STORIES
### 2.1 Persona Utama
| Persona | Profil | Kebutuhan Utama | Pain Points |
|---------|--------|----------------|-------------|
| 🎓 Calon Siswa (15-17 th) | Lulusan SMP, melek digital | Info program, fasilitas, cara daftar | Website lama sulit diakses di HP, info tidak jelas |
| 👨👩‍👧 Orang Tua/Wali | Usia 35-50 th, peduli masa depan anak | Kredibilitas sekolah, prospek karir lulusan | Biaya tersembunyi, sulit bandingkan program |
| 🏢 Admin PPDB | Guru/Staf pengelola pendaftaran | Kemudahan kelola data pendaftar | Formulir kertas hilang, rekap manual rawan error |

### 2.2 User Stories (Prioritas)
| ID | Sebagai... | Saya ingin... | Agar... | Prioritas |
|----|-----------|--------------|---------|-----------|
| US-01 | Calon siswa | Melihat daftar program keahlian dengan contoh karya | Saya bisa pilih jurusan yang sesuai minat |  High |
| US-02 | Calon siswa | Mendaftar hanya dengan 5 field utama | Proses cepat, tidak membosankan | 🔴 High |
| US-03 | Orang tua | Melihat testimoni alumni & mitra industri | Saya yakin dengan kualitas sekolah | 🔴 High |
| US-04 | Admin PPDB | Menerima notifikasi email saat ada pendaftar baru | Saya bisa segera verifikasi data |  Medium |
| US-05 | Admin PPDB | Export data pendaftar ke CSV | Saya bisa olah data untuk laporan | 🟢 Low |

---

## ✨ 3. FITUR & SPESIFIKASI TEKNIS
### 3.1 Fitur Utama (MVP)
| ID | Fitur | Deskripsi | Kriteria Penerimaan |
|----|-------|-----------|---------------------|
| F01 | Hero + CTA | Banner menarik + tombol "Daftar Sekarang" | Load < 2s, tombol min. 44x44px, smooth scroll |
| F02 | Program Keahlian | 3 Kartu (DKV, RPL, Bisnis) + detail kompetensi | Responsif 1/3 kolom, hover effect, link aktif |
| F03 | Keunggulan Sekolah | 4-6 poin ikon + teks singkat | SVG ikon, max 15 kata/poin, fade-in scroll |
| F04 | Statistik Sekolah | Counter animasi (siswa, guru, mitra, kelulusan) | Intersection Observer, format "500+", tidak lag |
| F05 | Formulir Pendaftaran | 5 field wajib + validasi real-time | Mobile-friendly, pesan error jelas, sukses message |
| F06 | Video Profil | Embed YouTube/Vimeo + lazy load | Modal lightbox, close via ESC/klik luar, alt text |
| F07 | Responsif & Aksesibilitas | Mobile-first, kontras ≥4.5:1, keyboard nav | Lighthouse ≥90, no horizontal scroll, screen reader ready |

### 3.2 Matriks Prioritas (MoSCoW)
| Fitur | Must | Should | Could | Won't (v1) |
|-------|------|--------|-------|------------|
| Hero + CTA | ✅ | | | |
| Kartu Program | ✅ | | | |
| Formulir Pendaftaran | ✅ | | | |
| Responsif Mobile | ✅ | | | |
| Video Profil | | ✅ | | |
| Admin Dashboard | | | | ✅ |

---

## 🎨 4. DESIGN SYSTEM & UX
- **Warna**: Primary `#2563EB`, Accent `#F97316`, Text `#0F172A`, BG `#F8FAFC`
- **Font**: Poppins (Heading), Inter (Body) via Google Fonts
- **Spacing**: 8px scale (4, 8, 16, 24, 32, 48)
- **Komponen**: Tombol primary/secondary, kartu shadow-md, input ring-focus, notifikasi success/error

---

## 📊 5. METRIK & ANALYTICS (KPI)
| Kategori | Metrik | Target | Tool |
|----------|--------|--------|------|
| 📈 Konversi | Form Submission Rate | ≥ 15% | GA4 + Netlify Forms |
| ⚡ Performa | First Contentful Paint | < 1.8s | Lighthouse |
| 📱 Engagement | Bounce Rate (mobile) | < 40% | GA4 |
| ✅ Kualitas | Form Completion Rate | ≥ 80% | Custom event tracking |

---

## 🔐 6. KEAMANAN & PRIVASI
- ✅ HTTPS wajib (TLS 1.2+)
- ✅ Data form dienkripsi transit & at rest (Netlify default)
- ✅ Minimal data collection (MVP)
- ✅ Pernyataan privasi di form: "Data hanya untuk proses PPDB"
- ✅ Compliance: UU PDP No. 27/2022

---

## 🗓️ 7. TIMELINE & MILESTONE

---

## ⚠️ 8. RISIKO & MITIGASI
| Risiko | Dampak | Mitigasi |
|--------|--------|----------|
| Load lambat di 3G | Bounce rate tinggi | Optimasi WebP, lazy load, minify |
| Form sulit di mobile | User abandon | Touch target ≥44px, autofill, testing device nyata |
| Data bocor | Reputasi rusak | HTTPS, tidak simpan data sensitif, akses admin terbatas |
| Konten kadaluarsa | Kebingungan user | PIC konten, review bulanan |

---



---
> 📎 **Dokumen ini hidup** — revisi via GitHub Issues.  
> 🔄 **Versi selanjutnya**: v1.1 (Admin Dashboard + Notifikasi WA).
