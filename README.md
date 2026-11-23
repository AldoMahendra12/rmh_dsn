# 🏛️ Rumah Disain — Official Website

> **"Merangkai Ruang Penuh Cerita"**  
> Website resmi & portofolio studio arsitektur dan desain interior Rumah Disain.

[![Astro](https://img.shields.io/badge/Astro-v6-BC52EE?style=flat-square&logo=astro&logoColor=white)](https://astro.build/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![GSAP](https://img.shields.io/badge/GSAP-Animation-88CE02?style=flat-square&logo=greensock&logoColor=white)](https://greensock.com/gsap/)

---

## 📖 Tentang Rumah Disain

**Rumah Disain** adalah studio arsitektur dan desain interior independen yang dipimpin langsung oleh **Dimas Arief Hidayat**. Kami percaya bahwa arsitektur terbaik tidak hanya lahir dari keahlian teknis semata, melainkan dari kolaborasi yang erat dan hubungan yang transparan dengan pemilik rumah.

Melalui pendekatan desain pasif, efisiensi energi, dan estetika yang selaras dengan iklim tropis, setiap ruang dirancang untuk merefleksikan karakter dan kebutuhan penghuninya secara utuh.

---

## ✨ Fitur & Halaman Utama

1. **Beranda (`/`)**
   - Hero header dinamis dengan interaksi hover logo ekspansif.
   - Sorotan karya arsitektur pilihan.
   - Ringkasan 6 tahapan kerja studio dan filosofi desain.

2. **Karya (`/karya`)**
   - Katalog portofolio proyek hunian dan komersial dengan tata letak visual modern.

3. **Studio (`/studio`)**
   - Profil studio arsitektur dan visi pendiri (Dimas Arief Hidayat).
   - Penjelasan filosofi desain pasif dan etos kerja studio.

4. **Proses (`/proses`)**
   - Panduan transparan mengenai alur kerja 6 tahap dari konsep hingga serah terima:
     - **(01) Sketch Design** — Konsep dasar & alur spasial awal.
     - **(02) Design Development** — Pengembangan model digital 3D detail.
     - **(03) Development Application** — Pengurusan izin pembangunan (IMB/PBG).
     - **(04) Interior Design** — Tata ruang dalam, material, dan pencahayaan.
     - **(05) Building Approval Plans** — Gambar kerja & integrasi teknis MEP.
     - **(06) Construction Plans** — Dokumen konstruksi presisi untuk lapangan.

5. **Interaksi & Navigasi**
   - *Sliding menu header* & *Fullscreen navigation overlay*.
   - *Interactive drawer* multi-langkah ("Ngobrol Yuk") untuk konsultasi proyek.
   - Animasi *card-stacking* dan transisi halus bertenaga **GSAP ScrollTrigger**.

---

## 🛠️ Tech Stack

- **Framework:** [Astro](https://astro.build/) (v6)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (v4)
- **Animasi:** [GSAP](https://greensock.com/gsap/) & [ScrollTrigger](https://greensock.com/scrolltrigger/)
- **Typography:** [Montserrat Variable](https://fontsource.org/fonts/montserrat) via `@fontsource-variable/montserrat`

---

## 📁 Struktur Direktori

```text
rmh_dsn/
├── public/              # Aset statis (gambar proyek, foto tim, logo, ikon)
├── src/
│   ├── pages/           # Routing halaman Astro
│   │   ├── index.astro  # Halaman Beranda
│   │   ├── karya.astro  # Portofolio Karya
│   │   ├── proses.astro # Penjelasan 6 Tahap Proses
│   │   └── studio.astro # Profil Studio & Tim
│   └── styles/
│       └── global.css   # Konfigurasi Tailwind CSS v4 & font global
├── astro.config.mjs     # Konfigurasi Astro
├── package.json         # Dependensi & script proyek
└── README.md            # Dokumentasi proyek
```

---

## 🚀 Panduan Memulai (Development)

### Prasyarat
- [Node.js](https://nodejs.org/) versi `22.12.0` atau yang lebih baru.
- npm / yarn / pnpm.

### Instalasi & Menjalankan

1. **Clone repositori:**
   ```bash
   git clone https://github.com/AldoMahendra12/rmh_dsn.git
   cd rmh_dsn
   ```

2. **Pasang dependensi:**
   ```bash
   npm install
   ```

3. **Jalankan server pengembangan lokal:**
   ```bash
   npm run dev
   ```
   Buka peramban Anda di [http://localhost:4321](http://localhost:4321).

4. **Build untuk produksi:**
   ```bash
   npm run build
   ```
   Hasil build siap disebarkan pada folder `dist/`.

---

## 👤 Kredit & Kepemilikan

- **Studio:** Rumah Disain
- **Lead Architect & Owner:** Dimas Arief Hidayat
- **Repository Maintainer:** [Aldo Mahendra](https://github.com/AldoMahendra12)
