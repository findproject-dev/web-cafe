# FindFein Cafe - Web Project Setup

Proyek landing page cafe **FindFein** dibangun menggunakan framework modern **Astro** dan styling modular menggunakan **Vanilla CSS** untuk performa optimal dan desain luxury industrial minimalist.

## 🚀 Menjalankan Proyek dengan Bun

Proyek ini sepenuhnya dikonfigurasi untuk menggunakan **Bun** sebagai runtime dan package manager utama. Jangan gunakan `npm`.

### 1. Instalasi Dependensi
Untuk menginstal seluruh package yang diperlukan:
```bash
bun install
```

### 2. Mode Pengembangan (Development)
Untuk menjalankan server lokal dengan live reload:
```bash
bun dev
```
Buka browser Anda di: [http://localhost:4321](http://localhost:4321)

### 3. Build Produksi
Untuk melakukan kompilasi file produksi yang dioptimalkan:
```bash
bun run build
```

### 4. Preview Produksi
Untuk meninjau hasil build lokal:
```bash
bun run preview
```

---

## 🎨 Design System & Visual Guidelines

Website ini menggunakan kombinasi design system premium:
* **design-taste-frontend**
* **minimalist-ui**

### 📍 Palette Warna
* **Background utama:** `#0c0a09` (Warm espresso black)
* **Surface card:** `#141211` (Warm charcoal dark)
* **Accent Gold:** `#c5a57f` (Muted gold luxury)
* **Accent Brown/Coffee:** `#8c6239` (Warm coffee brown)

### 📁 Struktur Folder Utama
* `/src/components/` - Komponen Astro modular (Navbar, Hero, Menu, dll.)
* `/src/layouts/` - Layout halaman utama (`Layout.astro`)
* `/src/styles/` - Stylesheet Vanilla CSS (`global.css`)
* `/public/images/` - Aset gambar cafe premium yang di-generate AI
