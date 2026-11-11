---
name: EVENT.KITA
colors:
  surface: '#fcf8ff'
  surface-dim: '#dcd6f8'
  surface-bright: '#fcf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f1ff'
  surface-container: '#f0ebff'
  surface-container-high: '#ebe5ff'
  surface-container-highest: '#e5deff'
  on-surface: '#1b1831'
  on-surface-variant: '#494455'
  inverse-surface: '#302d47'
  inverse-on-surface: '#f3eeff'
  outline: '#7a7486'
  outline-variant: '#cac3d7'
  surface-tint: '#663cdd'
  primary: '#5728cf'
  on-primary: '#ffffff'
  primary-container: '#7048e8'
  on-primary-container: '#ede4ff'
  inverse-primary: '#ccbdff'
  secondary: '#2552ca'
  on-secondary: '#ffffff'
  secondary-container: '#446ce4'
  on-secondary-container: '#fffbff'
  tertiary: '#523bb1'
  on-tertiary: '#ffffff'
  tertiary-container: '#6b55cb'
  on-tertiary-container: '#ece5ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7deff'
  primary-fixed-dim: '#ccbdff'
  on-primary-fixed: '#1f005f'
  on-primary-fixed-variant: '#4d17c5'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b6c4ff'
  on-secondary-fixed: '#00164e'
  on-secondary-fixed-variant: '#003baf'
  tertiary-fixed: '#e6deff'
  tertiary-fixed-dim: '#cabeff'
  on-tertiary-fixed: '#1c0062'
  on-tertiary-fixed-variant: '#482fa7'
  background: '#fcf8ff'
  on-background: '#1b1831'
  surface-variant: '#e5deff'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 34px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
Design system ini dirancang untuk platform manajemen dan agregator event kampus/mahasiswa dengan karakter modern SaaS: bersih, terstruktur, energik, namun tetap berwibawa secara profesional.

### Target Audiens
- Mahasiswa dan organisasi intra/ekstra kampus (BEM, Himpunan, UKM, Komite Festival).
- Peserta kegiatan akademik, kompetisi, seminar, workshop, hingga konser seni mahasiswa.

### Respon Emosional
Antarmuka harus memicu rasa percaya diri, antusiasme eksplorasi kegiatan baru, kemudahan navigasi tanpa distraksi visual, dan efisiensi waktu dalam registrasi maupun ticketing.

### Pendekatan Gaya Visual
- **Modern Clean SaaS & Subtle Layering:** Memadukan fluiditas tipografi humanist yang ramah dengan struktur layout modular.
- Mengedepankan whitespace lapang, card ber-radius medium-tinggi, aksen warna ungu-biru yang dinamis, serta pemanfaatan Lucide stroke icons (1.75px–2px stroke) yang konsisten.

## Colors
Sistem warna mengandalkan kontras yang harmonis antara nuansa royal purple dan cobalt blue di atas kanvas ultra-soft violet-tinted white.

### Palet Inti & Semantik
- **Primary Purple (`#7048E8`):** Aksi utama, high-priority CTA, tab aktif, dan highlight identitas event.
- **Deep Purple (`#4930A8`):** Hover state pada button primer, link penting saat ditekan, serta penekanan teks hero.
- **Primary Blue (`#4169E1`):** Warna pendukung (secondary), penanda kategori webinar/kompetisi, status informasi, dan gradient pairing bersama Primary Purple.
- **Surface & Tint Tiers:**
  - **Background Canvas (`#F8F9FF`):** Latar belakang utama aplikasi yang dingin dan bersih.
  - **Surface White (`#FFFFFF`):** Latar card, modul form, dan modal pop-up.
  - **Lavender Tint (`#F1EDFF`):** Badge background aktif, filter chip yang dipilih, dan hover fill pada list item.
  - **Light Blue Tint (`#EAF0FF`):** Badge kategori teknikal, info cards, dan alert container.
- **Teks & Netral:**
  - **Primary Text (`#24213A`):** Teks judul, heading modul, dan isi penting dengan kontras tinggi.
  - **Secondary Text (`#85839A`):** Metadata event (tanggal, lokasi, kuota), placeholder input, dan inactive navigation.
  - **Border Subtle (`#E6E8F2`):** Garis pemisah ultra-tipis untuk menjaga keteraturan tanpa membuat interface terlihat berat.

## Typography
Hirarki tipografi menggabungkan kehangatan modern dan ekspresi muda dari **Plus Jakarta Sans** untuk seluruh heading, dipadukan dengan presisi tinggi dan efisiensi keterbacaan data dari **Inter** untuk UI, paragraf, badge, dan kontrol interaktif.

### Panduan Implementasi
- Gunakan minus letter-spacing pada level display dan headline untuk memperkuat kesan kompak dan tegas ala SaaS kontemporer.
- Pada judul event di dalam kartu, batasi teks maksimal 2 baris (line-clamp-2) menggunakan `title-md` demi menjaga simetri visual grid.
- Metadata tanggal, jam, dan lokasi wajib menggunakan `body-sm` atau `label-md` dengan bobot yang jelas agar mudah dipindai cepat.

## Layout & Spacing
Sistem tata letak menggunakan 12-kolom fluid grid responsif yang terpusat dengan batasan lebar maksimal konten desktop sebesar `1240px`.

### Skala Breakpoint & Penataan Grid
- **Desktop (>= 1024px):** 12 kolom, gutter `1.5rem` (24px), margin luar `2rem` (32px). Kartu event disusun dalam format 3 hingga 4 kolom per baris.
- **Tablet (768px – 1023px):** 8 kolom, gutter `1.25rem` (20px), margin luar `1.5rem` (24px). Kartu event ditampilkan 2 kolom per baris.
- **Mobile (< 768px):** 4 kolom, gutter `1rem` (16px), margin luar `1rem` (16px). Komponen event card beralih ke 1 kolom vertikal atau horizontal swipe carousel untuk section kurasi.

### Ritmik Spasi Komponen
- Padding internal kartu event: `1rem` (16px) hingga `1.25rem` (20px).
- Jarak antar metadata dalam baris (icon + label): `0.375rem` (6px) hingga `space-sm` (8px).
- Jarak antar section halaman: `space-xl` (40px) pada desktop dan `1.75rem` (28px) pada mobile.

## Elevation & Depth
Menghindari shadow gelap yang pekat. Kedalaman visual diciptakan melalui perpaduan "ghost borders" berwarna pastel netral dan ambient shadows yang terdifusi halus dengan nuansa ungu kebiruan.

### Tingkatan Elevasi
- **Level 0 (Flat / Kanvas):** `#F8F9FF` tanpa bayangan, digunakan untuk area canvas utama dan background section selang-seling.
- **Level 1 (Card Default & Form Surface):** Background `#FFFFFF`, outline border `1px solid #E6E8F2`, bayangan: `0 2px 8px -2px rgba(36, 33, 58, 0.04), 0 1px 4px -1px rgba(112, 72, 232, 0.03)`.
- **Level 2 (Hover State Card & Floating Controls):** Digunakan saat kursor berada di atas kartu event atau filter dropdown aktif. Transformasi translateY(-2px) disertai bayangan: `0 12px 24px -6px rgba(112, 72, 232, 0.12), 0 4px 12px -2px rgba(36, 33, 58, 0.04)`.
- **Level 3 (Modal, Floating Ticket Bar & Popover):** Latar `#FFFFFF`, border `1px solid rgba(112, 72, 232, 0.08)`, bayangan: `0 20px 32px -8px rgba(36, 33, 58, 0.14), 0 8px 16px -4px rgba(112, 72, 232, 0.08)`.

## Shapes
Tingkat kebulatan ditetapkan pada level **2 (Rounded)** untuk memancarkan aura youthful, ramah mahasiswa, dan tidak kaku, namun tetap mempertahankan kerapian layout enterprise.

### Distribusi Radius Elemen
- **Card & Banner Promosi:** `rounded-lg` (12px hingga 16px) untuk membingkai poster event dan kontainer ringkasan.
- **Input Fields & Form Elements:** `0.625rem` (10px) hingga `rounded` (8px) untuk kenyamanan area sentuh.
- **Tombol & Action Chips:** `rounded` (8px hingga 10px) untuk tombol reguler; pill-shaped (`9999px`) diperbolehkan khusus status badge dan category tag kecil.
- **Modal & Bottom Sheets:** `rounded-xl` (20px hingga 24px) pada sudut atas untuk transisi mobile sheet.

## Components

### 1. Tombol (Buttons)
- **Primary:** Background `#7048E8`, teks `#FFFFFF`, tinggi 44px (desktop) / 48px (mobile), font `label-lg`, tanpa border. Hover state transisi halus ke Deep Purple `#4930A8`.
- **Secondary:** Background `#F1EDFF`, teks `#7048E8`, border `1px solid rgba(112, 72, 232, 0.2)`. Hover state background berubah menjadi `#E7E0FF`.
- **Outline / Ghost:** Latar transparan, border `1px solid #E6E8F2`, teks `#24213A`. Hover state background `#F8F9FF`.
- **Icon Placement:** Gunakan Lucide icons berukuran 18px dengan margin 8px dari teks tombol.

### 2. Status Badges & Category Chips
- **Format:** Pill-shape (`rounded-full`), padding vertikal `4px`, horizontal `10px`, font `label-sm`.
- **Status Registrasi Buka:** Background `#EAF0FF`, teks `#4169E1`, ikon titik (dot indicator) `#4169E1`.
- **Status Segera Berakhir:** Background `#FFF4E5`, teks `#D97706`.
- **Category Filter Chips (Default):** Background `#FFFFFF`, border `1px solid #E6E8F2`, teks `#85839A`.
- **Category Filter Chips (Active):** Background `#7048E8`, teks `#FFFFFF`, border transparan, dengan transisi 150ms.

### 3. Kartu Event (Modern Event Cards)
- Struktur vertikal: Area thumbnail poster aspek 16:9 (`rounded-t-[12px]`) dengan badge status mengambang di pojok kanan atas.
- Bagian konten (`p-4` atau `p-5`): Tag organisasi/kampus warna `#85839A` (`body-sm`), Judul Event `title-md` warna `#24213A` (max 2 baris).
- Baris metadata: Dua kolom ringkas berisi tanggal dan lokasi/platform (Online via Zoom / Offline di Kampus) disertai Lucide icons (`Calendar`, `MapPin`) ukuran 14px warna `#85839A`.
- Footer kartu: Informasi harga ("Gratis" / "Rp XX.XXX") di sisi kiri dengan font `title-md` tebal, dan tombol aksi "Detail" atau "Daftar" di sisi kanan.

### 4. Input Fields & Search Bars
- Tinggi input 44px, latar `#FFFFFF`, border `1px solid #E6E8F2`, font `body-md`.
- Focus state: Border berubah menjadi `#7048E8` disertai outline ring halus `0 0 0 3px rgba(112, 72, 232, 0.15)`.
- Input pencarian global dilengkapi Lucide `Search` icon pada leading side dan shortcut chip (misal: "Ctrl + K") di sisi trailing.

### 5. Checkboxes & Radio Buttons
- Checkbox berukuran 18x18px, radius 5px. Saat checked: background `#7048E8` dengan Lucide check icon warna `#FFFFFF`.
- Radio button: Lingkaran 18px dengan border 2px `#7048E8` dan titik pusat 8px ketika dipilih.

### 6. Floating Action Ticket Bar (Mobile Specific)
- Bar menempel di bagian bawah viewport mobile khusus halaman detail event: Latar `#FFFFFF` dengan elevasi Level 3, menampilkan harga ringkas dan tombol full-width "Beli Tiket / Daftar Sekarang" untuk konversi instan.