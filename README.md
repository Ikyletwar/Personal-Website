# Hizkia Letwar — Portofolio Pribadi

> **"Elegance Is My Philosophy"**

Sebuah website portofolio satu halaman yang modern, elegan, dan sepenuhnya responsif. Dibangun dengan HTML, CSS, dan JavaScript murni. Didesain dengan pendekatan mobile-first dan dilengkapi animasi smooth, lazy loading, serta praktik aksesibilitas terbaik.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/id/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/id/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/id/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/Lisensi-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## 📋 Daftar Isi

- [Tentang](#-tentang)
- [Fitur](#-fitur)
- [Teknologi](#-teknologi)
- [Filosofi Desain](#-filosofi-desain)
- [Ringkasan Bagian](#-ringkasan-bagian)
- [Memulai](#-memulai)
- [Struktur File](#-struktur-file)
- [Kustomisasi](#-kustomisasi)
- [Deployment](#-deployment)
- [Kompatibilitas Browser](#-kompatibilitas-browser)
- [Performa](#-performa)
- [Aksesibilitas](#-aksesibilitas)
- [Penulis](#-penulis)
- [Lisensi](#-lisensi)

---

## 🙋‍♂️ Tentang

Ini adalah website portofolio pribadi resmi milik **Hizkia Letwar**, seorang siswa di **SMK Negeri 1 Maluku Tengah** jurusan **Teknik Jaringan Komputer dan Telekomunikasi (TJKT)** dan menjabat sebagai **Anggota OSIS Bidang IT**.

Website ini menampilkan pendekatan unik dalam pengembangan web yang disebut **"Vibe Coding"** — sebuah metodologi pengembangan berbantuan AI di mana ide dalam bahasa alami diubah menjadi kode yang berfungsi, memungkinkan developer fokus pada kreativitas dan pemecahan masalah.

### Highlight Utama

| Aspek | Detail |
|-------|--------|
| **Nama** | Hizkia Letwar |
| **Sekolah** | SMK Negeri 1 Maluku Tengah |
| **Jurusan** | TJKT (Teknik Jaringan Komputer & Telekomunikasi) |
| **Jabatan** | Anggota OSIS Bidang IT |
| **Fokus** | AI Engineering, Web Development |
| **Filosofi** | "Elegance Is My Philosophy" |
| **Gaya Development** | Vibe Coding (Berbantuan AI) |

---

## ✨ Fitur

### Visual & Interaktif

- 🎨 **Tema Gelap** — Latar belakang hitam elegan dengan overlay gradient halus
- 🌊 **Glassmorphism Navigation** — Navbar efek kaca buram dengan backdrop blur
- ⌨️ **Efek Mesin Ketik** — Teks dinamis yang berganti otomatis
- 📱 **Sepenuhnya Responsif** — Desain mobile-first dengan breakpoint untuk semua ukuran layar
- 🎭 **Animasi Scroll** — Animasi reveal smooth saat scroll
- 🚀 **Lazy Loading** — Bagian dimuat secara progresif saat masuk viewport
- 🎯 **Smooth Scrolling** — Perilaku scroll smooth native
- 🔄 **Efek Hover** — Transformasi halus pada elemen interaktif

### Navigasi

- 📱 **Menu Hamburger Mobile** — Navigasi collapsible untuk layar kecil
- 🔗 **Anchor Links** — Scroll smooth ke bagian (Tentang, Proyek, Tools, Kontak)
- 📍 **Header Sticky** — Navigasi dengan visibilitas berbasis scroll
- ♿ **Label ARIA** — Dukungan aksesibilitas penuh untuk screen reader

### Performa

- ⚡ **Nol Dependensi** — Tanpa framework atau library eksternal (kecuali font)
- 🎯 **CSS Teroptimasi** — Custom properties CSS untuk theming efisien
- 🧠 **Intersection Observer** — Animasi scroll-triggered yang efisien
- 🚫 **Dukungan Reduced Motion** — Menghormati preferensi motion pengguna
- 📦 **Single File** — Semua dalam satu file HTML untuk pemuatan cepat

---

## 🛠️ Teknologi

| Teknologi | Tujuan |
|-----------|--------|
| **HTML5** | Struktur semantik dan konten |
| **CSS3** | Styling dengan custom properties, flexbox, grid |
| **JavaScript (Murni)** | Fitur interaktif dan animasi |
| **Google Fonts** | Font family Inter untuk tipografi |
| **SVG** | Icon dan grafis inline |

### Fitur CSS yang Digunakan

- **Custom Properties (Variabel CSS)** — Sistem theming terpusat
- **Flexbox** — Manajemen layout
- **CSS Grid** — Layout grid kompleks
- **Media Queries** — Breakpoint responsif
- **Animasi CSS** — Animasi keyframe
- **Transisi** — Perubahan state smooth
- **Backdrop Filter** — Efek glassmorphism
- **Transform** — Transformasi 2D/3D
- **Calc()** — Perhitungan dinamis

### Fitur JavaScript yang Digunakan

- **Intersection Observer API** — Animasi trigger scroll
- **Request Animation Frame** — Penanganan scroll smooth
- **Manipulasi DOM** — Update konten dinamis
- **Event Listeners** — Penanganan interaksi pengguna
- **SetTimeout** — Timing efek mesin ketik
- **MatchMedia** — Deteksi reduced motion

---

## 🎨 Filosofi Desain

### Prinsip Inti

```
"Elegance Is My Philosophy"
```

Desain dibangun di atas tiga prinsip inti:

1. **UI Bersih** — Desain minimalis dengan elemen yang memiliki tujuan
2. **Fungsi Elegan** — Setiap interaksi terasa smooth dan disengaja
3. **Fitur Thoughtful** — Setiap fitur memiliki tujuan jelas

### Palet Warna

| Variabel | Nilai | Penggunaan |
|----------|-------|------------|
| `--bg` | `#000000` | Latar utama |
| `--bg-elevated` | `#0a0a0b` | Permukaan elevated |
| `--fg` | `#F5F5F7` | Teks primer |
| `--fg-secondary` | `#d1d1d6` | Teks sekunder |
| `--muted` | `#86868b` | Teks muted |
| `--muted-secondary` | `#6e6e73` | Teks muted dalam |
| `--accent` | `rgba(255, 255, 255, 0.04)` | Latar accent |
| `--accent-hover` | `rgba(255, 255, 255, 0.08)` | State hover |
| `--border` | `rgba(255, 255, 255, 0.06)` | Border halus |
| `--border-hover` | `rgba(255, 255, 255, 0.12)` | Border hover |

### Skala Tipografi

| Variabel | Mobile | Desktop |
|----------|--------|---------|
| `--text-xs` | 0.6875rem | 0.75rem |
| `--text-sm` | 0.8125rem | 0.875rem |
| `--text-base` | 0.9375rem | 1rem |
| `--text-lg` | 1.0625rem | 1.125rem |
| `--text-xl` | 1.125rem | 1.25rem |
| `--text-2xl` | 1.25rem | 1.75rem |
| `--text-3xl` | 1.75rem | 3rem |
| `--text-hero` | 2.25rem | 5rem |

### Sistem Spasi

Semua spasi mengikuti skala konsisten:

- `--space-xs`: 4px
- `--space-sm`: 8px
- `--space-md`: 16px
- `--space-lg`: 24px
- `--space-xl`: 32px
- `--space-2xl`: 48px
- `--space-3xl`: 64px
- `--space-4xl`: 96px

### Border Radius

- `--radius-xs`: 6px
- `--radius-sm`: 10px
- `--radius-md`: 14px
- `--radius-lg`: 20px
- `--radius-xl`: 28px

### Timing Animasi

| Variabel | Nilai | Penggunaan |
|----------|-------|------------|
| `--duration-fast` | 150ms | Interaksi cepat |
| `--duration-base` | 250ms | Transisi standar |
| `--duration-slow` | 400ms | Animasi smooth |
| `--duration-slower` | 600ms | Urutan kompleks |

**Fungsi Easing:**
- `--ease-out`: `cubic-bezier(0.16, 1, 0.3, 1)`
- `--ease-in-out`: `cubic-bezier(0.65, 0, 0.35, 1)`

---

## 📑 Ringkasan Bagian

### 1. Navigasi
- Header posisi fixed dengan efek glassmorphism
- Logo (inisial HL)
- Menu hamburger mobile
- Link navigasi: Tentang, Proyek, Tools, Kontak

### 2. Bagian Hero
- Teks overline dengan elemen dekoratif
- Judul utama dengan span animasi
- Efek mesin ketik dengan frase berganti:
  - "Elegance Is My Philosophy"
  - "Vibe Coding Enthusiast"
  - "AI-Assisted Developer"
  - "Problem Solver"
  - "Future AI Engineer"
- Deskripsi subtitle
- Tombol CTA: "Lihat Proyek" dan "Hubungi Aku"
- Indikator scroll (hanya desktop)

### 3. Bagian Bio/Tentang
- Layout dua kolom (desktop)
- Label dan heading bagian
- Tiga paragraf konten biografi
- Grid detail dengan:
  - Sekolah
  - Jurusan
  - Peran
  - Fokus

### 4. Bagian Filosofi
- Kartu quote di tengah
- Efek text gradient
- Teks deskripsi

### 5. Bagian Proyek
- Header bagian
- Kartu proyek unggulan (SIRA - Sistem Informasi Razia Siswa)
  - Indikator badge
  - Judul dan subtitle
  - Deskripsi
  - Daftar fitur dengan checkmark
  - Tag teknologi
- Grid proyek dengan kartu tambahan

### 6. Bagian Tools
- Grid layout tools AI yang digunakan:
  - Trae AI
  - ChatGPT
  - Gemini
  - Qwen
  - Qwen Code CLI

### 7. Bagian Inspirasi
- Kartu mentor menampilkan "Pak Bahy"
- Placeholder avatar
- Nama, peran, dan deskripsi

### 8. Bagian Kontak
- Layout di tengah
- Judul dan deskripsi
- Link email dengan animasi underline hover
- Link sosial:
  - GitHub (@Ikyletwar)
  - TikTok (@ikyletwar)
  - Instagram (@ikyletwar)

### 9. Footer
- Teks hak cipta
- Tagline filosofi

---

## 🚀 Memulai

### Prasyarat

Ini adalah website statis tanpa build process. Anda hanya butuh:

- Browser modern (Chrome, Firefox, Safari, Edge)
- Text editor (opsional, untuk kustomisasi)

### Instalasi

1. **Clone atau download** repository ini:
   ```bash
   git clone https://github.com/Ikyletwar/Personal-Website.git
   cd Personal-Website
   ```

2. **Buka file** di browser Anda:
   ```bash
   # Di Windows
   start index.html

   # Di macOS
   open index.html

   # Di Linux
   xdg-open index.html
   ```

3. **Atau gunakan local server** (direkomendasikan):
   ```bash
   # Menggunakan Python 3
   python -m http.server 8000

   # Menggunakan Node.js (npx)
   npx serve

   # Menggunakan PHP
   php -S localhost:8000
   ```

4. **Buka** `http://localhost:8000` di browser Anda

---

## 📁 Struktur File

```
root-proyek/
│
├── index.html          # File HTML utama (berisi semua CSS dan JS)
├── README.md           # File dokumentasi ini
└── .git/               # Direktori Git
```

### Di dalam index.html

```
index.html
│
├── <!DOCTYPE html>
├── <head>
│   ├── Meta tags
│   ├── Title
│   ├── Link Google Fonts
│   └── <style> (CSS - ~1.400 baris)
│       ├── Custom Properties CSS
│       ├── Reset & Base Styles
│       ├── Efek Latar Belakang
│       ├── Style Navigasi
│       ├── Style Bagian
│       ├── Style Komponen
│       ├── Kelas Animasi
│       └── Media Queries Responsif
│
├── <body>
│   ├── Elemen latar (gradient, noise)
│   ├── Wrapper konten
│   │   ├── Navigasi
│   │   ├── Konten utama
│   │   │   ├── Bagian Hero
│   │   │   ├── Bagian Bio
│   │   │   ├── Bagian Filosofi
│   │   │   ├── Bagian Proyek
│   │   │   ├── Bagian Tools
│   │   │   ├── Bagian Inspirasi
│   │   │   └── Bagian Kontak
│   │   └── Footer
│   │
│   └── <script> (JavaScript - ~200 baris)
│       ├── Inisialisasi Variabel
│       ├── Handler DOMContentLoaded
│       ├── Navigasi Mobile
│       ├── Animasi Scroll Reveal
│       ├── Lazy Loading
│       ├── Efek Scroll Nav
│       └── Efek Mesin Ketik
│
└── </body>
</html>
```

---

## 🔧 Kustomisasi

### Mengubah Informasi Pribadi

1. **Nama dan Judul**
   - Cari "Hizkia Letwar" dan ganti dengan nama Anda
   - Update tag `<title>`

2. **Informasi Kontak**
   - Email: Cari `manggadurian20@gmail.com`
   - Link sosial: Update atribut `href` di bagian social-links

3. **Konten Bio**
   - Edit paragraf di bagian `.bio-content`
   - Update detail di `.detail-grid`

4. **Proyek**
   - Modifikasi kartu proyek di bagian projects
   - Update informasi featured project

### Mengubah Warna

Edit custom properties CSS di selector `:root`:

```css
:root {
    --bg: #000000;              /* Ubah latar */
    --fg: #F5F5F7;              /* Ubah warna teks */
    --accent: rgba(255,255,255,0.04);  /* Ubah warna accent */
}
```

### Mengubah Tipografi

Update link Google Fonts dan font-family:

```html
<!-- Ubah link ini -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<!-- Dan update font-family di CSS -->
font-family: 'Font Anda', sans-serif;
```

### Memodifikasi Teks Mesin Ketik

Cari array `typewriterTexts` di bagian JavaScript:

```javascript
const typewriterTexts = [
    '"Elegance Is My Philosophy"',
    '"Vibe Coding Enthusiast"',
    '"AI-Assisted Developer"',
    '"Problem Solver"',
    '"Future AI Engineer"'
];
```

Ganti dengan frase Anda sendiri.

### Menyesuaikan Kecepatan Animasi

Modifikasi variabel duration:

```css
:root {
    --duration-fast: 150ms;
    --duration-base: 250ms;
    --duration-slow: 400ms;
    --duration-slower: 600ms;
}
```

---

## 🌐 Deployment

Website ini statis dan bisa di-deploy ke platform hosting statis manapun.

### GitHub Pages

1. Push kode ke repository GitHub
2. Buka **Settings > Pages**
3. Pilih branch dan folder Anda
4. Website akan tersedia di `https://username.github.io/nama-repo`

### Vercel

1. Instal Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

3. Ikuti prompt

### Netlify

1. Drag and drop folder proyek ke [Netlify Drop](https://app.netlify.com/drop)
2. Atau sambungkan repository Git untuk deployment otomatis

### Hosting Manual

Cukup upload `index.html` ke web server atau penyedia hosting manapun.

---

## 🌍 Kompatibilitas Browser

### Browser yang Didukung

| Browser | Versi | Dukungan |
|---------|-------|----------|
| Chrome | 80+ | ✅ Penuh |
| Firefox | 75+ | ✅ Penuh |
| Safari | 13+ | ✅ Penuh |
| Edge | 80+ | ✅ Penuh |
| Opera | 65+ | ✅ Penuh |
| Samsung Internet | 11+ | ✅ Penuh |

### Dukungan Fitur

| Fitur | Dukungan | Catatan |
|-------|----------|---------|
| Custom Properties CSS | ✅ | IE tidak didukung |
| Flexbox | ✅ | Dukungan penuh |
| CSS Grid | ✅ | Dukungan penuh |
| Backdrop Filter | ⚠️ | Safari butuh prefix `-webkit-` |
| Intersection Observer | ✅ | Fallback disertakan |
| Request Animation Frame | ✅ | Dukungan penuh |
| Arrow Functions | ✅ | Butuh dukungan ES6 |
| Template Literals | ✅ | Butuh dukungan ES6 |
| Const/Let | ✅ | Butuh dukungan ES6 |

### Fallback

Kode menyertakan fallback untuk:
- **Reduced motion**: Menghormati `prefers-reduced-motion`
- **Browser lama**: Degradasi elegan untuk fitur tidak didukung
- **Tanpa JavaScript**: Konten tetap dapat diakses

---

## ⚡ Performa

### Metrik Performa

| Metrik | Target | Pencapaian |
|--------|--------|------------|
| First Contentful Paint | < 1.5s | ✅ |
| Time to Interactive | < 3s | ✅ |
| Total Ukuran Bundle | ~50KB | ✅ |
| Request Eksternal | 1 (font) | ✅ |
| Ukuran JavaScript | ~8KB | ✅ |
| Ukuran CSS | ~35KB | ✅ |

### Teknik Optimasi

1. **Arsitektur Single File**
   - Tanpa request HTTP tambahan
   - Load awal lebih cepat

2. **Optimasi CSS**
   - Custom properties untuk update efisien
   - Tanpa framework CSS tidak terpakai

3. **Optimasi JavaScript**
   - Event delegation bila memungkinkan
   - Intersection Observer untuk deteksi scroll efisien
   - Request Animation Frame untuk animasi smooth

4. **Lazy Loading**
   - Bagian dimuat hanya saat dibutuhkan
   - Waktu paint awal berkurang

5. **Dukungan Reduced Motion**
   - Menghormati preferensi pengguna
   - Aksesibilitas lebih baik

---

## ♿ Aksesibilitas

### Kepatuhan WCAG 2.1

| Kriteria | Implementasi |
|----------|--------------|
| **HTML Semantik** | Hierarki heading proper (h1-h3) |
| **Label ARIA** | Navigasi, tombol, dan link berlabel |
| **Navigasi Keyboard** | Semua elemen interaktif dapat difokuskan |
| **Indikator Fokus** | Style fokus terlihat pada semua elemen |
| **Kontras Warna** | Teks memenuhi persyaratan kontras WCAG AA |
| **Reduced Motion** | Menghormati `prefers-reduced-motion` |
| **Screen Reader** | Kompatibel dengan screen reader utama |
| **Bahasa** | Atribut `lang="id"` diatur |

### Implementasi ARIA

```html
<!-- Navigasi -->
<nav class="nav" role="navigation" aria-label="Navigasi utama">
    <button class="nav-toggle" aria-label="Toggle menu" aria-expanded="false">
    <!-- ... -->
    </button>
</nav>

<!-- Link Sosial -->
<a href="..." class="social-link" aria-label="GitHub">
```

### Navigasi Keyboard

- `Tab` - Navigasi melalui elemen interaktif
- `Enter` - Aktifkan link dan tombol
- `Spasi` - Toggle menu mobile
- `Escape` - Tutup menu mobile

---

## 👨‍💻 Penulis

**Hizkia Letwar**

- 📍 Maluku Tengah, Indonesia
- 🎓 Siswa di SMK Negeri 1 Maluku Tengah
- 💼 Anggota OSIS Bidang IT
- 🎯 Fokus: AI Engineering, Web Development
- 📧 Email: [manggadurian20@gmail.com](mailto:manggadurian20@gmail.com)

### Terhubung

[![GitHub](https://img.shields.io/badge/GitHub-%40Ikyletwar-181717?style=for-the-badge&logo=github)](https://github.com/Ikyletwar)
[![Instagram](https://img.shields.io/badge/Instagram-%40ikyletwar-E4405F?style=for-the-badge&logo=instagram)](https://www.instagram.com/ikyletwar/)
[![TikTok](https://img.shields.io/badge/TikTok-%40ikyletwar-000000?style=for-the-badge&logo=tiktok)](https://www.tiktok.com/@ikyletwar)

---

## 📄 Lisensi

Proyek ini open source dan tersedia di bawah [Lisensi MIT](https://opensource.org/licenses/MIT).

```
MIT License

Copyright (c) 2026 Hizkia Letwar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Ucapan Terima Kasih

- **Pak Bahy** — Guru Bahasa Inggris, programmer, dan AI enthusiast yang menginspirasi perjalanan ke dunia programming dan vibe coding
- **Google Fonts** — Untuk font family Inter yang indah
- **Komunitas Vibe Coding** — Untuk mendorong batas-batas pengembangan berbantuan AI

---

## 📝 Catatan

### Apa itu Vibe Coding?

**Vibe Coding** adalah pendekatan pengembangan berbantuan AI di mana:
- Prompt bahasa alami digunakan untuk menghasilkan kode
- Fokus pada kreativitas dan pemecahan masalah, bukan sintaks
- Tools AI seperti Trae AI, ChatGPT, dan Qwen digunakan sebagai partner coding
- Prototyping dan iterasi cepat memungkinkan

### Tools yang Digunakan dalam Development

Website ini dibangun menggunakan:
- **Trae AI** — Generasi kode bertenaga AI
- **Qwen Code CLI** — Asisten AI command-line
- **ChatGPT** — Bantuan AI tujuan umum
- **Gemini** — Asisten AI Google

---

<div align="center">

**Dibangun dengan ❤️ dan AI oleh Hizkia Letwar**

*"Elegance Is My Philosophy"*

</div>
