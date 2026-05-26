# 🎓 SPMB SMK Budi Bakti Ciwidey
> Sistem Penerimaan Peserta Didik Baru - SMK Budi Bakti Ciwidey  
> Developed by **Nexa Tech** | [Live Demo](https://nexa-tech-spmb-smkbbc.netlify.app/)

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-production-yellow.svg)

---

## 📋 Deskripsi
Website ini merupakan portal informasi dan pendaftaran peserta didik baru untuk **SMK Budi Bakti Ciwidey**, menampilkan program keahlian, fasilitas, keunggulan sekolah, serta formulir pendaftaran online.

---

## 🚀 Fitur Utama
- ✅ Landing page responsif dengan desain modern
- ✅ Informasi 3 program keahlian: DKV, RPL, Bisnis Daring
- ✅ Statistik sekolah (siswa, guru, mitra industri)
- ✅ Tombol CTA: Daftar Sekarang, Lihat Video Profil, Detail Program
- ✅ Optimasi mobile-first & SEO dasar
- ✅ Integrasi formulir pendaftaran (frontend)

---

## 🛠️ Tech Stack
| Kategori | Teknologi |
|----------|-----------|
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| Styling | Tailwind CSS / Custom CSS |
| Hosting | Netlify |
| Form Handling | Netlify Forms |
| Version Control | Git & GitHub |

---

## 📁 Struktur Proyek
📦 spmb-smkbbc/
├── 📁 assets/
│ ├── 📁 images/ # Logo, banner, ikon program
│ │ ├── BBC.jpeg
│ │ ├── bdc.jpeg
│ │ ├── dkv.jpeg
│ │ └── langbbc.jpeg
│ ├── 📁 videos/ # Video profil sekolah
│ └── 📁 icons/ # Favicon, sosial media icons
├── 📁 css/
│ └── styles.css # Custom styles
├── 📁 js/
│ └── main.js # Interaksi UI & validasi form
├── index.html # Landing page utama
├── README.md # Dokumentasi ini
├── PRD.md # Product Requirements Document
└── netlify.toml # Konfigurasi deploy Netlify

---

## ⚙️ Cara Menjalankan (Development)

### Prasyarat
- Browser modern (Chrome, Firefox, Edge)
- Text editor (VS Code recommended)
- Akun Netlify (untuk deploy)

### Langkah Instalasi
```bash
# 1. Clone repository
git clone https://github.com/4ulia2321-art/nexa-tech-Landingpage.git
cd nexa-tech-Landingpage

# 2. Buka file index.html di browser
#    Klik kanan file → Open with → Browser

# 3. Atau gunakan Live Server di VS Code
#    Install extension "Live Server"
#    Klik kanan index.html → Open with Live Server
# Opsi 1: Drag & Drop
# 1. Buka netlify.com
# 2. Login/Daftar
# 3. Drag folder proyek ke area deploy

# Opsi 2: Via GitHub
# 1. Connect GitHub di Netlify
# 2. Pilih repository ini
# 3. Klik Deploy
<form name="pendaftaran-spmb" method="POST" data-netlify="true">
  <input type="text" name="nama_lengkap" required>
  <input type="email" name="email" required>
  <select name="program_keahlian">
    <option value="dkv">DKV - Desain Komunikasi Visual</option>
    <option value="rpl">RPL - Rekayasa Perangkat Lunak</option>
    <option value="bisnis">Bisnis Daring & Pemasaran</option>
  </select>
  <button type="submit">Daftar Sekarang</button>
</form>
🎨 Program Keahlian
1. DKV - Desain Komunikasi Visual
Graphic Design
Illustration & Photography
Multimedia Production
UI/UX Design
2. RPL - Rekayasa Perangkat Lunak
Web Programming
Mobile Development
Database Management
Cloud Computing
3. Bisnis Daring & Pemasaran
Digital Marketing
E-Commerce Management
Market Analysis
Business Development
📊 Statistik Sekolah
👥 500+ Siswa Aktif
👨‍🏫 20+ Guru Profesional
🏭 10+ Mitra Industri
✅ 100% Kelulusan Siap Kerja
🧪 Testing Checklist
Responsif di mobile (320px - 768px)
Responsif di tablet (768px - 1024px)
Responsif di desktop (>1024px)
Validasi form berfungsi
Semua link & CTA bekerja
Load time < 3 detik
Gambar teroptimasi (WebP format)
📝 License
Dibawah lisensi MIT. Silakan gunakan, modifikasi, dan distribusikan dengan mencantumkan atribusi kepada Nexa Tech dan SMK Budi Bakti Ciwidey.
🤝 Kontribusi
Fork repository
Buat branch fitur: git checkout -b fitur/baru
Commit perubahan: git commit -m 'feat: tambah fitur X'
Push ke branch: git push origin fitur/baru
Buka Pull Request
📬 Kontak & Dukungan
Tim Nexa Tech: [Email/Contact]
SMK Budi Bakti Ciwidey: [Email Sekolah]
Issue Tracker: GitHub Issues
🔗 Link Penting
Live Website
Product Requirements (PRD)
GitHub Repository
© 2026 SMK Budi Bakti Ciwidey. Developed by Nexa Tech.
# 📋 README.md - Siap Copy-Paste

Salin semua konten di bawah ini dan tempel ke file README.md di GitHub kamu:

```markdown
# 🎓 SPMB SMK Budi Bakti Ciwidey
> Sistem Penerimaan Peserta Didik Baru - SMK Budi Bakti Ciwidey  
> Developed by **Nexa Tech** | [Live Demo](https://nexa-tech-spmb-smkbbc.netlify.app/)

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-production-yellow.svg)

---

## 📋 Deskripsi
Website ini merupakan portal informasi dan pendaftaran peserta didik baru untuk **SMK Budi Bakti Ciwidey**, menampilkan program keahlian, fasilitas, keunggulan sekolah, serta formulir pendaftaran online.

---

## 🚀 Fitur Utama
- ✅ Landing page responsif dengan desain modern
- ✅ Informasi 3 program keahlian: DKV, RPL, Bisnis Daring
- ✅ Statistik sekolah (siswa, guru, mitra industri)
- ✅ Tombol CTA: Daftar Sekarang, Lihat Video Profil, Detail Program
- ✅ Optimasi mobile-first & SEO dasar
- ✅ Integrasi formulir pendaftaran (frontend)

---

## 🛠️ Tech Stack
| Kategori | Teknologi |
|----------|-----------|
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| Styling | Tailwind CSS / Custom CSS |
| Hosting | Netlify |
| Form Handling | Netlify Forms |
| Version Control | Git & GitHub |

---

## 📁 Struktur Proyek
```
📦 spmb-smkbbc/
├── 📁 assets/
│   ├── 📁 images/       # Logo, banner, ikon program
│   │   ├── BBC.jpeg
│   │   ├── bdc.jpeg
│   │   ├── dkv.jpeg
│   │   └── langbbc.jpeg
│   ├── 📁 videos/       # Video profil sekolah
│   └── 📁 icons/        # Favicon, sosial media icons
├── 📁 css/
│   └── styles.css       # Custom styles
├── 📁 js/
│   └── main.js          # Interaksi UI & validasi form
├── index.html           # Landing page utama
├── README.md            # Dokumentasi ini
├── PRD.md               # Product Requirements Document
└── netlify.toml         # Konfigurasi deploy Netlify
```

---

## ⚙️ Cara Menjalankan (Development)

### Prasyarat
- Browser modern (Chrome, Firefox, Edge)
- Text editor (VS Code recommended)
- Akun Netlify (untuk deploy)

### Langkah Instalasi
```bash
# 1. Clone repository
git clone https://github.com/4ulia2321-art/nexa-tech-Landingpage.git
cd nexa-tech-Landingpage

# 2. Buka file index.html di browser
#    Klik kanan file → Open with → Browser

# 3. Atau gunakan Live Server di VS Code
#    Install extension "Live Server"
#    Klik kanan index.html → Open with Live Server
```

### Deploy ke Netlify
```bash
# Opsi 1: Drag & Drop
# 1. Buka netlify.com
# 2. Login/Daftar
# 3. Drag folder proyek ke area deploy

# Opsi 2: Via GitHub
# 1. Connect GitHub di Netlify
# 2. Pilih repository ini
# 3. Klik Deploy
```

---

## 🔧 Konfigurasi Formulir Pendaftaran

Formulir sudah terintegrasi dengan **Netlify Forms**. Pastikan atribut berikut ada:

```html
<form name="pendaftaran-spmb" method="POST" data-netlify="true">
  <input type="text" name="nama_lengkap" required>
  <input type="email" name="email" required>
  <select name="program_keahlian">
    <option value="dkv">DKV - Desain Komunikasi Visual</option>
    <option value="rpl">RPL - Rekayasa Perangkat Lunak</option>
    <option value="bisnis">Bisnis Daring & Pemasaran</option>
  </select>
  <button type="submit">Daftar Sekarang</button>
</form>
```

> 💡 Data form akan tersimpan otomatis di dashboard Netlify → Forms

---

## 🎨 Program Keahlian

### 1. **DKV - Desain Komunikasi Visual**
- Graphic Design
- Illustration & Photography
- Multimedia Production
- UI/UX Design

### 2. **RPL - Rekayasa Perangkat Lunak**
- Web Programming
- Mobile Development
- Database Management
- Cloud Computing

### 3. **Bisnis Daring & Pemasaran**
- Digital Marketing
- E-Commerce Management
- Market Analysis
- Business Development

---

## 📊 Statistik Sekolah
- 👥 **500+** Siswa Aktif
- 👨‍🏫 **20+** Guru Profesional
- 🏭 **10+** Mitra Industri
- ✅ **100%** Kelulusan Siap Kerja

---

## 🧪 Testing Checklist
- [ ] Responsif di mobile (320px - 768px)
- [ ] Responsif di tablet (768px - 1024px)
- [ ] Responsif di desktop (>1024px)
- [ ] Validasi form berfungsi
- [ ] Semua link & CTA bekerja
- [ ] Load time < 3 detik
- [ ] Gambar teroptimasi (WebP format)

---

## 📝 License
Dibawah lisensi MIT. Silakan gunakan, modifikasi, dan distribusikan dengan mencantumkan atribusi kepada **Nexa Tech** dan **SMK Budi Bakti Ciwidey**.

---

## 🤝 Kontribusi
1. Fork repository
2. Buat branch fitur: `git checkout -b fitur/baru`
3. Commit perubahan: `git commit -m 'feat: tambah fitur X'`
4. Push ke branch: `git push origin fitur/baru`
5. Buka Pull Request

---

## 📬 Kontak & Dukungan
- **Tim Nexa Tech**: [Email/Contact]
- **SMK Budi Bakti Ciwidey**: [Email Sekolah]
- **Issue Tracker**: [GitHub Issues](https://github.com/4ulia2321-art/nexa-tech-Landingpage/issues)

---

## 🔗 Link Penting
- [Live Website](https://nexa-tech-spmb-smkbbc.netlify.app/)
- [Product Requirements (PRD)](./PRD.md)
- [GitHub Repository](https://github.com/4ulia2321-art/nexa-tech-Landingpage)

---

**© 2026 SMK Budi Bakti Ciwidey. Developed by Nexa Tech.**
```

---

## ✅ Cara Paste di GitHub:

1. **Klik file `README.md`** di repository kamu
2. **Klik ikon pensil ✏️** (Edit this file)
3. **Hapus semua isi yang ada** (Ctrl+A → Delete)
4. **Paste** semua kode di atas
5. **Scroll ke bawah**
6. **Commit message**: `feat: update README dengan dokumentasi lengkap`
7. **Klik "Commit changes"**

