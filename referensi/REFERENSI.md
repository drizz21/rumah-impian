# Referensi Desain — Website Rumah Impian

> Dokumen ini adalah **sumber kebenaran visual** untuk project ini.
> Setiap perubahan desain harus merujuk ke sini. Gambar aslinya ada di folder ini.

## Berkas

| File | Keterangan |
|---|---|
| `desain-utama.jpg` | Referensi utama (688 × 2560 px, screenshot panjang) |
| `desain-utama-alt.jpg` | Salinan/versi lain dari referensi yang sama |

---

## Palet Warna (hasil sampling piksel, bukan perkiraan)

| Peran | Hex | Dipakai di |
|---|---|---|
| Latar halaman | `#EDF4E2` | Latar di belakang kartu putih |
| Kartu / permukaan | `#FFFFFF` | Badan utama halaman, kartu |
| Aksen (lime) | `#CDF187` | Tombol Register, Search, Read More, Explore, Get a Quote |
| Hijau tua | `#0F483F` | Latar footer + harga properti |
| Teks judul | `#1A2B3C` | Judul, teks tegas |
| Teks abu | `#94A3B8` / `slate-400` | Paragraf, keterangan |
| Garis | `slate-200` | Border kartu, pemisah |

## Tipografi

- Font: **Plus Jakarta Sans** (400 / 500 / 600 / 700 / 800)
- Judul utama (H1): 50px, weight 800, `leading-[1.08]`, `tracking-[-0.02em]`
- Judul bagian (H2): 34px, weight 800
- Judul kartu: 15–16px, weight 800
- Isi: 12.5–13.5px, `slate-400`
- Label kecil: 11px, uppercase-ish, `font-semibold`

## Bentuk

- Bingkai halaman: kartu putih `rounded-4xl` (28px) di atas latar mint, `margin 24px`
- Tombol: **pill penuh** (`rounded-full`)
- Kartu: `rounded-2xl` (16px)
- Input: `rounded-xl` (12px)
- Bayangan: lembut, tidak tajam

---

## Susunan Bagian (urut dari atas)

### 1. Navbar
Logo ikon rumah (kotak lime, ikon hijau tua) + "Rumah Impian" (extrabold 19px)
Menu tengah: Home · Property · Product · About Us · Contact Us
Kanan: "Login" (teks) + "Register" (pill lime)
Mobile: menu disembunyikan, muncul tombol hamburger

### 2. Hero (2 kolom)
**Kiri:** H1 3 baris — `Start Your Search` / `For The Perfect Living` / `Space Now.`
(baris ke-3 **menjorok ke kanan** ±40px)
Subjudul abu 2 baris · Tombol "See Property" (putih ber-border) + "About Us" (teks)
Baris bawah: 3 avatar bertumpuk + badge lime "30+" + teks ajakan + tautan "Contact Advisor"

**Kanan:** Gambar rumah (ilustrasi) `rounded-3xl`, rasio ±4:3.1
- Kartu kaca "50+" di kanan bawah (putih transparan + blur), teks "We have 50+ Properties For You", ada ikon panah
- 3 titik navigasi di tengah bawah

### 3. Search Bar (mengapung, 1 baris)
Kontainer putih **pill penuh** dengan bayangan, berisi:
`Location` → `Select Type` → `Budget` (masing-masing ikon dalam lingkaran mint, label tebal + placeholder abu), dipisah garis vertikal tipis, lalu tombol lime **"Search Property"**
Mobile: menumpuk vertikal

### 4. Services
Badge "Services" (pill outline) · Judul tengah "Your Trusted Real Estate Partner"
4 kartu (border `slate-200`, `rounded-2xl`, **tanpa bayangan**, ikon garis 32px tanpa wadah):
1. Personalized Service — "Tailored Consultations And Strategies To Meet Individual Client Needs."
2. Expert Local Agents — "Knowledgeable Agents With Expertise In Specific Neighborhoods And Markets."
3. Track Record — "Offering A History Of Successful Transactions And Satisfied Clients."
4. Advanced Search Filters — "Robust Filtering Options To Narrow Down Searches By Price, Location, Property Type."

### 5. About + Statistik
Baris atas: badge "Who We Are" + judul "Turning Your Real Estate Dreams Into Reality." (kiri) — tombol "Read More" (kanan, sejajar bawah)
Baris bawah: **4 statistik dalam 1 baris**, tanpa garis pemisah:
| Angka | Keterangan |
|---|---|
| 250+ | Successfully Closed 250 Residential Properties In 2024 Alone |
| 100+ | Operate With A Dedicated Team Of 100 Licensed Agents |
| 30% | Achieved A 30% Increase In Sales Compared To The Previous Year |
| 4.9 | Maintained An Average Customer Rating Of 4.9 Out Of 5 Based On Client Feedback |

### 6. Property Listings
Badge "Property" · Judul tengah "Discover Your Ideal Living Space!"
Grid **3 kolom × 2 baris**, kartu **tanpa border/bayangan** (dipisah ruang kosong):
- Gambar `rounded-2xl` rasio 4:3, tag **"For Sale"** putih di kiri atas
- Harga (hijau tua, extrabold 16px) → Nama (bold) → baris ikon: Bed · Bath · sq ft
- Tombol tengah bawah: "Explore All Listings" (pill lime)

| # | Harga | Nama | Spesifikasi |
|---|---|---|---|
| 1 | $350,000 | Modern Condo With Stunning City Views | 2 Bed · 2 Bath · 1,100 sq ft. |
| 2 | $375,000 | Historic Home With Modern Upgrades | 5 Bed · 4 Bath · 3,500 sq ft. |
| 3 | $420,000 | Conveniently Located Townhouse | 4 Bed · 3 Bath · 2,200 sq ft. |
| 4 | $350,000 | Modern Condo With Stunning City Views | 2 Bed · 2 Bath · 1,100 sq ft. |
| 5 | $375,000 | Historic Home With Modern Upgrades | 5 Bed · 4 Bath · 3,500 sq ft. |
| 6 | $420,000 | Conveniently Located Townhouse | 4 Bed · 3 Bath · 2,200 sq ft. |

### 7. FAQ (2 kolom)
**Kiri:** badge "FAQ" + judul "Need Help? Explore Our FAQ Section!" + paragraf
**Kanan:** accordion — kotak putih border `slate-200`, `rounded-2xl`, tombol bulat mint berisi +/−
1. How Much Can I Afford To Spend On A Home? *(terbuka di referensi)*
2. What Is The Process Of Buying A Home?
3. What Should I Look For When Viewing A Property?
4. How Much Should I Offer When Buying A Home?

### 8. Testimonials
Badge "Reviews" · Judul "We've Helped Our Clients Achieve Their Dreams!"
Grid **3 kolom × 2 baris**, kartu putih ber-border, avatar bulat + nama + teks ulasan (tanpa bintang, tanpa tanda kutip)
Cora Wilderman · James Smitham · Jennifer Dach · Dewey Medhurst · Victoria Little · Shaun Cruickshank

### 9. Footer / Contact (latar hijau tua `#0F483F`)
**Kiri:** badge "Contact Us" (outline putih) + judul putih "Let's Find Your Perfect Property" + paragraf putih 70%
**Kanan:** form grid 2 kolom, input **transparan** ber-border putih tipis, teks putih:
| Label | Isi |
|---|---|
| Your Name | Enter your full name |
| What Do You Want? | Buy a house *(dropdown)* |
| Your Preferred Location | New York *(dropdown)* |
| Your Desired Budget | $300,000 *(dropdown)* |
| Your Email Address | yourmail@gmail.com |
| Your Phone Number | +01 234 2846 345 |
Tombol tengah: "Get a Quote" (pill lime)

---

## Catatan Pengerjaan

- **Tahap 1 (selesai):** visual & layout saja — `index.html` (HTML + Tailwind CDN). Tanpa backend.
- **Revisi 1 (selesai):** full-bleed, font Poppins, hero diperbesar, services dirapikan, semua kartu pakai foto Unsplash.
- **Revisi 2 (selesai)** — referensi `section-about-ref.jpg`: bagian "Mitra Terpercaya" gaya solar-energy (badge, judul dengan kata disorot hijau, kolase 2 foto + kartu statistik putih), JavaScript interaktif penuh (pembuka, animasi scroll, angka berjalan, slideshow, FAQ akordeon, navbar sticky), search bar dihapus, kartu tambahan saat klik "Lihat Semua", tombol WhatsApp di 6 tempat, ulasan 9 kartu / 3 baris, konten Bahasa Indonesia.

### Revisi 3 (selesai) — referensi `card-layanan-ref.jpg`

1. **Logo diganti** → `assets/rumah_impian_logo_vector.svg` (vektor, lencana lime + rumah hijau tua). Dipakai di navbar (36px) dan layar pembuka (68px).
2. **Font nama merek "Rumah Impian" → Josefin Sans** (kelas `.brand`). Poppins tetap untuk teks lain. Terverifikasi termuat: `document.fonts.check('700 20px "Josefin Sans"')` = true.
3. **Foto hero tampil UTUH (tidak terpotong)** — `object-fit: contain`, kontainer diubah ke `aspect-[16/10]` yang **sama persis dengan rasio foto** (terukur: kontainer 1,600 = foto 1,600), jadi tidak ada ruang kosong di sisi.
4. **Titik navigasi (dots) kini berada DI ATAS gambar**, dengan alas gelap transparan + blur agar tetap terbaca di atas foto apa pun.
5. **Label `(Layanan Kami)` dan `(Tentang Kami)` dihapus.**
6. **Kartu layanan dirombak sesuai referensi:** satu wadah ber-border tipis berisi 4 kolom yang dipisah garis vertikal, **ikon garis polos tanpa kotak**, judul **HURUF BESAR** dua baris, deskripsi abu, semuanya **rata kiri**. Isi kartu diubah jadi alur kerja nyata: Konsultasi Kebutuhan · Kurasi Pilihan · Survei Lokasi · Berkas & Akad.
7. **Seluruh teks jadi Bahasa Indonesia** dengan gaya penulisan properti profesional. Judul properti dipendekkan, ditambah **baris subjudul** per properti (mis. "Hunian vertikal dengan panorama kota"), dan istilah diperbaiki (budget → anggaran, jual/beli → menjual/membeli).

### Revisi 4 (selesai) — referensi `navbar-ref.png`

1. **Font navbar dikunci** memakai tautan persis dari referensi:
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital@0;1&display=swap" rel="stylesheet">
   ```
   Dipisah dari tautan Poppins. Bobot teks merek disetel ke **600 (semibold)**.
2. **Logo diperbaiki jadi presisi.** Akar masalahnya ada di **file SVG itu sendiri**:
   ```
   viewBox asli ......... 0 0 295 152
   Gambar sebenarnya .... x 75–195, y 30–139  (hanya 120 × 109)
   Ruang kosong ......... kiri 75 · kanan 100 · atas 30 · bawah 13
   ```
   Gambar hanya menempati **41% lebar** viewBox. Akibatnya: logo tampak kecil, terlihat turun (atas 30 > bawah 13), dan berjarak jauh dari teks (100 unit kosong di kanan).
   **Perbaikan:** `viewBox` dipersempit ke batas gambar sebenarnya → `viewBox="73 28 124 113"`, `width/height` disesuaikan. Jalur (path) logo **tidak diubah sama sekali**.
3. **Jarak logo–teks dirapatkan** dari `gap-3` (12px) + ruang kosong SVG menjadi `gap-2` (8px) tanpa ruang kosong.
4. **Penyejajaran:** tinggi logo 26px, dinaikkan 1px (`-translate-y-[1px]`) agar pusatnya pas dengan pusat teks.

**Hasil terukur:**

| Ukuran | Nilai |
|---|---|
| Ukuran asli logo | 124 × 113 (rasio 1.097) |
| Tampil di navbar | 29 × 26 (rasio 1.097 — proporsional) |
| Pusat logo vs pusat teks | selisih **1.00 px** (sejajar) |
| Jarak logo ke teks | **8 px** (rapat) |
| Tinggi logo / tinggi teks | 26 / 30 px |
| Font merek | Josefin Sans 600 — termuat |

- **Bug yang ditemukan & diperbaiki:**
  1. Search bar pecah 2 baris — grid 4 kolom padahal 6 anak → `lg:grid-cols-[1fr_auto_1fr_auto_1fr_auto]`.
  2. Headline pecah 4 baris setelah ganti ke Poppins → kolom hero dilebarkan.
  3. 6 gambar kartu tidak termuat karena `loading="lazy"` → atribut dihapus.
  4. Overflow horizontal 15px — animasi geser mengeluarkan elemen dari layar → `overflow-x: clip` pada `html, body` (BUKAN `hidden`, karena merusak `position: sticky`).
  5. Rasio kontainer hero tidak sama dengan foto → foto terpotong. Diperbaiki: kontainer disetel ke rasio foto (16:10).
  6. **File logo punya ruang kosong besar di dalam viewBox** (75/100/30/13 unit) → logo kecil, turun, dan jauh dari teks. Diperbaiki dengan mempersempit viewBox.

### Berkas penting

| File | Keterangan |
|---|---|
| `assets/rumah_impian_logo_vector.svg` | Logo vektor emas (viewBox sudah dirapikan) |
| `assets/img/hero-1…5.jpg` | 5 foto slideshow, rasio 16:10 |
| `assets/img/kartu1…6.jpg` | 6 properti awal |
| `assets/img/extra-1…6.jpg` | 6 properti tambahan |
| `referensi/navbar-ref.png` | Referensi navbar (baru) |
| `referensi/card-layanan-ref.jpg` | Referensi kartu layanan |
| `referensi/section-about-ref.jpg` | Referensi bagian layanan |

- Belum dikerjakan: backend, halaman detail properti, peta lokasi, filter pencarian.




