# Pulba Digital — Ekosistem Solusi Terpadu

> **Swiss Style Minimalist Digital Ecosystem** dibangun dengan [Astro 7](https://astro.build), [Tailwind CSS v4](https://tailwindcss.com), dan [Bun JS](https://bun.sh).

Landing page resmi dan hub katalog platform untuk seluruh solusi digital yang dikembangkan oleh **Pulba Digital**.

---

## 🌐 Platform dalam Ekosistem

1. **[Jejak Bahagia](https://jejakbahagia.com)** — *Wedding Tech*  
   Platform undangan pernikahan digital modern dan elegan. Dilengkapi fitur RSVP real-time, buku tamu interaktif, galeri multimedia HD, dan navigasi lokasi.
   
2. **[Sekulah](https://sekulah.pages.dev)** — *Edutech*  
   Sistem website sekolah profesional dengan integrasi portal SPMB online mandiri, publikasi profil akademik, dan manajemen informasi sekolah.

3. **[Desgo](https://desgo.pages.dev)** — *Govtech*  
   Sistem informasi desa dan digitalisasi tata kelola administrasi pelayanan surat-menyurat mandiri bagi warga desa.

4. **[Sobat Deadline](https://sobatdeadline.pages.dev)** — *Academic Services*  
   Layanan asistensi dan pendampingan akademik komprehensif untuk skripsi, makalah riset, pengolahan data statistik, dan desain grafis presentasi.

---

## 🛠️ Tech Stack & Standar Desain

- **Core Framework:** [Astro v7](https://astro.build) (Static Site Generation & Optimized Asset Pipeline)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com) (dengan `@tailwindcss/vite`)
- **Runtime & Package Manager:** [Bun](https://bun.sh)
- **Design Philosophy:** Swiss Style Minimalist (International Typographic Style) — tata letak grid modular presisi, tipografi tegas, dan palet warna resmi (*Deep Navy*, *Electric Blue*, *Muted Slate*, *Crisp White*).

---

## 📁 Struktur Proyek

```text
pulbagrup/
├── public/
│   ├── favicon.ico
│   └── favicon.png          # Favicon resmi
├── src/
│   ├── assets/              # Aset gambar & thumbnail (dioptimasi via Astro <Image />)
│   │   ├── logo-pulba.png
│   │   ├── favicon.png
│   │   ├── desgo_hero.png
│   │   ├── jejakbahagia_hero.png
│   │   ├── sekulah_hero.png
│   │   └── SobatDeadline.png
│   ├── components/
│   │   ├── Hero.astro       # Hero section dengan tipografi Swiss
│   │   └── ProductCards.astro # Katalog 4 platform (3-kolom grid pada lg:)
│   ├── layouts/
│   │   └── Layout.astro     # Navbar modular, metadata, dan footer
│   ├── pages/
│   │   └── index.astro      # Entry point halaman utama
│   └── styles/
│       └── global.css       # Konfigurasi token tema Tailwind v4
├── astro.config.mjs
├── bun.lock
├── package.json
└── tsconfig.json
```

---

## 🚀 Memulai (Quickstart)

Pastikan [Bun](https://bun.sh) telah terpasang di sistem Anda.

### 1. Instalasi Dependensi
```bash
bun install
```

### 2. Menjalankan Server Development
```bash
bun run dev
```
Buka `http://localhost:4321` di browser Anda.

### 3. Membangun Bundle Produksi
```bash
bun run build
```
Output static files akan dihasilkan di direktori `./dist/`.

### 4. Preview Build Lokal
```bash
bun run preview
```

---

## 📄 Lisensi & Hak Cipta

&copy; 2024–2026 **Pulba Digital**. Hak cipta dilindungi undang-undang.
