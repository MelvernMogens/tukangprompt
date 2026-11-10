# Tukang Prompt

**Landing page jasa bangun sistem AI buat bisnis: "Lo cerita masalahnya. Gue rakit sistemnya pakai AI."**

Satu halaman statis buat jualan jasa: dashboard, bot, sistem booking, dan tools internal custom buat UMKM dan bisnis yang masih ngerjain semuanya manual.

**Live:** https://melvernmogens.github.io/tukangprompt/

![Logo Tukang Prompt](logo.png)

## Isi halaman

- **Hero** dengan teks ketik-otomatis yang gonta-ganti contoh masalah ("catat penjualan harian otomatis", "bot yang balesin order di WA", …)
- **Masalah**: kerjaan manual yang bikin bocor waktu
- **Layanan**: Dashboard Operasional · Bot & Automation · Sistem Booking · Prediksi & Kalkulasi · Tools Internal Custom · Web & Landing
- **Karya** (`#karya`): Platform Booking Multi-Bisnis · Kalkulator Harga Jasa · Bot Analis Saham IDX · Sistem Pembelian Komoditas
- **Cara kerja**: ngobrol dulu → gue rancang & bangun → lo pakai, gue dampingin
- **Kontak** (`#contact`): tombol WhatsApp + email, plus tombol WA melayang (FAB) yang muncul pas di-scroll

Tema terang ala cat air, warnanya diambil dari palet logo lumba-lumba.

## Teknis

- Satu file: `index.html` (CSS & JS inline), tanpa build, tanpa dependency.
- Tetap kebaca walau JS mati: konten nggak disembunyiin kalau JS nggak jalan, dan link WA/email ditulis langsung di HTML.
- Animasi reveal pakai `IntersectionObserver` dan ngikutin `prefers-reduced-motion`.
- Aset: `logo.png`, `favicon-64.png`, `apple-touch-icon.png` (juga dipakai buat OG image).

## Jalanin lokal

```bash
git clone https://github.com/MelvernMogens/tukangprompt.git
open tukangprompt/index.html
```

## Ganti kontak

Nomor WA dan email ditulis langsung di beberapa link `wa.me/…` dan `mailto:…`. Ganti pakai find/replace di `index.html` (instruksinya ada di komentar paling atas blok `<script>`).

---

Dibuat oleh [Melvern Mogens](https://github.com/MelvernMogens).
