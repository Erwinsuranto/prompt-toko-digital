# prompt-toko-digital


# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```

```
# 
```
PERBAIKAN FINAL UI — MENU HAMBURGER + WARNA KATEGORI

Repository:
zenolambee/toko-digital

JANGAN menyentuh repository toko-online.

Gunakan screenshot terbaru sebagai referensi visual utama.

PENTING:
Jangan membuat gambar baru.
Jangan mengubah fitur/functionality yang sudah berjalan.
Jangan redesign seluruh homepage.
Fokus HANYA pada:
1. menu hamburger
2. warna/styling kategori di bagian bawah homepage.

==================================================
1. PERBAIKI MENU HAMBURGER
==================================================

Saat hamburger menu dibuka, sekarang panel menu terlalu besar dan memanjang hampir memenuhi seluruh layar.

UBAH menjadi menu overlay yang lebih compact dan premium.

Target desain:

- panel menu berbentuk card/modal rounded besar
- tidak memenuhi seluruh tinggi layar
- posisi tetap nyaman di bawah header
- margin kiri dan kanan cukup
- border tipis
- shadow lembut
- background putih/light yang sedikit berbeda dari background halaman
- border-radius besar sekitar 24–30px
- padding lebih compact
- jangan membuat jarak antar menu terlalu tinggi

Struktur menu tetap:

Semua Produk
Paket Data
Semua
AI & Tools
Aplikasi
Streaming
Top Up
Cloud & Server
Lainnya
Hubungi Kami

JANGAN menghapus menu-menu tersebut.

Namun tampilkan dengan spacing yang lebih rapat dan rapi sehingga seluruh menu terlihat sebagai satu navigation card yang compact.

==================================================
MENU HEADER
==================================================

Bagian atas menu:

- tetap gunakan tombol X untuk menutup
- X harus berada di header kanan seperti sekarang
- jangan membuat header ikut berubah ukuran
- menu harus muncul sebagai overlay di bawah/di sekitar header
- halaman di belakang tetap terlihat sedikit
- jangan membuat menu mendorong layout homepage ke bawah

Overlay:

- gunakan background overlay/transparansi ringan jika diperlukan
- jangan terlalu gelap
- jangan sampai terlihat seperti halaman baru
- menu harus terasa seperti dropdown/mobile navigation premium

==================================================
MENU ITEM
==================================================

Setiap item menu:

- tinggi lebih kecil
- padding horizontal konsisten
- spacing vertikal compact
- typography tetap jelas
- gunakan hover/active state yang lembut
- icon hanya jika memang sudah ada
- jangan menambahkan icon secara berlebihan

Untuk item "Paket Data":
- boleh diberi icon yang sesuai
- tetap terlihat sebagai menu utama

"Hubungi Kami":
- tetap berada di bagian paling bawah
- gunakan aksen hijau yang sesuai dengan tombol WhatsApp/CTA
- pisahkan dengan divider tipis

==================================================
2. PERBAIKI WARNA KATEGORI HOMEPAGE
==================================================

Kategori di bagian bawah homepage saat ini terlalu putih/plain.

Struktur kategori JANGAN diubah.

Tetap pertahankan kategori:

- Paket Data
- AI & Tools
- Aplikasi
- Streaming
- Top Up
- Cloud & Server
- Lainnya

Buat category cards lebih hidup dan sesuai dengan desain Digital Cell.

Gunakan pendekatan:

- background card putih/light
- border lembut
- setiap kategori memiliki aksen warna/icon yang berbeda
- warna tetap soft/premium, jangan terlalu mencolok
- gunakan warna yang harmonis dengan brand biru Digital Cell

Contoh arah warna:

Paket Data:
aksen hijau/teal

AI & Tools:
aksen biru

Aplikasi:
aksen ungu

Streaming:
aksen merah/coral

Top Up:
aksen orange

Cloud & Server:
aksen cyan/blue

Lainnya:
aksen abu-abu/indigo

JANGAN menggunakan warna background yang terlalu terang/neon.

==================================================
CATEGORY CARD
==================================================

Buat category card:

- rounded sekitar 18–22px
- border tipis
- background soft tint sesuai aksen kategori
- icon berada di dalam small rounded icon container
- nama kategori jelas
- visual hierarchy bagus
- ukuran compact
- tidak terlalu tinggi
- tidak membuat halaman menjadi terlalu panjang

Desktop/tablet:
gunakan grid yang rapi.

Mobile:
gunakan 2 kolom jika layout kategori memang berupa card grid.

Contoh:

[ Paket Data ] [ AI & Tools ]
[ Aplikasi   ] [ Streaming ]
[ Top Up     ] [ Cloud & Server ]
[ Lainnya    ]

Pastikan semua card memiliki tinggi yang konsisten.

==================================================
WARNA GLOBAL
==================================================

Kategori harus menyatu dengan:

- header putih
- background halaman biru sangat muda
- hero/banner biru
- tombol hijau WhatsApp
- product card putih

Jangan membuat kategori terlihat seperti section dari website berbeda.

Gunakan warna soft/pastel dengan saturation sedang.

==================================================
BORDER — WAJIB
==================================================

Semua card kategori WAJIB memiliki:

- border 1px solid yang sangat lembut
- border-radius konsisten
- shadow sangat ringan
- tidak boleh terlihat flat tanpa border

Menu hamburger juga WAJIB memiliki border tipis dan rounded corner.

Jangan menghilangkan border yang sudah bagus pada komponen lain.

==================================================
RESPONSIVE
==================================================

Pastikan:

Mobile:
- menu compact
- tidak keluar dari viewport
- tidak menyebabkan horizontal overflow
- kategori tetap nyaman disentuh
- 2 kolom kategori

Tablet:
- spacing menyesuaikan

Desktop:
- menu tidak menjadi terlalu besar
- kategori tetap proporsional

==================================================
JANGAN UBAH
==================================================

Jangan mengubah:

- header Digital Cell
- hero/banner
- product populer
- product card
- Paket Data page
- provider selector
- category selector Paket Data
- list paket
- WhatsApp order
- admin panel
- routing
- database
- API
- dark mode functionality
- bottom navigation

Jangan menghapus fitur apa pun.

==================================================
VALIDASI
==================================================

Setelah selesai:

npm run lint
npm run build

Jika ada error, perbaiki sampai bersih.

Kemudian:

git add .
git commit -m "fix: refine mobile menu and category styling"
git push origin main

Jangan force push.
Jangan reset repository.
Jangan menyentuh toko-online.

Setelah selesai laporkan:

- file yang diubah
- hasil lint
- hasil build
- commit hash
- status push

HASIL AKHIR YANG DIINGINKAN:

Menu hamburger = compact, premium, rounded, tidak memenuhi layar.

Kategori homepage = lebih berwarna, soft, modern, memiliki border, dan menyatu dengan desain Digital Cell.

Jangan melakukan perubahan lain di luar dua bagian tersebut.

```
# 
```
REVISI KECIL HALAMAN PAKET DATA — HAPUS TOMBOL "SEMUA"

Repository:
zenolambee/toko-digital

Jangan menyentuh repository toko-online.

JANGAN HAPUS FITUR PAKET DATA.
JANGAN REDESIGN HALAMAN.

Hanya lakukan perubahan berikut:

========================================
HAPUS 2 TOMBOL "SEMUA"
========================================

Pada halaman Paket Data, HAPUS tombol:

1. "Semua" pada bagian:
Pilih Provider

2. "Semua" pada bagian:
Pilih Kategori Paket

Kedua tombol tersebut benar-benar tidak perlu ditampilkan.

========================================
HASIL YANG DIINGINKAN
========================================

Pilih Provider

[ Telkomsel ] [ Indosat ] [ XL ] [ Tri ] [ AXIS ] ...

Tidak ada:
[ Semua ]

Kemudian:

Pilih Kategori Paket

[ Internet ] [ Unlimited ] [ Masa Aktif ] ...

Tidak ada:
[ Semua ]

========================================
PERILAKU DEFAULT
========================================

Karena pilihan "Semua" dihapus:

Saat halaman Paket Data dibuka:
- pilih provider pertama yang tersedia sebagai provider aktif/default
ATAU gunakan provider yang memang sudah dipilih dari navigasi sebelumnya jika tersedia.

Setelah provider dipilih:
- tampilkan kategori yang tersedia untuk provider tersebut.
- pilih kategori pertama sebagai kategori aktif/default jika diperlukan.

List paket langsung menampilkan paket sesuai provider + kategori aktif.

Jangan membuat filter "semua" tersembunyi di UI.

========================================
PROVIDER
========================================

Tetap gunakan horizontal scroll jika provider banyak.

Provider selected:
- border/accent biru
- background selected yang lembut
- text tetap jelas

Provider tidak selected:
- border tipis
- background putih/light
- text dark/gray

========================================
KATEGORI
========================================

Tetap gunakan horizontal scroll jika diperlukan.

Kategori selected:
- border/accent biru
- background selected lembut

Tidak ada tombol "Semua".

========================================
JANGAN UBAH BAGIAN LAIN
========================================

Pertahankan:

- Header Digital Cell
- ← Paket Data
- Provider selector
- Category selector
- Daftar Paket
- package card
- logo provider
- harga
- status OPEN
- status GANGGUAN
- border card
- bottom navigation
- dark mode
- WhatsApp order
- data Paket Data

Jangan menambahkan:
- input nomor HP
- tombol Kontak
- tombol Scan
- tombol Bantuan
- search
- menu tambahan

========================================
RESPONSIVE
========================================

Mobile:
Provider → horizontal scroll
Kategori → horizontal scroll
Daftar paket → vertical

Jangan sampai body mengalami horizontal overflow.

========================================
VALIDASI
========================================

Setelah perubahan:

npm run lint
npm run build

Perbaiki semua error.

Kemudian:

git add .
git commit -m "fix: remove all filters from package data"
git push origin main

Jangan force push.
Jangan reset.
Jangan menyentuh toko-online.

Laporkan:
- file yang diubah
- hasil lint
- hasil build
- commit hash
- status push

PERUBAHAN HANYA:
HAPUS DUA TOMBOL "SEMUA" YANG DILINGKARI.

Jangan mengubah desain lainnya.
```
# 
```
PERBAIKI HALAMAN PAKET DATA — SEDERHANAKAN TOTAL

Repository:
zenolambee/toko-digital

Jangan menyentuh repository toko-online.

PENTING:
JANGAN HAPUS FITUR PAKET DATA.

Yang dilakukan adalah MENYEDERHANAKAN UI halaman Paket Data.

========================================
STRUKTUR FINAL
========================================

Halaman Paket Data hanya terdiri dari:

1. Provider
2. Kategori Paket
3. List Paket

Urutannya:

Paket Data
↓
Pilih Provider
↓
Pilih Kategori Paket
↓
Daftar Paket

========================================
HAPUS ELEMEN YANG TIDAK DIPERLUKAN
========================================

Hapus dari halaman Paket Data:

- input nomor HP
- tampilan nomor HP
- tombol Kontak
- tombol Scan
- tombol Bantuan
- search button khusus referensi
- list/grid/image button
- card tambahan
- banner tambahan
- informasi yang tidak berhubungan dengan pemilihan paket
- elemen UI besar dari desain referensi provider

Jangan mengganti dengan elemen baru yang tidak diperlukan.

========================================
HEADER
========================================

Tetap gunakan header website Digital Cell yang sudah ada.

Di bawah header cukup:

← Paket Data

Buat compact dan rapi.

Jangan membuat header halaman terlalu tinggi.

========================================
1. PROVIDER
========================================

Tampilkan:

Pilih Provider

Contoh:

[ Semua ] [ Telkomsel ] [ Indosat ] [ XL ] [ Tri ] [ AXIS ]

Provider selector boleh horizontal scroll.

Jangan membuat card provider besar.

Provider yang dipilih harus terlihat jelas dengan border/accent.

========================================
2. KATEGORI
========================================

Di bawah Provider:

Pilih Kategori Paket

Contoh:

[ Semua ] [ Internet ] [ Combo ] [ Unlimited ] [ Masa Aktif ]

Kategori juga boleh horizontal scroll.

Kategori mengikuti provider yang dipilih.

========================================
3. LIST PAKET
========================================

Di bawah kategori:

Daftar Paket

Gunakan card/list compact.

Contoh:

┌────────────────────────────────────┐
│  [LOGO]  3GB All Jaringan 28 Hari │
│          Rp 22.270          OPEN   │
└────────────────────────────────────┘

┌────────────────────────────────────┐
│  [LOGO]  Happy 7GB 28 Hari        │
│          Rp 30.198          OPEN   │
└────────────────────────────────────┘

┌────────────────────────────────────┐
│  [LOGO]  Happy 4,5GB 28 Hari      │
│          Rp 25.420      GANGGUAN   │
└────────────────────────────────────┘

Card harus:

- compact
- border halus
- radius sekitar 18–22px
- shadow sangat lembut
- logo kecil
- nama paket jelas
- harga menonjol
- status compact

========================================
4. NOMOR HP
========================================

JANGAN tampilkan nomor HP di halaman ini.

Tidak boleh ada:

- input nomor
- nomor tujuan
- form nomor
- card nomor

Nomor/provider tujuan diproses pada flow order berikutnya jika diperlukan.

========================================
5. BORDER
========================================

WAJIB mempertahankan border.

Provider selector:
- border tipis
- selected menggunakan accent biru
- radius pill

Kategori:
- border tipis
- selected menggunakan accent biru
- radius pill

Package card:
- border tipis abu/biru muda
- radius 18–22px
- shadow lembut

Status GANGGUAN:
- border merah muda/transparan
- badge merah muda

Status OPEN:
- border normal
- badge hijau muda

Jangan menggunakan border hitam tebal.

========================================
6. MOBILE
========================================

Prioritas mobile.

Layout:

Header
↓
Paket Data
↓
Pilih Provider
[ provider horizontal scroll ]
↓
Pilih Kategori Paket
[ kategori horizontal scroll ]
↓
Daftar Paket
[ package ]
[ package ]
[ package ]
[ package ]

Hanya provider dan kategori yang boleh horizontal scroll.

List paket WAJIB vertical.

Tidak boleh body horizontal overflow.

========================================
7. JANGAN UBAH HOMEPAGE
========================================

Homepage yang sekarang sudah benar.

Jangan mengubah:

- Header homepage
- Kategori Pilihan
- Hero banner
- Produk Populer
- Product slider 2 card
- Bottom navigation
- dark mode
- product card existing
- WhatsApp order existing

Hanya perbaiki halaman Paket Data.

========================================
8. DATA DAN FILTER
========================================

Pertahankan sistem data Paket Data yang sudah dibuat.

Provider → memfilter paket.

Kategori → memfilter paket.

Contoh:

Provider:
Tri

Kategori:
Internet

Maka hanya tampil paket:
Tri + Internet.

Jangan menghapus data Paket Data.

========================================
9. RESPONSIVE
========================================

Test:

360px
375px
390px
412px
430px
768px
1024px
1280px+

Pastikan tidak ada:

- overflow
- card terpotong
- text terpotong
- badge keluar card
- logo rusak
- horizontal body scroll

========================================
10. VALIDASI
========================================

Setelah perubahan:

npm run lint
npm run build

Perbaiki semua error.

Kemudian:

git status
git add .
git commit -m "fix: simplify data package page"
git push origin main

Jangan force push.
Jangan reset.
Jangan menyentuh toko-online.

LAPORKAN:

- file yang diubah
- elemen yang dihapus dari UI
- hasil lint
- hasil build
- commit hash
- status push

HASIL FINAL:

┌──────────────────────────────┐
│ ← Paket Data                 │
│                              │
│ Pilih Provider               │
│ [Semua] [Telkomsel] [Tri] → │
│                              │
│ Pilih Kategori Paket         │
│ [Semua] [Internet] [Combo] → │
│                              │
│ Daftar Paket                 │
│                              │
│ ┌──────────────────────────┐ │
│ │ Logo  Paket 3GB          │ │
│ │       Rp22.270    OPEN   │ │
│ └──────────────────────────┘ │
│                              │
│ ┌──────────────────────────┐ │
│ │ Logo  Paket 7GB          │ │
│ │       Rp30.198    OPEN   │ │
│ └──────────────────────────┘ │
└──────────────────────────────┘

Sederhana.
Compact.
Tidak ada nomor HP.
Tidak ada Kontak/Scan/Bantuan.
Fokus hanya PROVIDER → KATEGORI → LIST PAKET.
```
# 
```
IMPLEMENTASI FITUR PAKET DATA — TOKO-DIGITAL

Repository:
zenolambee/toko-digital

Branch:
main

KERJAKAN LANGSUNG DI REPOSITORY INI.

Jangan menyentuh repository toko-online.

==================================================
TUJUAN
==================================================

Tambahkan halaman/fitur khusus "Paket Data" dengan alur:

PAKET DATA
↓
PILIH PROVIDER
↓
PILIH KATEGORI PAKET
↓
LIST PAKET

PENTING:
Nomor HP TIDAK ditampilkan dan TIDAK diinput pada halaman Paket Data.

Nomor tujuan/provider sudah menjadi bagian dari proses berikutnya dan tidak boleh membuat halaman katalog Paket Data menjadi rumit.

==================================================
1. DESAIN HALAMAN
==================================================

Gunakan bahasa visual yang konsisten dengan desain Digital Cell yang sekarang:

- background very light blue/off-white
- card putih
- border tipis
- border-radius besar
- shadow sangat lembut
- typography modern
- warna utama biru Digital Cell
- spacing rapi
- mobile-first
- responsive

Jangan membuat desain yang terlihat seperti aplikasi provider asli.
Tetap harus terasa sebagai bagian dari website toko-digital.

==================================================
2. HEADER
==================================================

Buat header halaman:

←  Paket Data

Back button kembali ke halaman sebelumnya/home.

Jangan membuat header terlalu tinggi.

Tetap gunakan style header yang konsisten dengan website existing.

==================================================
3. PROVIDER
==================================================

Bagian pertama:

Pilih Provider

Tampilkan provider sebagai horizontal scroll/chips atau compact cards.

Contoh:

[ Semua ]
[ Telkomsel ]
[ Indosat ]
[ XL ]
[ Tri ]
[ AXIS ]
[ Smartfren ]

Jangan membuat provider card terlalu besar.

Setiap provider dapat memiliki:
- logo
- nama provider

Provider yang aktif harus memiliki visual selected yang jelas.

Contoh:

[ Telkomsel ] ← selected
[ Indosat ]
[ XL ]
[ Tri ]

Jangan menggunakan warna terlalu mencolok.
Gunakan warna brand provider hanya sebagai aksen seperlunya.

==================================================
4. KATEGORI PAKET
==================================================

Setelah provider:

Pilih Kategori Paket

Contoh:

[ Semua ]
[ Internet ]
[ Combo ]
[ Unlimited ]
[ Masa Aktif ]

Kategori harus mengikuti provider yang dipilih.

Jika provider memiliki kategori berbeda, tampilkan kategori yang tersedia untuk provider tersebut.

Kategori juga dapat horizontal scroll jika jumlahnya banyak.

Jangan membuat kategori menjadi grid besar.

==================================================
5. LIST PAKET
==================================================

Setelah kategori:

Daftar Paket

Gunakan LIST CARD COMPACT.

Jangan menggunakan product card besar seperti Produk Populer.

Referensi visual:

┌────────────────────────────────────┐
│ [LOGO]  3GB All Jaringan 28 Hari  │
│         Rp 22.270          OPEN    │
└────────────────────────────────────┘

┌────────────────────────────────────┐
│ [LOGO]  Happy 4,5GB 28 Hari       │
│         Rp 25.420       GANGGUAN  │
└────────────────────────────────────┘

┌────────────────────────────────────┐
│ [LOGO]  Happy 7GB 28 Hari         │
│         Rp 30.198          OPEN    │
└────────────────────────────────────┘

Struktur setiap item:

[Logo Provider]

Nama Paket
Harga

Status

==================================================
6. STATUS PAKET
==================================================

Status minimal:

OPEN
GANGGUAN

OPEN:
- badge hijau muda
- text hijau

GANGGUAN:
- badge merah muda
- text merah
- card boleh memiliki border merah sangat tipis/halus

Contoh:

OPEN

GANGGUAN

Jangan menggunakan warna merah terlalu kuat sehingga merusak desain.

==================================================
7. INFORMASI PAKET
==================================================

Data paket harus mendukung:

- id
- provider
- category
- name
- quota
- validity
- price
- status
- logo/provider reference
- description optional
- active
- sort/order

Contoh:

{
  provider: "tri",
  category: "internet",
  name: "Happy 7GB 28 Hari",
  quota: "7GB",
  validity: "28 Hari",
  price: 30198,
  status: "OPEN",
  active: true
}

Jangan hardcode seluruh paket langsung di component UI jika project sudah memiliki sistem data/product.

Gunakan struktur data yang mudah dikembangkan.

==================================================
8. FILTER
==================================================

Interaksi:

Jika user memilih provider:
→ list paket hanya provider tersebut.

Jika user memilih kategori:
→ list paket hanya kategori tersebut.

Jika user memilih:

Provider:
Tri

Kategori:
Internet

Maka hanya tampil paket:

Tri + Internet.

Jika tidak ada paket:

Tampilkan empty state yang rapi:

"Tidak ada paket tersedia"

Jangan tampilkan card kosong.

==================================================
9. KLIK PAKET
==================================================

Setiap paket harus clickable.

Ketika user memilih paket:

buka detail/konfirmasi paket menggunakan flow yang sudah tersedia di project jika ada.

Jangan membuat checkout/payment system baru.

Website ini tetap katalog/order via WhatsApp.

Jika flow WhatsApp sudah tersedia:
gunakan flow tersebut.

Jangan mengganti sistem WhatsApp existing.

==================================================
10. NOMOR HP
==================================================

PENTING SEKALI:

JANGAN menambahkan:

- input nomor HP
- field nomor HP
- nomor tujuan di halaman list
- form nomor di halaman provider
- card nomor HP

Halaman ini hanya katalog/pemilihan paket.

Nomor HP merupakan proses terpisah setelah paket dipilih jika memang diperlukan oleh flow order.

==================================================
11. MOBILE UI
==================================================

Prioritas utama mobile.

Pada mobile:

Header
↓
Pilih Provider
↓
Provider chips horizontal
↓
Pilih Kategori Paket
↓
Kategori chips horizontal
↓
Daftar Paket
↓
List card compact

Tidak boleh ada horizontal overflow pada BODY.

Yang boleh horizontal scroll hanya:

- provider selector
- category selector

List paket tetap vertical.

==================================================
12. UKURAN CARD
==================================================

Jangan membuat card paket tinggi.

Target:
- compact
- mudah discan
- satu card sekitar 80–110px tergantung isi
- logo kecil tetapi jelas
- nama paket mudah dibaca
- harga menonjol
- status badge compact

Jangan membuat card seperti ProductCard Produk Populer.

==================================================
13. BORDER — WAJIB
==================================================

Semua card Paket Data harus mempunyai border halus.

Normal:

border tipis abu/biru muda
border-radius sekitar 18–22px
shadow sangat lembut

OPEN:
border normal

GANGGUAN:
border merah muda/merah transparan

Provider selected:
gunakan border/accent biru yang jelas.

Kategori selected:
gunakan border/accent biru yang jelas.

Jangan menggunakan border hitam tebal.

==================================================
14. DESKTOP
==================================================

Desktop tetap responsive.

Jangan membuat list paket terlalu lebar.

Gunakan max-width yang nyaman.

Contoh konsep:

┌─────────────────────────────────────┐
│             Paket Data              │
│                                     │
│ Provider                            │
│ [Telkomsel] [Indosat] [XL] [Tri]  │
│                                     │
│ Kategori                            │
│ [Internet] [Combo] [Unlimited]     │
│                                     │
│ Daftar Paket                        │
│ ┌───────────────────────────────┐   │
│ │ package                       │   │
│ └───────────────────────────────┘   │
└─────────────────────────────────────┘

Jangan membuat 4 kolom card besar.

==================================================
15. INTEGRASI DENGAN ADMIN
==================================================

Audit admin panel existing.

Jika project sudah memiliki sistem product management:

Tambahkan kemampuan mengelola Paket Data tanpa merusak produk existing.

Admin harus dapat membuat/edit:

- Provider
- Kategori Paket
- Nama Paket
- Kuota
- Masa Aktif
- Harga
- Status OPEN/GANGGUAN
- Active/Inactive
- Urutan

Jangan merusak produk digital yang sudah ada.

Jika arsitektur admin saat ini belum mendukung struktur tersebut, buat modul terpisah yang modular.

Jangan memasukkan seluruh logic Paket Data ke satu file besar.

==================================================
16. ARSITEKTUR
==================================================

Buat modular.

Pisahkan jika diperlukan:

- data/model Paket Data
- provider
- category
- package list
- package card
- provider selector
- category selector

Jangan membuat satu component raksasa.

Ikuti pola/arsitektur existing repository jika sudah tersedia.

==================================================
17. HOMEPAGE
==================================================

Jangan merombak homepage yang sekarang.

Pertahankan:

- Header
- Kategori Pilihan
- Hero banner compact
- Produk Populer
- Product slider 2 card
- Bottom navigation
- Dark mode
- styling existing

Tambahkan akses ke Paket Data secara natural melalui kategori/menu yang sudah tersedia.

==================================================
18. DATA AWAL
==================================================

Jika belum ada backend/database khusus untuk Paket Data, buat sample seed/mock data yang realistis untuk development.

Minimal contoh:

Tri:
- 3GB All Jaringan 28 Hari
- Happy 4,5GB 28 Hari
- Happy 7GB 28 Hari
- Happy 9GB 28 Hari
- Happy 10GB 28 Hari

Tambahkan beberapa contoh provider lain untuk menguji filtering.

Status:
- sebagian OPEN
- minimal satu GANGGUAN

Jangan mengklaim data tersebut sebagai harga real-time.

==================================================
19. DARK MODE
==================================================

Pastikan halaman Paket Data mengikuti dark mode existing.

Jangan hanya membalik background.

Perhatikan:

- card
- border
- text
- provider chip
- category chip
- status badge
- empty state

==================================================
20. RESPONSIVE TEST
==================================================

Wajib test:

360px
375px
390px
412px
430px
768px
1024px
1280px+

Pastikan:

- tidak ada body horizontal overflow
- provider selector dapat swipe
- category selector dapat swipe
- package list tetap vertical
- text tidak terpotong
- harga tidak keluar card
- status badge tidak keluar card
- logo tidak pecah
- spacing konsisten

==================================================
21. CODE QUALITY
==================================================

Sebelum implementasi:
audit struktur repository terlebih dahulu.

Jangan membuat duplicate component/page.

Gunakan component existing jika memang cocok.

Jangan menghapus fitur existing.

Setelah implementasi:

npm run lint
npm run build

Perbaiki SEMUA error yang muncul.

==================================================
22. GIT
==================================================

Setelah semuanya selesai dan lint/build berhasil:

git status

Pastikan hanya perubahan repository:

zenolambee/toko-digital

Kemudian:

git add .
git commit -m "feat: add data package catalog"
git push origin main

Jangan:
- force push
- reset --hard
- menghapus commit lama
- mengubah toko-online
- mengubah repository lain

==================================================
23. LAPORAN AKHIR
==================================================

Setelah push berhasil, laporkan:

1. File yang dibuat/diubah
2. Fitur Paket Data yang dibuat
3. Provider filtering
4. Category filtering
5. Package list
6. Status OPEN/GANGGUAN
7. Admin integration
8. Responsive test
9. npm run lint → hasil
10. npm run build → hasil
11. Commit hash
12. Push → berhasil/gagal

FOKUS UTAMA:

Paket Data harus terasa sederhana:

PILIH PROVIDER
↓
PILIH KATEGORI
↓
LIHAT LIST PAKET
↓
PILIH PAKET
↓
LANJUT KE FLOW ORDER

TIDAK ADA INPUT NOMOR HP DI HALAMAN INI.

Jangan membuat desain terlalu besar.
Gunakan card paket compact dengan border halus seperti referensi.
```

# 
```
PERBAIKAN HOMEPAGE TOKO-DIGITAL — KECILKAN HERO BANNER

Kerjakan HANYA di repository:
zenolambee/toko-digital

Jangan menyentuh toko-online.

Tampilan terbaru sudah cukup bagus. JANGAN melakukan redesign besar.

Fokus utama perubahan kali ini:
HERO/BANNER biru terlalu besar dan terlalu tinggi di mobile.

================================
TARGET LAYOUT
================================

Urutan tetap:

HEADER
↓
KATEGORI PILIHAN
↓
HERO BANNER COMPACT
↓
PRODUK POPULER
↓
PRODUCT SLIDER 2 CARD
↓
SECTION LAINNYA
↓
BOTTOM NAVIGATION

Jangan mengubah urutan tersebut.

================================
1. HERO BANNER HARUS LEBIH PENDEK
================================

Banner saat ini mengambil terlalu banyak tinggi layar.

Kecilkan secara signifikan.

Target mobile:
- banner tetap lebar mengikuti container
- tetapi tinggi dibuat compact
- jangan memenuhi hampir seluruh layar
- jangan terlihat seperti poster vertikal
- lebih menyerupai promotional banner horizontal/landscape

Gunakan rasio visual sekitar 16:9 sebagai target utama.

PENTING:
JANGAN menggunakan rasio 9:16.
JANGAN membuat banner portrait.
JANGAN membuat banner sangat tinggi.

Target konsep:

┌──────────────────────────────────────────┐
│                                          │
│  Solusi Digital       [PHONE / ICON]    │
│  Dalam Genggaman                         │
│                                          │
│  [Belanja Sekarang] [Hubungi Kami]      │
│                                          │
└──────────────────────────────────────────┘

Bukan:

┌───────────────────┐
│                   │
│       HERO        │
│                   │
│                   │
│                   │
│                   │
│                   │
│                   │
└───────────────────┘

================================
2. CONTENT HERO
================================

Tetap pertahankan:
- "Siap order via WhatsApp"
- "Solusi Digital"
- "Dalam Genggaman"
- deskripsi
- tombol "Belanja Sekarang"
- tombol "Hubungi Kami"
- ilustrasi phone/D
- pagination indicator

Tetapi semua elemen harus dipadatkan agar muat dalam banner yang lebih pendek.

Jangan menghapus informasi penting.

================================
3. HERO RESPONSIVE MOBILE
================================

Untuk mobile:

Hero width:
- hampir penuh mengikuti container
- margin kiri/kanan tetap konsisten

Hero height:
- sekitar 56.25% dari lebar container (16:9)
- boleh sedikit fleksibel jika isi membutuhkan ruang
- tetapi tetap harus terasa compact

Jangan membuat fixed height yang sangat besar.

Gunakan aspect-ratio jika cocok dengan struktur existing.

Contoh konsep:

aspect-ratio: 16 / 9;

Namun jangan memaksakan aspect-ratio jika menyebabkan content overflow.

================================
4. POSISI ELEMEN HERO
================================

Atur ulang internal hero agar efisien.

Desktop/tablet:
- text di kiri
- illustration di kanan

Mobile:
- text tetap dominan
- illustration diperkecil dan ditempatkan di sisi kanan/bawah sesuai kebutuhan
- tombol tetap terlihat
- tidak boleh ada elemen keluar dari card

Semua content harus berada di dalam border-radius hero.

================================
5. TYPOGRAPHY HERO
================================

Karena tinggi banner dikurangi:

perkecil typography secara responsive.

Heading:
"Solusi Digital
Dalam Genggaman"

Tetap menjadi focal point tetapi jangan terlalu besar.

Deskripsi:
lebih kecil dan compact.

Badge:
lebih kecil.

Buttons:
lebih pendek dan compact.

Pagination:
tetap berada di bagian bawah hero tetapi jangan memakan banyak ruang.

================================
6. BUTTON
================================

Jangan membuat dua tombol terlalu tinggi.

Gunakan button height yang compact.

Contoh:

[ Belanja Sekarang → ] [ WhatsApp Hubungi Kami ]

Desktop:
boleh lebih besar.

Mobile:
lebih compact agar tidak menyebabkan hero menjadi tinggi.

================================
7. BORDER HERO — WAJIB
================================

Hero harus tetap memiliki batas visual yang jelas.

Gunakan:

- border tipis
- warna border biru/transparan yang halus
- border-radius besar
- shadow lembut

Contoh konsep:

border: 1px solid rgba(...);
box-shadow: 0 10px 30px rgba(...);

Jangan menggunakan border hitam.

Border harus mengelilingi seluruh banner.

Tujuannya agar banner terlihat seperti premium card dan tidak menyatu dengan background.

================================
8. JARAK ANTAR SECTION
================================

Setelah Hero selesai, jangan beri ruang kosong terlalu besar.

Hero
↓
spacing compact
↓
🔥 Produk Populer

Produk Populer harus terlihat lebih cepat setelah hero.

Jangan membuat user harus scroll jauh hanya untuk melihat Produk Populer.

================================
9. BACKGROUND
================================

Pertahankan background halaman very light blue/off-white.

Hero tetap menggunakan gradient biru Digital Cell.

Jangan membuat background halaman menjadi putih polos.

================================
10. JANGAN RUSAK BAGIAN YANG SUDAH BENAR
================================

Jangan mengubah secara tidak perlu:

- Header
- Kategori Pilihan
- warna kategori yang sudah diperbaiki
- Produk Populer
- product slider
- 2 card mobile
- swipe horizontal
- bottom navigation
- Admin
- data produk
- WhatsApp order
- dark mode

Fokus hanya:
HERO BANNER + spacing yang berhubungan langsung dengannya.

================================
11. PRODUCT POPULER
================================

Pastikan setelah hero diperkecil:

🔥 Produk Populer

tetap muncul dengan posisi yang rapi.

Product slider tetap:
- 2 card terlihat di mobile
- horizontal swipe
- compact
- border halus
- tidak ada body horizontal overflow

Jangan mengubah implementasi slider kecuali diperlukan untuk menyesuaikan spacing.

================================
12. MOBILE PRIORITY
================================

Prioritas pengujian:
Android mobile.

Periksa minimal viewport:
- 360px
- 375px
- 390px
- 412px
- 430px

Pastikan hero:
- tidak overflow
- tidak memotong text
- tidak memotong tombol
- tidak memotong ilustrasi
- tidak terlalu tinggi
- tidak terlalu sempit

================================
13. DESKTOP / TABLET
================================

Jangan membuat desktop menjadi terlalu kecil.

Gunakan responsive behavior:

Mobile:
16:9 / compact

Tablet:
sedikit lebih besar jika diperlukan

Desktop:
banner tetap landscape dan proporsional

Jangan menggunakan satu fixed height untuk semua device.

================================
14. AUDIT CODE
================================

Sebelum mengedit:
- cari component Hero/Banner existing
- cari CSS hero
- cari responsive breakpoint
- cari aspect-ratio/min-height/height yang membuat hero terlalu tinggi

Perbaiki source existing.

Jangan membuat duplicate Hero component.

================================
15. VALIDASI
================================

Setelah selesai:

npm run lint
npm run build

Perbaiki semua error.

Kemudian cek:
- mobile hero compact
- hero sekitar 16:9
- tidak overflow
- text tidak terpotong
- button tidak terpotong
- illustration tidak terpotong
- border hero terlihat
- Produk Populer muncul lebih dekat setelah hero
- product slider tetap 2 card mobile
- body tidak horizontal overflow

================================
16. GIT
================================

Pastikan:

repository:
zenolambee/toko-digital

branch:
main

Jangan menyentuh toko-online.

Jangan:
- force push
- reset --hard
- menghapus commit existing
- mengubah repository lain

Setelah lint dan build berhasil:

git add .
git commit -m "fix: compact responsive hero banner"
git push origin main

Laporkan:
- file yang diubah
- hasil lint
- hasil build
- commit hash
- hasil push

HASIL AKHIR YANG DIINGINKAN:

Header
↓
Kategori Pilihan
↓
┌──────────────────────────────┐
│       HERO 16:9 COMPACT      │
│  text + buttons + illustration│
└──────────────────────────────┘
↓
🔥 Produk Populer
↓
[ Product 1 ] [ Product 2 ]
      ← swipe →
↓
section berikutnya

Fokus utama:
BANNER JANGAN LAGI TERLALU TINGGI.

Buat terasa seperti promotional banner marketplace modern, bukan banner portrait.
```
# 
```
UPDATE UI TOKO-DIGITAL — PERBAIKI WARNA KATEGORI PILIHAN

Kerjakan HANYA di repository zenolambee/toko-digital.
Jangan menyentuh toko-online.

Saya sudah cek tampilan terbaru.

POSISI "Kategori Pilihan" SUDAH BENAR.
Jangan mengubah posisi atau urutannya.

Yang perlu diperbaiki hanya visual/styling Kategori Pilihan agar lebih menyatu dengan desain Digital Cell.

================================
TARGET DESAIN
================================

Kategori Pilihan harus terlihat sebagai bagian dari UI Digital Cell yang sama dengan Header, Hero, dan Product Card.

Saat ini warna category chip terlalu putih/abu-abu dan terasa seperti komponen terpisah.

Buat lebih modern, soft, premium, dan menggunakan aksen biru Digital Cell.

================================
1. CATEGORY CONTAINER
================================

Pertahankan container Kategori Pilihan seperti sekarang:

- background putih
- rounded corner besar
- border tipis
- shadow sangat lembut

Tetapi berikan sedikit nuansa biru agar tidak terlihat seperti putih polos.

Gunakan:
- putih sebagai base
- very light blue sebagai aksen
- border biru sangat tipis/transparan

Jangan menggunakan abu-abu dominan.

Container harus tetap kontras dengan background halaman.

================================
2. CATEGORY CHIP
================================

Ubah chip kategori agar lebih sesuai dengan warna utama Digital Cell.

Jangan gunakan chip putih polos dengan border abu-abu seperti tampilan sekarang.

Gunakan konsep:

ACTIVE:
background: very light blue / soft blue
border: blue tipis
text: Digital Cell blue
icon: blue

INACTIVE:
background: very light blue-gray / hampir putih
border: soft blue-gray
text: dark navy/blue-gray
icon: blue-gray

Contoh visual:

[ Semua ] [ 💡 AI & Tools ] [ 📖 Aplikasi ] [ ... ]

Bukan:

[ Semua ] [ AI & Tools ] [ Aplikasi ]
semuanya putih + border abu-abu.

================================
3. ACTIVE CATEGORY
================================

Kategori yang aktif harus langsung terlihat.

Gunakan:
- background biru muda
- border biru lembut
- text biru
- icon biru
- sedikit shadow/glow jika diperlukan

Jangan gunakan biru terlalu gelap.

Tetap gunakan warna biru yang konsisten dengan Hero Digital Cell.

================================
4. ICON
================================

Icon kategori harus memiliki warna yang konsisten.

Jangan menggunakan kombinasi warna yang terlalu banyak seperti:
hijau + ungu + orange + merah
untuk chip utama.

Gunakan warna utama Digital Cell sebagai dasar.

Jika ingin memberikan sedikit variasi warna, gunakan hanya sebagai aksen yang sangat lembut.

Prioritas:
BLUE > soft blue > navy

================================
5. TYPOGRAPHY
================================

Judul:

Kategori Pilihan

harus tetap tegas dan konsisten dengan heading Produk Populer.

Gunakan:
- dark navy
- font weight 700/800
- ukuran responsive
- jangan terlalu besar

" Lihat semua → "
gunakan Digital Cell blue.

================================
6. CATEGORY SCROLL
================================

Mobile tetap:

horizontal scroll untuk chip kategori.

Contoh:

[Semua] [AI & Tools] [Aplikasi] [Streaming] →

User dapat swipe ke samping.

Tetapi:
- scrollbar hidden
- tidak membuat seluruh body horizontal
- tidak menyebabkan layout overflow
- spacing antar chip konsisten

================================
7. BORDER — WAJIB DIPERHATIKAN
================================

Container kategori:
- border tipis
- soft blue/neutral
- rounded besar
- shadow lembut

Chip:
- border tipis
- active border lebih terlihat
- inactive border lebih soft

Jangan:
- border hitam
- border abu-abu tebal
- outline terlalu kontras

Border harus membantu memisahkan elemen dari background, bukan menjadi elemen utama.

================================
8. KONSISTENSI WARNA
================================

Gunakan color system yang sama dengan Hero dan UI Digital Cell.

Primary:
Digital Cell blue

Background:
very light blue / off-white

Card:
white

Text:
dark navy

Secondary text:
slate blue-gray

Border:
soft blue-gray

Hindari warna yang membuat kategori terlihat seperti aplikasi lain.

================================
9. JANGAN UBAH BAGIAN LAIN
================================

Jangan mengubah:
- posisi Kategori Pilihan
- Hero
- Product Slider
- Product Card
- Header
- Bottom Navigation
- Admin Panel
- data produk
- fungsi order WhatsApp

Khusus perbaiki styling Kategori Pilihan.

================================
10. RESPONSIVE
================================

Pastikan tampilan bagus pada:
- Android mobile
- tablet
- desktop

Mobile adalah prioritas.

Kategori tetap compact dan tidak mengambil tinggi berlebihan.

================================
11. VALIDASI
================================

Setelah perubahan:

npm run lint
npm run build

Perbaiki semua error.

Kemudian:

git status
git diff

Pastikan repository:
zenolambee/toko-digital

Branch:
main

Jangan force push.
Jangan reset --hard.
Jangan menyentuh toko-online.

Commit:

style: refine category selection colors

Push:

git push origin main

Laporkan:
- file yang diubah
- hasil lint
- hasil build
- commit hash
- hasil push

HASIL YANG DIINGINKAN:

Kategori Pilihan tetap di posisi sekarang,
tetapi tampilannya lebih menyatu dengan Digital Cell:

white/light-blue container
+
soft blue border
+
soft blue category chips
+
blue active state
+
dark navy text
+
Digital Cell blue accent

Jangan mengubah layout yang sekarang sudah benar.
Fokus hanya memperbaiki warna, border, shadow, icon, dan styling kategori.
```
# 
```
UPDATE UI TOKO-DIGITAL — DESAIN NOMOR 2

Kerjakan HANYA di repository:
zenolambee/toko-digital

Jangan menyentuh toko-online.

Gunakan desain nomor 2 sebagai acuan utama.

URUTAN HOMEPAGE:

1. Header
2. Kategori Pilihan
3. Hero Banner
4. Produk Populer
5. 2-card horizontal slider
6. Indicator slider
7. Section berikutnya
8. Bottom Navigation

================================
1. KATEGORI PILIHAN
================================

Kategori Pilihan berada DI ATAS Hero.

Buat sebagai section/card yang jelas terpisah dari background.

Style:
- background putih
- border tipis dan sangat lembut
- border-radius besar
- shadow sangat halus
- jangan terlalu terang sampai menyatu dengan background
- padding compact

Contoh:

┌─────────────────────────────────────┐
│ 🏷 Kategori Pilihan     Lihat semua │
│                                     │
│ [AI] [Streaming] [Game] [Cloud] ...│
└─────────────────────────────────────┘

Category chips boleh horizontal scroll di mobile.

================================
2. HERO
================================

Hero berada setelah Kategori Pilihan.

Gunakan hero existing yang sudah ada.

Hero harus:
- compact
- tidak terlalu tinggi
- border-radius besar
- memiliki border tipis transparan/putih
- shadow lembut
- tidak memenuhi hampir seluruh layar mobile
- tetap responsive

PENTING:
Hero jangan dibuat terlalu panjang/tinggi.

Gunakan rasio visual sekitar 6:9 atau proporsi compact yang setara untuk area mobile jika diperlukan.

================================
3. PRODUK POPULER
================================

Setelah Hero, tampilkan:

🔥 Produk Populer                 Lihat semua →
Produk pilihan paling laris

Kemudian product slider.

================================
4. PRODUCT SLIDER
================================

MOBILE WAJIB:

Tampilkan tepat 2 card produk secara berdampingan.

Contoh:

┌────────────┐  ┌────────────┐
│ Product 1  │  │ Product 2  │
│            │  │            │
│ detail     │  │ detail     │
│ harga      │  │ harga      │
│   Order    │  │   Order    │
└────────────┘  └────────────┘

User bisa swipe/geser ke kiri dan kanan.

Jangan membuat:
- 1 card full width
- 1 card memenuhi layar
- 4 card sekaligus
- product grid vertical pada section ini

Harus horizontal carousel.

Gunakan:
- overflow-x auto
- scroll-snap
- touch-friendly
- smooth scrolling
- scrollbar hidden

Body halaman tetap vertical scroll.

================================
5. BORDER CARD PRODUK — WAJIB
================================

Setiap product card HARUS mempunyai pemisah visual yang jelas dari background.

Gunakan:

- border 1px solid dengan warna yang sangat lembut
- border-radius sekitar 18–24px
- shadow lembut
- background putih

Contoh konsep:

border: 1px solid rgba(..., 0.08);
box-shadow: 0 8px 24px rgba(..., 0.06);

Jangan menggunakan border hitam atau border yang terlalu tebal.

Tujuannya supaya card terlihat premium dan jelas batasnya, tetapi tetap halus.

Border harus mengelilingi SELURUH card:
- image/visual
- badge
- nama
- deskripsi
- rating
- harga
- tombol Order

Jangan membuat border hanya pada bagian image.

================================
6. PRODUCT CARD
================================

Card harus compact.

Struktur:

[Badge]

[Product Visual]

Nama Produk

Kategori • Brand

Deskripsi singkat

⭐ Rating • Terjual

────────────

Mulai dari
Rp xxx.xxx          [Order]

Jangan ada whitespace besar.

Image/visual bagian atas jangan terlalu tinggi.

Harga dan tombol Order harus tetap terlihat tanpa membuat card menjadi sangat tinggi.

================================
7. PRODUCT IMAGE / VISUAL
================================

Pastikan tidak ada broken image.

Jangan memakai external image URL yang mudah gagal.

Jika product image tidak tersedia:
gunakan fallback visual yang rapi dari sistem existing.

Jangan menampilkan:
- broken image icon
- area putih kosong besar
- gambar yang overflow keluar card

================================
8. SLIDER INDICATOR
================================

Di bawah product slider:

● ○ ○

Active:
- biru
- sedikit lebih panjang

Inactive:
- abu-abu

Indicator jangan terlalu besar.

================================
9. SECTION BORDER
================================

Semua section/card utama yang menggunakan background putih harus memiliki pemisah visual dari background halaman.

Gunakan kombinasi:

- background putih
- border tipis
- soft shadow
- rounded corners

Jangan membuat background section terlalu putih/terang tanpa border karena akan menyatu dengan background biru muda.

Namun jangan memberikan border berat pada semua elemen kecil.

================================
10. BACKGROUND
================================

Background halaman:
- very light blue / off-white
- tidak terlalu putih
- cukup kontras dengan card putih

Tujuan:

BACKGROUND
   ↓
┌───────────────────────┐
│ WHITE CARD            │
│ dengan border halus   │
└───────────────────────┘

Bukan:

BACKGROUND PUTIH
┌───────────────────────┐
│ PUTIH                  │
└───────────────────────┘

================================
11. RESPONSIVE
================================

Mobile adalah prioritas.

Mobile:
- Kategori horizontal jika diperlukan
- Hero compact
- 2 product card horizontal
- swipe
- tidak ada body horizontal overflow

Tablet:
- sesuaikan ukuran card

Desktop:
- tetap modern
- slider dapat menampilkan beberapa card
- jangan merusak layout existing

================================
12. BODY OVERFLOW
================================

Pastikan horizontal scrolling hanya terjadi pada:
- category chips
- product carousel

Bukan pada seluruh halaman.

Header dan bottom navigation tidak boleh ikut bergeser horizontal.

================================
13. JANGAN RUSAK FITUR EXISTING
================================

Jangan menghapus:
- Admin
- product management
- category management
- order WhatsApp
- dark mode
- favorite
- navigation
- data produk
- fitur existing lainnya

Audit component existing terlebih dahulu.

Jangan membuat duplicate component jika sudah tersedia.

================================
14. VALIDASI
================================

Setelah selesai:

npm run lint
npm run build

Perbaiki semua error.

Pastikan:
- tidak ada TypeScript error
- tidak ada hydration error
- tidak ada broken import
- tidak ada broken image
- tidak ada horizontal body overflow
- slider bisa swipe
- 2 card terlihat di mobile
- border card terlihat halus
- kategori berada di atas Hero
- Hero berada di atas Produk Populer

================================
15. GIT
================================

Pastikan repository:

zenolambee/toko-digital

Branch:

main

Jangan menyentuh toko-online.

Jangan:
- force push
- reset --hard
- menghapus commit
- mengubah repository lain

Setelah semua lolos:

git add .
git commit -m "feat: refine storefront layout and product slider"
git push origin main

Laporkan:
- file yang diubah
- hasil lint
- hasil build
- commit hash
- hasil push

Fokus utama desain:
KATEGORI PILIHAN
↓
HERO COMPACT
↓
PRODUK POPULER
↓
2 CARD SLIDER
↓
INDICATOR
↓
SECTION BERIKUTNYA

Dengan border halus pada card dan section supaya tidak menyatu dengan background.
```
# 
```
KOREKSI UI — URUTAN KATEGORI & PRODUK POPULER

Kerjakan hanya di repository zenolambee/toko-digital.
Jangan menyentuh toko-online.

Koreksi prompt sebelumnya:

URUTAN YANG BENAR PADA HOMEPAGE MOBILE ADALAH:

Header
↓
Kategori Pilihan
↓
Produk Populer
↓
Product Slider
↓
Section berikutnya
↓
Bottom Navigation

Kategori Pilihan HARUS berada DI ATAS card Produk Populer.

Contoh layout:

┌─────────────────────────────────┐
│ 🏷 Kategori Pilihan             │
│                                 │
│ [AI & Tools] [Streaming] [Game] │
│ [Cloud] [Edu] [Semua]           │
└─────────────────────────────────┘

Produk Populer                    Lihat semua →
Produk pilihan paling laris

┌──────────────┐ ┌──────────────┐
│   Product 1  │ │   Product 2  │
│              │ │              │
│   detail     │ │   detail     │
│   harga      │ │   harga      │
│    Order     │ │    Order     │
└──────────────┘ └──────────────┘

← SWIPE HORIZONTAL →

             ● ○ ○

Kemudian baru section lainnya.

PENTING:
- Kategori Pilihan jangan dipindahkan ke bawah Produk Populer.
- Kategori Pilihan harus tetap di bagian atas card Produk Populer.
- Produk Populer tetap menggunakan horizontal slider.
- Mobile tetap menampilkan 2 card produk sekaligus.
- Card bisa swipe/geser horizontal.
- Halaman utama tetap vertical scrolling.
- Jangan sampai seluruh body ikut horizontal scrolling.
- Jangan mengubah header yang sudah bagus.
- Jangan merusak bottom navigation.
- Jangan merusak admin panel.

Untuk slider Produk Populer:
- 2 card terlihat pada mobile.
- card compact dan proporsional.
- horizontal touch scrolling.
- scroll-snap.
- scrollbar disembunyikan.
- pagination indicator di bawah card.
- jangan membuat 1 card full-width.
- jangan membuat card terlalu besar.
- jangan ada whitespace berlebihan.

Untuk Kategori Pilihan:
- section berada tepat sebelum Produk Populer.
- tampil sebagai card/section rounded dengan background putih atau sangat lembut.
- category chips dapat horizontal scroll di mobile.
- tetap compact agar tidak memakan terlalu banyak layar.

Audit implementation existing terlebih dahulu.
Gunakan component/data yang sudah ada.
Jangan membuat duplicate ProductCard atau duplicate section.

Setelah selesai:
- npm run lint
- npm run build
- perbaiki semua error
- git status
- pastikan repository zenolambee/toko-digital
- branch main
- jangan force push
- jangan reset --hard
- commit perubahan
- push ke origin/main

Jangan menyentuh toko-online.

Laporkan file yang diubah, hasil lint, build, commit hash, dan hasil push.
```
# 
```
Kita sekarang bekerja HANYA di repository toko-digital.

Saya sudah masuk ulang ke folder repository yang benar. Tolong jangan menyentuh repository/folder toko-online sama sekali.

Tugas kamu:

1. Pastikan current directory benar-benar repository toko-digital.
   - Jalankan pwd
   - Jalankan git remote -v
   - Pastikan remote mengarah ke repository GitHub zenolambee/toko-digital.
   - Jika ternyata bukan toko-digital, STOP dan laporkan, jangan mengubah repository lain.

2. Audit Git configuration repository ini:
   - git status
   - git branch --show-current
   - git log -5 --format='%h %an <%ae> %s'
   - git config user.name
   - git config user.email

3. Perbaiki masalah deployment Vercel yang diblokir karena commit terakhir menggunakan identitas:
   root@kenzonano1-0647ecaf-3287-vm...

   Gunakan identitas GitHub yang benar/terhubung dengan repository zenolambee/toko-digital.
   Prioritaskan mengambil identitas/email yang benar dari konfigurasi/commit GitHub sebelumnya atau akun GitHub yang tersedia di environment.
   JANGAN menggunakan email root@kenzonano... untuk commit.

4. Jangan mengubah source code hanya untuk membuat commit.
   Pertama audit apakah source code sudah bersih dan apakah ada perubahan yang memang perlu diperbaiki.

5. Jika repository sudah benar dan source code tidak perlu diubah, buat perubahan Git minimal yang aman untuk menghasilkan commit baru dengan author GitHub yang benar. Jangan merusak aplikasi.

6. Pastikan commit baru:
   - berada di branch main
   - author/name dan email valid untuk akun GitHub yang memiliki akses ke zenolambee/toko-digital
   - bukan root@kenzonano...
   - tidak menghapus atau mereset pekerjaan yang sudah ada.

7. Sebelum push:
   - jalankan git status
   - pastikan hanya repository toko-digital yang digunakan
   - pastikan remote benar
   - jangan force push
   - jangan reset --hard
   - jangan menghapus commit yang sudah ada.

8. Push commit baru ke origin/main.

9. Setelah push, verifikasi:
   - git log -1 --format=fuller
   - git status
   - git remote -v
   - pastikan commit terbaru sudah berada di origin/main.

10. Jika GitHub CLI/API tersedia, verifikasi bahwa author email commit baru memang terasosiasi dengan akun GitHub yang memiliki akses ke repository.

11. Jangan melakukan upgrade Vercel/Pro.
    Jangan mengubah billing.
    Jangan menyentuh toko-online.
    Jangan membuat repository baru.

12. Setelah semuanya selesai, laporkan secara singkat:
    - folder/repository yang digunakan
    - branch
    - commit terbaru
    - author/email commit
    - apakah push berhasil
    - apakah masalah Git identity/Vercel deployment block sudah diperbaiki.

PENTING:
- Jangan menjalankan perintah di luar repository toko-digital yang dapat mengubah repository lain.
- Jangan menyentuh toko-online.
- Jangan force push.
- Jangan menghapus file atau commit yang sudah ada.
- Fokus utama sekarang adalah memperbaiki Git author identity agar deployment Vercel berikutnya tidak lagi diblokir.
```
# 
```
Lanjutkan perbaikan project toko-digital di repository yang sedang aktif.

PENTING:
- Kerjakan langsung di repository.
- Jangan hanya menjelaskan atau memberi contoh code.
- Kamu yang melakukan semua perubahan code.
- Setelah selesai WAJIB jalankan lint dan build.
- Jika ada error, perbaiki sampai bersih.
- Setelah semuanya berhasil, commit dan push ke branch main.
- Jangan mengubah fitur yang sudah berjalan tanpa alasan.
- Jangan membuat pekerjaan setengah jadi.
- Jangan menunggu prompt berikutnya untuk memperbaiki masalah yang sudah terlihat dari audit ini.
- Fokus pada kualitas UI production/mobile terlebih dahulu.
- Jangan membuat desain baru yang jauh dari desain Digital Cell yang sudah ada.

TUJUAN UTAMA:
Perbaiki halaman storefront Digital Cell agar tampilan mobile terlihat rapi, profesional, proporsional, dan nyaman digunakan. Masalah terbesar saat ini adalah PRODUCT CARD TERLALU BESAR sehingga satu produk mengambil hampir seluruh lebar/tinggi layar. Produk harus dibuat jauh lebih compact dan ditampilkan dalam GRID 2 KOLOM VERTIKAL.

==================================================
1. PRODUCT CARD — PRIORITAS PALING TINGGI
==================================================

Perbaiki section "Produk Populer".

Kondisi sekarang:
- Product card terlalu besar.
- Gambar produk terlalu besar.
- Satu card terasa seperti mengambil hampir seluruh layar.
- Informasi produk menjadi terlalu renggang.
- Pada mobile layout tidak efisien.
- User harus scroll terlalu jauh hanya untuk melihat beberapa produk.

UBAH MENJADI:
- Mobile: tepat 2 kolom produk.
- Tablet: 2 atau 3 kolom sesuai breakpoint.
- Desktop: 4 kolom.
- Produk tersusun ke BAWAH secara vertikal menggunakan normal page scrolling.
- JANGAN membuat product list horizontal sebagai layout utama.
- JANGAN membuat satu produk memenuhi seluruh lebar layar.
- JANGAN membuat carousel horizontal untuk product grid utama.
- User harus bisa scroll halaman ke bawah dan melihat:
  row 1 = 2 produk
  row 2 = 2 produk
  row 3 = 2 produk
  dan seterusnya.

Gunakan CSS Grid yang responsive dan stabil.

Contoh konsep:
mobile:
[ Produk 1 ] [ Produk 2 ]
[ Produk 3 ] [ Produk 4 ]
[ Produk 5 ] [ Produk 6 ]

desktop:
[ 1 ] [ 2 ] [ 3 ] [ 4 ]

Pastikan grid tidak overflow ke kanan.

==================================================
2. UKURAN PRODUCT CARD
==================================================

Buat card jauh lebih compact daripada tampilan sekarang.

Card harus:
- memiliki width yang mengikuti grid column;
- tinggi otomatis berdasarkan isi;
- tidak memiliki min-height besar yang tidak diperlukan;
- tidak menggunakan height fixed yang menyebabkan ruang kosong raksasa;
- padding compact tetapi tetap nyaman;
- border-radius konsisten dengan desain Digital Cell;
- image/product thumbnail dibuat proporsional dan tidak mengambil sebagian besar card;
- title maksimal beberapa baris dengan line-clamp;
- description juga jangan membuat card menjadi sangat tinggi;
- harga tetap mudah dibaca;
- badge seperti Populer/Promo/Ready/New tetap terlihat tetapi tidak menutupi produk;
- tombol cart/action berbentuk compact;
- seluruh card tetap clickable jika memang sebelumnya clickable.

Jangan gunakan ukuran gambar yang menyebabkan blank space besar.

Jika gambar produk gagal dimuat:
- tampilkan fallback yang rapi;
- jangan tampilkan broken-image icon;
- jangan menyebabkan layout meloncat.

==================================================
3. PRODUCT INFORMATION
==================================================

Urutan informasi pada card harus jelas:

[thumbnail + badge]
Nama produk
Kategori/provider
Rating / jumlah terjual jika tersedia
Harga
Action/cart

Contoh visual:

┌─────────────────────┐
│ [ IMAGE ]   POPULER │
│                     │
│ ChatGPT Plus        │
│ Akun Resmi          │
│ ⭐ 4.9 | 1.2K       │
│                     │
│ Mulai dari          │
│ Rp 25.000       🛒  │
└─────────────────────┘

Jangan membuat teks terlalu besar.

Typography product card harus lebih kecil daripada heading "Produk Populer".

==================================================
4. PRODUCT IMAGE
==================================================

Perbaiki ukuran thumbnail produk.

Thumbnail:
- konsisten aspect ratio;
- tidak terlalu tinggi;
- tidak membuat card menjadi raksasa;
- gunakan object-fit yang sesuai;
- gunakan container dengan ukuran responsive;
- jangan membuat gambar menjadi full-screen/full-card.

Jika menggunakan image component Next.js:
- pastikan konfigurasi image benar;
- jangan menyebabkan broken image;
- jangan membuat layout shift;
- pertahankan fallback jika URL image kosong/tidak valid.

==================================================
5. SECTION "PRODUK POPULER"
==================================================

Section harus memiliki hierarchy yang bagus:

🔥 Produk Populer                         Lihat semua →

Kemudian langsung grid 2 kolom pada mobile.

Jangan memberi jarak vertikal berlebihan antara heading dan product grid.

" Lihat semua " tetap berada di kanan heading dan tidak menyebabkan overflow.

Pastikan heading tidak terlalu besar pada mobile.

==================================================
6. MOBILE RESPONSIVE
==================================================

Audit seluruh homepage khusus viewport mobile.

Pastikan:
- tidak ada horizontal overflow;
- tidak ada elemen keluar dari layar;
- tidak ada teks terpotong secara aneh;
- tidak ada header bertumpuk;
- search bar tidak bertabrakan dengan logo/menu;
- hero tidak menutupi header;
- category row tidak merusak layout;
- product grid benar-benar 2 kolom;
- bottom navigation tidak menutupi konten;
- body memiliki padding bawah yang cukup agar produk terakhir tetap bisa terlihat;
- semua button mudah disentuh;
- tidak ada elemen yang terlalu kecil untuk touch target.

Gunakan breakpoint yang masuk akal, bukan workaround berdasarkan ukuran layar tertentu saja.

==================================================
7. HEADER
==================================================

Pertahankan header Digital Cell yang sudah ada.

Pastikan:
- logo/brand berada di kiri;
- dark mode button dan hamburger menu berada di kanan;
- tidak ada duplicate header;
- tidak ada search bar yang menumpuk di dalam header;
- header tidak menyebabkan konten tertutup;
- spacing mobile rapi.

Jangan menghapus fitur menu.

==================================================
8. HERO
==================================================

Pertahankan hero:
"Solusi Digital
Dalam Genggaman"

dengan:
- badge siap order WhatsApp;
- tombol Belanja Sekarang;
- tombol Hubungi Kami;
- visual/banner;
- carousel indicator jika memang sudah tersedia.

Tetapi pastikan hero:
- tidak terlalu tinggi;
- tidak memenuhi seluruh layar;
- tidak menyebabkan content below fold terlalu jauh;
- tetap responsive pada mobile;
- text tidak keluar dari container;
- button tidak bertabrakan;
- visual tidak rusak.

Jangan menghilangkan CTA WhatsApp.

==================================================
9. SEARCH & FILTER
==================================================

Search/filter harus berada pada section yang jelas setelah hero.

Pastikan:
- tidak bertumpuk;
- tidak overflow;
- input terlihat jelas;
- tombol Filter tetap dapat digunakan;
- ukuran sesuai mobile;
- tidak terlalu tinggi.

==================================================
10. CATEGORY
==================================================

Kategori seperti:
- Semua
- AI & Tools
- Aplikasi
- Streaming
- Top Up
- Cloud & Server
- Lainnya

harus tetap tersedia.

Pada mobile:
- boleh menggunakan horizontal scrolling untuk CATEGORY saja jika diperlukan;
- category item tidak boleh membuat seluruh page horizontal overflow;
- scrollbar boleh disembunyikan secara visual tetapi fungsi swipe tetap bekerja.

PENTING:
Horizontal scrolling boleh digunakan untuk category navigation.
Tetapi PRODUCT GRID UTAMA harus tetap 2 kolom dan turun ke bawah.

==================================================
11. BOTTOM NAVIGATION
==================================================

Pertahankan:
- Beranda
- Kategori
- Pesanan
- Favorit
- Akun

Pastikan:
- fixed/sticky sesuai implementasi existing;
- tidak menutupi product card;
- memiliki safe bottom spacing;
- icon dan text sejajar;
- active state jelas;
- tidak overflow pada mobile.

==================================================
12. DATA & FITUR
==================================================

Jangan mengganti data produk hanya demi memperbaiki UI.

Pertahankan:
- product data;
- category;
- provider;
- pricing;
- rating;
- order/WhatsApp;
- favorite;
- cart/action;
- dark mode;
- menu;
- routing yang sudah ada.

Jika ada data yang memang kosong, handle gracefully.

==================================================
13. DESKTOP
==================================================

Jangan hanya memperbaiki mobile.

Pastikan desktop juga bagus:
- product grid 4 kolom;
- container memiliki max-width yang masuk akal;
- tidak terlalu melebar;
- whitespace proporsional;
- hero tidak terlalu besar;
- search/filter rapi;
- kategori rapi;
- tidak ada horizontal overflow.

==================================================
14. DARK MODE
==================================================

Pertahankan dark mode.

Audit agar:
- product card tetap terbaca;
- text memiliki contrast yang cukup;
- border/shadow sesuai;
- search input tetap terlihat;
- category tetap terbaca;
- bottom navigation tetap terbaca;
- tidak ada hardcoded white background yang merusak dark mode.

==================================================
15. KODE & STRUKTUR
==================================================

Sebelum mengubah code:
- audit struktur project;
- cek komponen yang sudah tersedia;
- gunakan komponen existing jika memang sesuai;
- jangan membuat duplicate component;
- jangan membuat duplicate app/page directory;
- jangan membuat workaround yang hanya menyelesaikan satu viewport;
- jangan menambahkan dependency baru jika tidak diperlukan.

Pastikan tidak ada:
- duplicate layout;
- duplicate header;
- duplicate navigation;
- CSS conflict;
- class yang saling menimpa;
- import yang tidak digunakan;
- component yang tidak digunakan.

==================================================
16. QUALITY CHECK
==================================================

Setelah implementasi:

1. Jalankan lint.
2. Jalankan production build.
3. Pastikan tidak ada TypeScript error.
4. Pastikan tidak ada import error.
5. Pastikan tidak ada broken route.
6. Pastikan tidak ada missing module.
7. Pastikan tidak ada duplicate app directory.
8. Pastikan tidak ada horizontal overflow pada mobile.
9. Pastikan product grid mobile benar-benar 2 kolom.
10. Pastikan product card tidak lagi berukuran raksasa.
11. Pastikan seluruh homepage tetap dapat discroll sampai bawah.
12. Pastikan bottom navigation tidak menutupi konten.

Jika build/lint gagal:
- cari akar masalah;
- perbaiki;
- jalankan ulang;
- jangan berhenti pada error pertama.

==================================================
17. HASIL AKHIR YANG WAJIB
==================================================

Target akhir mobile harus terasa seperti storefront e-commerce profesional:

Header
↓
Hero compact
↓
Search + Filter
↓
Category navigation
↓
Produk Populer
↓
[Product] [Product]
[Product] [Product]
[Product] [Product]
[Product] [Product]
↓
Section berikutnya
↓
Bottom navigation

BUKAN:

[Product super besar memenuhi layar]
[Product super besar memenuhi layar]
[Product super besar memenuhi layar]

Product harus compact sehingga user dapat melihat minimal beberapa produk sekaligus dalam satu layar.

==================================================
18. GIT
==================================================

Setelah semua selesai dan build/lint berhasil:

- cek git diff;
- pastikan hanya perubahan yang relevan;
- commit dengan pesan yang jelas, misalnya:
  "fix: optimize mobile product grid and storefront layout"
- push ke branch main.

Jangan hanya commit tanpa push.

Setelah push, tampilkan:
- commit hash;
- ringkasan perubahan;
- hasil lint;
- hasil build;
- konfirmasi push berhasil.

KERJAKAN SEMUA DI ATAS SEKALIGUS DALAM SATU PENGERJAAN. JANGAN MENUNGGU PROMPT BERIKUTNYA UNTUK MEMPERBAIKI HAL-HAL YANG SUDAH TERMASUK DALAM AUDIT INI.

```
# 
```
Lakukan perombakan frontend toko-digital secara menyeluruh agar hasil akhirnya benar-benar mendekati UI referensi Digital Cell yang sudah diberikan sebelumnya.

PENTING:
- Jangan membuat screenshot-to-code atau fitur screenshot-to-code.
- Jangan hanya memperbaiki sebagian kecil tampilan.
- Jangan mengulang pekerjaan yang sudah benar.
- Sebelum mengubah kode, audit seluruh repository dan pahami struktur yang sudah ada.
- Pertahankan fitur yang memang sudah berfungsi dan jangan merusaknya.
- Fokus utama sekarang adalah kualitas UI/UX frontend.
- Setelah semua perubahan selesai, jalankan lint dan build.
- Perbaiki semua error sampai build berhasil.
- Commit semua perubahan dan push ke branch utama repository.
- Setelah push selesai, pastikan working tree bersih.

TARGET DESAIN:
Gunakan UI referensi Digital Cell yang diberikan user sebagai acuan visual utama. Hasil akhir harus terasa seperti website toko digital profesional, modern, premium, clean, responsive, bukan halaman template sederhana.

STRUKTUR HALAMAN UTAMA:
1. HEADER
   - Desktop dan mobile responsive.
   - Logo/brand Digital Cell di kiri.
   - Subjudul/tagline kecil di bawah nama brand.
   - Tombol dark/light mode.
   - Tombol menu.
   - Header berbentuk rounded card dengan shadow/border halus.
   - Jangan membuat header terlalu tinggi.
   - Gunakan typography yang modern dan konsisten.
   - Mobile harus tetap rapi dan tidak membuat elemen bertabrakan.

2. HERO BANNER
   - Buat hero banner besar dengan rounded corners.
   - Background dominan biru gelap/gradient biru seperti referensi.
   - Sediakan headline besar:
     "Solusi Digital
      Dalam Genggaman"
   - Deskripsi:
     "Akun premium, aplikasi, top up,
      dan layanan digital lainnya."
   - Tombol CTA "Belanja Sekarang".
   - Sediakan visual produk/ilustrasi digital di sisi kanan.
   - Tambahkan indikator carousel kecil di bagian bawah.
   - Hero harus terlihat premium dan seimbang.
   - Jangan menggunakan blok biru polos dengan tombol besar di tengah.
   - Jangan membuat hero seperti landing page generik.

3. SEARCH BAR
   - Setelah hero, buat search bar besar rounded.
   - Ada icon search.
   - Placeholder:
     "Cari produk, layanan, atau kategori..."
   - Tambahkan tombol filter di sisi kanan.
   - Search bar harus terlihat seperti komponen marketplace modern.
   - Responsive untuk mobile.

4. CATEGORY NAVIGATION
   - Buat kategori horizontal/card navigation seperti referensi.
   - Kategori:
     Semua
     AI & Tools
     Aplikasi
     Streaming
     Top Up
     Cloud & Server
     Lainnya
   - Setiap kategori mempunyai icon/visual yang jelas.
   - Kategori aktif memiliki warna biru dan indicator aktif.
   - Desktop horizontal.
   - Mobile dapat horizontal scroll tanpa scrollbar yang mengganggu.
   - Jangan menggunakan emoji sebagai visual utama jika tersedia icon yang lebih profesional.
   - Konsisten ukuran icon, card, typography dan spacing.

5. PRODUK POPULER
   - Heading:
     "🔥 Produk Populer"
   - Ada link "Lihat Semua →" di kanan.
   - Product grid responsive.
   - Desktop menampilkan 4 product card dalam satu row seperti referensi.
   - Tablet 2 kolom.
   - Mobile 2 kolom jika masih nyaman, atau 1 kolom jika diperlukan berdasarkan breakpoint.
   - Card harus memiliki:
     image/thumbnail area,
     badge status,
     nama produk,
     tipe produk,
     rating,
     jumlah terjual,
     harga mulai,
     harga utama,
     tombol order/cart.
   - Gunakan hierarchy typography yang jelas.
   - Card rounded, border/shadow halus.
   - Image product harus dominan dan konsisten.
   - Badge seperti Terlaris, Promo, Ready, New harus terlihat profesional.
   - Jangan membuat card terlalu tinggi atau terlalu kosong.

6. PROMO BANNER
   - Buat banner promo seperti referensi:
     "DISKON TERBATAS"
     "Dapatkan Diskon Hingga 20%"
     "Untuk semua produk pilihan"
   - Background biru gelap/gradient.
   - Ada visual discount/20% di sisi kanan.
   - Ada CTA/arrow.
   - Rounded corners.
   - Responsive.

7. TRUST FEATURES
   - Tambahkan section fitur:
     Aman & Terpercaya
     Proses Cepat
     Layanan 24/7
     Harga Terbaik
   - Setiap item mempunyai icon, title dan subtitle.
   - Layout horizontal pada desktop dan adaptif pada mobile.
   - Visual harus ringan dan premium.

8. BOTTOM NAVIGATION MOBILE
   - Pada mobile buat bottom navigation seperti referensi.
   - Menu:
     Beranda
     Kategori
     Pesanan
     Favorit
     Akun
   - Fixed di bawah.
   - Rounded/clean container.
   - Active state jelas.
   - Jangan menutupi konten.
   - Berikan padding bawah pada halaman agar konten terakhir tidak tertutup bottom navigation.
   - Desktop boleh menyembunyikan bottom navigation jika memang lebih sesuai.

9. DARK MODE
   - Pastikan dark mode benar-benar didesain, bukan sekadar membalik warna.
   - Background, card, border, text, icon, hero dan input harus mempunyai dark-mode treatment yang konsisten.
   - Tidak boleh ada text hitam di background gelap atau text putih yang sulit dibaca.
   - Simpan preferensi theme bila struktur aplikasi saat ini mendukungnya.

10. RESPONSIVE
   Pastikan hasil benar-benar bagus pada:
   - mobile 360px
   - mobile 390px
   - mobile 430px
   - tablet
   - desktop 1280px+
   Tidak boleh ada:
   - horizontal overflow
   - text terpotong
   - tombol keluar layar
   - card terlalu kecil
   - image gepeng
   - header berantakan
   - bottom navigation menutupi konten.

ARSITEKTUR:
- Gunakan component reusable.
- Jangan membuat seluruh homepage menjadi satu file besar.
- Pisahkan komponen seperti:
  Header
  HeroBanner
  SearchBar
  CategoryNav
  ProductSection
  ProductCard
  PromoBanner
  TrustFeatures
  MobileBottomNav
  dan komponen lain jika diperlukan.
- Gunakan data produk/kategori dari source data yang sudah ada jika masih relevan.
- Jangan membuat data duplicate hanya untuk mempercantik UI.
- Jika ada komponen lama yang masih bagus, reuse dan refactor seperlunya.

PRODUCT ORDER:
Website ini BUKAN checkout marketplace penuh.
Tidak perlu membuat sistem pembayaran/checkout.
Alur order utama adalah:
produk -> detail produk -> tombol order -> WhatsApp.
Pastikan tombol order mengarah ke WhatsApp dengan pesan order yang sudah terisi berdasarkan produk.
Nomor WhatsApp/config jangan hardcode di banyak tempat; gunakan satu konfigurasi/data source.

PRODUCT DETAIL:
- Pastikan halaman detail produk juga mempunyai kualitas visual yang sama dengan homepage.
- Informasi produk harus jelas.
- Harga jelas.
- Deskripsi jelas.
- Status/badge jelas.
- Tombol "Order via WhatsApp" menjadi CTA utama.
- Jangan membuat checkout/payment flow.

CATEGORY:
- Halaman kategori harus konsisten dengan homepage.
- User dapat memilih kategori dan melihat produk terkait.
- Search/filter jika fitur tersebut sudah tersedia harus tetap berfungsi.
- Jangan merusak routing yang sudah ada.

ADMIN PANEL:
- Jangan menghapus panel admin yang sudah ada.
- Audit panel admin yang sudah dibuat.
- Pastikan route/admin functionality tidak rusak akibat redesign frontend.
- Jika panel admin sudah memiliki struktur/data produk, gunakan data tersebut pada frontend bila arsitektur repository memang sudah mendukung.
- Jangan membuat panel admin kedua/duplikat.

KUALITAS VISUAL:
- Gunakan satu design system yang konsisten.
- Gunakan spacing yang teratur.
- Gunakan border radius konsisten.
- Gunakan shadow secara halus.
- Jangan terlalu banyak gradient.
- Warna utama mengikuti referensi: putih/light background dengan aksen biru kuat, serta dark mode yang profesional.
- Typography harus memiliki hierarchy yang jelas.
- Jangan menggunakan emoji sebagai pengganti seluruh icon UI.
- Jangan membuat UI terlihat seperti prototype kasar.
- Hindari excessive glassmorphism.
- Hindari oversized button yang memenuhi layar.
- Hindari whitespace yang tidak perlu.
- Pastikan alignment antar section rapi.

ASSET:
- Audit asset yang sudah ada terlebih dahulu.
- Jika sudah ada logo/product image/asset yang relevan, gunakan kembali.
- Jangan membuat asset duplicate dengan nama berbeda.
- Jika asset belum ada, gunakan solusi visual yang konsisten dengan design system dan mudah diganti nantinya.
- Pastikan image memiliki aspect ratio yang benar dan tidak pecah.

TECHNICAL AUDIT:
Sebelum selesai:
1. Audit package.json.
2. Audit src/app.
3. Audit src/components.
4. Audit src/lib/data atau sumber data yang digunakan.
5. Audit routing.
6. Audit theme/dark mode.
7. Audit Tailwind/CSS/global CSS.
8. Audit image handling.
9. Audit environment variables.
10. Audit dependency yang tidak terpakai.
11. Cari duplicate app directory atau route duplicate.
12. Cari import yang salah.
13. Cari component yang tidak digunakan.
14. Cari error TypeScript.
15. Cari masalah hydration/client component.
16. Pastikan konfigurasi Vercel kompatibel dengan Next.js project.
17. Jangan menambahkan dependency baru jika tidak diperlukan.

VERCEL:
- Project harus siap deploy ke Vercel.
- Jangan membutuhkan VPS untuk frontend.
- Pastikan build production berhasil dengan command yang digunakan Vercel.
- Pastikan environment variable yang diperlukan terdokumentasi.
- Jangan memasukkan secret/API key ke source code.
- Jangan membuat backend baru jika belum diperlukan.

VALIDASI:
Setelah implementasi:
- npm run lint
- npm run build
- jika ada test yang relevan, jalankan test yang memang aman/relevan.
- Perbaiki error yang ditemukan.
- Jalankan build ulang sampai PASS.
- Jangan berhenti hanya karena lint berhasil.
- Pastikan production build benar-benar berhasil.

GIT:
Setelah semuanya benar:
- git status
- git diff
- git add -A
- git commit dengan pesan yang jelas, misalnya:
  "feat: rebuild Digital Cell storefront UI"
- git push origin main

SEBELUM MENYATAKAN SELESAI:
- Pastikan perubahan benar-benar sudah masuk remote repository.
- Pastikan git status bersih.
- Pastikan tidak ada perubahan penting yang tertinggal.
- Jangan hanya mengatakan "sudah selesai" tanpa memastikan push berhasil.

HASIL YANG DIHARAPKAN:
Homepage final harus secara visual mendekati referensi Digital Cell yang diberikan user: header premium, hero banner biru, search bar, category navigation, product cards 4 kolom, promo banner, trust section, dan mobile bottom navigation.

Jangan mengurangi scope menjadi sekadar memperbaiki error build. Kerjakan redesign frontend secara menyeluruh, tetapi tetap pertahankan fitur yang sudah benar.

Setelah semua selesai, cukup tampilkan ringkasan:
- perubahan utama
- lint status
- build status
- commit hash
- push status
```
# 
```
Audit sebelumnya belum benar-benar selesai. Saya sudah cek repository dan menemukan root cause build Vercel masih ada.

WAJIB perbaiki langsung dan selesaikan sampai production build PASS.

Root cause yang sudah terkonfirmasi:
- src/app/globals.css menggunakan @import "tailwindcss";
- postcss.config.mjs menggunakan plugin "@tailwindcss/postcss"
- tetapi package.json TIDAK memiliki tailwindcss dan @tailwindcss/postcss.

Perbaiki root cause tersebut dengan dependency/configuration yang benar dan kompatibel dengan Next.js yang digunakan project.

Setelah itu JANGAN berhenti.

Lakukan audit ulang seluruh repository seperti instruksi sebelumnya:
1. package.json dan package-lock.json harus sinkron.
2. Semua dependency yang digunakan source code harus tersedia.
3. Semua import harus valid.
4. Audit case-sensitive path untuk Linux/Vercel.
5. Audit src/app dan pastikan tidak ada duplicate app directory.
6. Audit layout.tsx dan globals.css.
7. Audit seluruh client/server component boundary.
8. Audit Tailwind/PostCSS configuration.
9. Audit TypeScript configuration.
10. Audit seluruh route customer.
11. Audit seluruh route admin.
12. Pastikan /admin, /admin/login, /admin/produk, /admin/kategori tetap ada.
13. Jangan hapus panel admin.
14. Jangan mengubah konsep UI.
15. Jangan menghapus fitur WhatsApp order.
16. Pastikan NEXT_PUBLIC_WHATSAPP_NUMBER digunakan dengan benar.
17. Pastikan .env.example tidak berisi secret asli.
18. Audit semua asset public dan import gambar/icon.
19. Audit semua dependency yang dipakai component.
20. Audit semua konfigurasi Next.js/Vercel.

Kemudian jalankan dari kondisi dependency bersih:

rm -rf node_modules .next
npm install
npx tsc --noEmit
npm run lint
npm run build

Jika ada error, jangan hanya memperbaiki error pertama. Trace root cause dan lanjutkan sampai SEMUA PASS.

Perhatikan bahwa script "lint" saat ini sebenarnya menjalankan "tsc --noEmit". Jangan menganggap itu sebagai ESLint. Jika project memang membutuhkan ESLint, konfigurasi dengan benar dan tambahkan script lint yang benar tanpa merusak build.

Pastikan production build benar-benar menghasilkan:
- ✓ TypeScript/check berhasil
- ✓ lint berhasil
- ✓ Next.js production build berhasil
- ✓ tidak ada Module not found
- ✓ tidak ada dependency missing
- ✓ tidak ada route compilation error

Setelah build PASS:
- jalankan git status
- git diff --check
- pastikan tidak ada secret yang ikut commit
- commit semua perubahan yang diperlukan
- push ke branch main
- pastikan remote sudah berisi commit terbaru.

JANGAN berhenti dengan laporan saja.
JANGAN meminta saya memperbaiki manual.
JANGAN mengatakan "seharusnya sudah".
LAKUKAN perbaikan, TEST, COMMIT, dan PUSH.

Target akhir: saya cukup melakukan deploy Vercel ulang dan build harus berhasil.
```
# 
```
Lakukan AUDIT MENYELURUH project toko-digital dan selesaikan sampai benar-benar siap deploy production ke Vercel. Jangan hanya memperbaiki error yang terlihat dari log terakhir. Audit seluruh project terlebih dahulu, lalu perbaiki semua masalah yang berpotensi menyebabkan build gagal, runtime error, route error, UI rusak, atau fitur tidak berjalan.

KONTEKS PROJECT:
- Repository: toko-digital
- Target hosting: Vercel
- Framework: Next.js + TypeScript
- Website adalah katalog/toko digital.
- Website BUKAN sistem checkout/payment.
- Tombol order produk harus mengarah ke WhatsApp.
- UI harus mengikuti desain/referensi yang sudah dibuat sebelumnya.
- Panel admin harus tetap tersedia.
- Jangan menghapus fitur yang sudah ada hanya untuk membuat build berhasil.
- Jangan membuat workaround yang menyembunyikan error.
- Jangan membuat struktur /app kedua. Gunakan struktur App Router yang benar dan konsisten.

TUJUAN AKHIR:
Project harus dalam kondisi:
1. Bisa install dependency dari kondisi repository fresh.
2. Lulus TypeScript check.
3. Lulus ESLint/lint.
4. Lulus production build Next.js.
5. Tidak ada Module not found.
6. Tidak ada import path yang salah/case-sensitive.
7. Tidak ada dependency yang dipakai tetapi tidak tercantum di package.json.
8. Tidak ada dependency tidak diperlukan yang menyebabkan masalah build.
9. Semua route utama bisa di-build.
10. Tidak ada server/client component conflict.
11. Tidak ada penggunaan browser API di Server Component.
12. Tidak ada penggunaan server-only API di Client Component.
13. Tidak ada environment variable yang salah nama atau salah penggunaan.
14. Konfigurasi Vercel/Next.js aman untuk deployment.
15. UI utama tetap sesuai desain.
16. Panel admin tetap tersedia dan route-nya benar.
17. Tombol order menggunakan WhatsApp sesuai konsep website.
18. Responsive mobile dan desktop tetap baik.
19. Dark mode tetap berfungsi jika sudah dibuat.
20. Tidak ada error console/build yang jelas dari source code.
21. Setelah semua selesai, perubahan di-commit dan di-push ke branch main.

TAHAP 1 — AUDIT STRUKTUR PROJECT
Periksa seluruh struktur repository terlebih dahulu.

Audit:
- app/
- src/app/
- src/components/
- src/lib/
- public/
- package.json
- package-lock.json
- tsconfig.json
- next.config.*
- eslint config
- postcss config
- tailwind config jika digunakan
- middleware jika ada
- environment files
- konfigurasi Vercel jika ada
- semua file konfigurasi lain.

Pastikan tidak ada struktur App Router ganda atau file lama yang bertabrakan.

Pastikan route hanya memiliki satu sumber yang benar.

Cari:
- duplicate app directory
- duplicate layout
- duplicate globals.css
- duplicate page.tsx
- route collision
- folder yang salah posisi
- import dari file yang sudah dipindahkan/dihapus.

TAHAP 2 — AUDIT SEMUA IMPORT
Periksa SEMUA import di seluruh source code.

Cari:
- Module not found
- file path salah
- alias @/ yang tidak sesuai tsconfig
- relative import yang salah
- import case-sensitive yang mungkin berhasil di Windows tetapi gagal di Linux/Vercel
- import file yang tidak ada
- import dependency yang tidak terinstall
- import dependency yang hanya tersedia sebagai devDependency tetapi diperlukan saat build/runtime
- circular dependency yang bermasalah.

Jangan hanya memperbaiki import yang disebut dalam error terakhir. Scan seluruh repository.

TAHAP 3 — AUDIT PACKAGE.JSON
Periksa package.json secara menyeluruh.

Pastikan:
- semua package yang benar-benar digunakan tersedia.
- versi package kompatibel satu sama lain.
- Next.js, React, React DOM, TypeScript, Tailwind, icon library, dan package lainnya kompatibel.
- tidak ada package yang dipanggil source code tetapi belum diinstall.
- package-lock.json sinkron dengan package.json.
- script lint/typecheck/build benar.
- tidak ada script build yang salah.
- tidak ada konfigurasi yang hanya bekerja lokal tetapi gagal di Vercel.

Jika perlu dependency tambahan, install secara normal dan update package-lock.json.

TAHAP 4 — AUDIT NEXT.JS + TYPESCRIPT
Periksa semua:
- layout.tsx
- page.tsx
- loading.tsx
- error.tsx
- not-found.tsx
- route.ts
- metadata
- server/client components
- dynamic routes
- params/searchParams
- penggunaan hooks
- penggunaan window/document/localStorage
- penggunaan environment variables.

Pastikan penggunaan "use client" hanya pada component yang memang membutuhkan client-side API/hooks.

Pastikan globals.css diimport pada lokasi yang benar.

Pastikan tidak ada component client yang menyebabkan dependency server-only masuk ke browser bundle.

TAHAP 5 — AUDIT CSS/UI
Periksa seluruh UI tanpa mengubah konsep desain.

Referensi desain utama:
- header dengan logo/nama toko
- tombol dark mode
- menu
- hero/banner
- search
- kategori
- produk populer
- product card
- promo banner
- benefit/keunggulan
- navigasi/footer jika sudah dibuat
- responsive layout.

Pastikan:
- tidak ada class Tailwind yang invalid.
- tidak ada CSS import yang rusak.
- tidak ada asset path yang salah.
- gambar dari public dapat ditemukan.
- icon/component yang dipakai tersedia.
- tidak ada layout overflow pada mobile.
- tidak ada komponen yang hilang akibat import error.

Jangan redesign dari nol. Pertahankan UI yang sudah dibuat.

TAHAP 6 — AUDIT DATA PRODUK
Periksa data katalog dan struktur data.

Pastikan:
- products dapat diimport.
- categories dapat diimport.
- product ID unik.
- category ID unik.
- product/category relationship benar.
- ProductCard menerima props yang benar.
- tidak ada field yang digunakan UI tetapi tidak tersedia di data.
- harga dan informasi produk ditampilkan dengan benar.
- data provider jika ada tidak menyebabkan build error.

TAHAP 7 — AUDIT WHATSAPP ORDER
Website tidak menggunakan checkout/payment internal.

Audit alur order:
- tombol order produk tersedia.
- tombol tersebut membuat link WhatsApp yang valid.
- nomor WhatsApp berasal dari konfigurasi yang sesuai.
- pesan order otomatis berisi informasi produk yang relevan.
- encoding URL benar.
- tidak ada link WhatsApp rusak.
- tidak ada checkout/cart/payment flow yang tidak diperlukan.

Jika nomor WhatsApp membutuhkan environment variable, pastikan fallback/configuration-nya jelas dan tidak menyebabkan build gagal.

TAHAP 8 — AUDIT PANEL ADMIN
Panel admin WAJIB dipertahankan.

Pastikan route berikut dan route admin lain yang sudah ada tetap bekerja:
- /admin
- /admin/login
- /admin/produk
- /admin/kategori

Audit:
- routing
- login flow
- form
- state management
- data handling
- component import
- admin layout
- responsive UI
- client/server boundary.

Jangan menghapus panel admin hanya karena deployment publik belum menggunakan backend/database.

Jika sebagian fitur admin memang masih mock/static, jangan mengarang backend baru. Pastikan setidaknya source code tetap valid dan buildable.

TAHAP 9 — AUDIT ENVIRONMENT VARIABLES
Periksa:
- .env
- .env.example
- penggunaan process.env
- variable yang diperlukan saat build
- variable yang hanya diperlukan runtime.

Jangan pernah commit secret/API key/password/token.

Pastikan .env.example berisi nama variable yang diperlukan tanpa secret asli.

Jika environment variable diperlukan Vercel, dokumentasikan nama variable yang harus tersedia.

TAHAP 10 — AUDIT PUBLIC ASSETS
Scan semua:
- image
- logo
- icon
- font
- SVG
- favicon
- asset public lainnya.

Pastikan semua path valid.

Cari referensi seperti:
- /images/...
- /icons/...
- /logo...
- background-image
- next/image src
- CSS url()

Pastikan tidak ada asset yang hanya tersedia di environment lokal.

TAHAP 11 — AUDIT BUILD ERROR SAAT INI
Fokus khusus pada error Vercel sebelumnya yang menunjukkan dua error dan import trace melalui:

src/app/globals.css
src/app/layout.tsx

Cari root cause sebenarnya dari error tersebut dan periksa semua dependency yang digunakan oleh globals.css/layout.tsx.

Jangan menganggap masalah hanya ada pada dua file tersebut. Trace dependency sampai akar masalah.

TAHAP 12 — TEST DARI KONDISI BERSIH
Setelah perbaikan, simulasikan environment fresh install.

Gunakan install yang sesuai dengan lockfile, lalu jalankan:

npm run lint
npx tsc --noEmit
npm run build

Jika script lint belum benar, perbaiki script/configuration-nya terlebih dahulu.

Build harus benar-benar production build, bukan hanya dev server.

Jika build gagal:
- baca error lengkap.
- cari root cause.
- perbaiki.
- jalankan ulang.
- jangan berhenti pada error pertama jika masih ada error lain.

Teruskan sampai:
- lint PASS
- TypeScript PASS
- build PASS

TAHAP 13 — AUDIT ROUTES SETELAH BUILD
Setelah build berhasil, periksa daftar route yang dihasilkan Next.js.

Pastikan tidak ada route utama yang hilang.

Pastikan route:
- /
- halaman katalog/produk yang sudah dibuat
- route kategori jika ada
- /admin
- /admin/login
- /admin/produk
- /admin/kategori

terdeteksi dengan benar sesuai implementasi repository.

TAHAP 14 — FINAL CLEANUP
Sebelum commit:
- hapus file sementara.
- hapus duplicate files.
- hapus debugging console yang tidak diperlukan.
- jangan hapus fitur.
- jangan commit .env berisi secret.
- pastikan package-lock.json berubah hanya jika memang diperlukan.
- pastikan git diff masuk akal.

Jalankan:

git status
git diff --stat
git diff --check

Perbaiki whitespace/error jika ada.

TAHAP 15 — COMMIT DAN PUSH
Jika semua test PASS:
- git add semua perubahan yang relevan.
- commit dengan pesan yang jelas, misalnya:
  "fix: prepare toko-digital for Vercel production"

- push ke branch main.

Setelah push, pastikan:
- working tree bersih atau hanya menyisakan file yang memang sengaja tidak di-track.
- commit terbaru sudah berada di remote.
- tampilkan hash commit terakhir.

ATURAN PENTING:
- Jangan berhenti setelah audit saja.
- Jangan hanya memberikan laporan; LAKUKAN perbaikannya.
- Jangan meminta saya memperbaiki langkah manual yang sebenarnya bisa kamu perbaiki di repository.
- Jangan menghapus fitur untuk menghilangkan error.
- Jangan mengganti UI dengan desain sederhana.
- Jangan membuat /app kedua.
- Jangan membuat checkout/payment system.
- Jangan menambahkan backend/database baru jika tidak diperlukan untuk menyelesaikan build.
- Jangan menggunakan workaround yang hanya membuat Vercel melewati error.
- Semua perbaikan harus production-ready.
- Jangan berhenti sebelum lint, TypeScript check, dan production build berhasil.
- Setelah berhasil, langsung commit dan push ke main.

HASIL AKHIR YANG SAYA INGINKAN:
Project toko-digital dalam kondisi siap deploy ke Vercel. Saya cukup melakukan deployment ulang dan tidak perlu memperbaiki error satu per satu lagi.

Setelah selesai, berikan ringkasan singkat:
1. Masalah yang ditemukan.
2. Perbaikan yang dilakukan.
3. Hasil lint.
4. Hasil TypeScript.
5. Hasil production build.
6. Commit hash.
7. Status push ke main.
```
# 
```
Perbaiki struktur project toko-digital sebelum dianggap selesai.

MASALAH YANG DITEMUKAN:
Project saat ini memiliki dua App Router:
- /app
- /src/app

Customer utama masih berada di /app, sedangkan admin berada di /src/app/admin.
Jangan biarkan struktur App Router ganda seperti ini.

TUGAS:
1. Audit seluruh project.
2. Jadikan SATU App Router sebagai sumber route utama.
3. Pertahankan desain/UI customer yang sudah dibuat.
4. Pastikan route berikut benar-benar aktif:
   /
   /produk
   /produk/[slug] atau route detail yang digunakan
   /kategori
   /favorit
   /pesanan
   /akun
   /admin
   /admin/login
   /admin/produk
   /admin/kategori
5. Pilih struktur yang paling tepat untuk Next.js dan pindahkan/rapikan file yang diperlukan agar tidak ada route yang mati karena berada di App Router yang salah.
6. Jangan sampai ada duplikasi page yang menyebabkan bingung saat build/deploy.
7. Pastikan alias @/* tetap bekerja.
8. Pastikan komponen dan data yang sudah ada tetap digunakan.
9. Jangan mengubah konsep website:
   - katalog saja
   - tidak ada checkout
   - tidak ada payment
   - order melalui WhatsApp
10. Pastikan panel admin benar-benar bisa dibuka melalui /admin dan halaman produk/kategori admin bisa dinavigasi.
11. Jika admin CRUD saat ini masih berbasis local state/mock data, pertahankan untuk tahap ini tetapi strukturkan dengan baik agar backend/database bisa ditambahkan kemudian.
12. Pastikan login admin tidak mengklaim keamanan production jika belum ada authentication backend.

VERIFIKASI WAJIB:
- npm run lint
- npm run build
- periksa hasil route Next.js
- pastikan / dan /admin tidak error
- pastikan tidak ada duplicate App Router yang membingungkan deployment.

SETELAH SEMUA BERES:
- git status
- commit perubahan
- push langsung ke origin main
- tampilkan commit hash terakhir
- tampilkan ringkasan route customer dan admin yang benar-benar aktif.

Jangan hanya menjelaskan. Kerjakan langsung sampai selesai dan push ke main.
```
# 
```
Lanjutkan project toko-digital sampai benar-benar siap dipakai dan langsung push semua perubahan ke branch main.

TARGET UTAMA:
1. Selesaikan UI customer agar semirip mungkin dengan desain referensi yang sudah diberikan sebelumnya.
2. Buat Panel Admin yang benar-benar berfungsi.
3. Jangan membuat checkout/cart/payment. Website hanya katalog dan tombol Order via WhatsApp.
4. Setelah semua selesai, jalankan lint + build, perbaiki error jika ada, lalu commit dan push ke main.
5. Jangan hanya menjelaskan atau memberi saran — langsung edit file project.

UI CUSTOMER:
- Header dengan logo/nama Digital Cell, tagline, tombol dark mode, dan menu mobile.
- Hero/banner besar dengan desain modern seperti referensi.
- Search produk.
- Filter/kategori: Semua, AI & Tools, Aplikasi, Streaming, Top Up, Cloud & Server, Lainnya.
- Section Produk Populer dengan card produk.
- Product card menampilkan gambar, badge, nama, tipe, rating/terjual, harga mulai, dan tombol Order.
- Banner promo/diskon.
- Section keunggulan: Aman & Terpercaya, Proses Cepat, Layanan 24/7, Harga Terbaik.
- Bottom navigation mobile seperti referensi: Beranda, Kategori, Pesanan, Favorit, Akun.
- Responsive desktop/mobile.
- Dark mode tetap berfungsi.
- Gunakan data produk yang sudah ada, jangan merusak struktur data yang sudah dibuat.
- Tombol produk/order harus mengarah ke WhatsApp dengan pesan order yang otomatis berisi nama produk.
- Tidak perlu sistem checkout internal.

HALAMAN CUSTOMER:
- /
- /produk
- /produk/[slug] atau route detail yang sudah digunakan project
- kategori/filter tetap berfungsi.
- Search dan navigasi harus benar-benar bekerja, bukan sekadar tampilan.

PANEL ADMIN:
Buat route /admin dengan layout admin yang rapi dan responsive.
Fitur minimal:
- Dashboard ringkas.
- Kelola produk: tambah, edit, hapus, aktif/nonaktif.
- Kelola kategori.
- Pengaturan nomor WhatsApp toko.
- Pengaturan nama toko, logo, tagline, banner/teks promo jika arsitektur project memungkinkan.
- Daftar produk menampilkan status aktif/nonaktif.
- Admin UI harus terpisah dari UI customer.
- Tambahkan navigasi/sidebar admin.
- Jangan membuat fitur pembayaran atau checkout.

AUTH ADMIN:
- Jangan membuat sistem authentication kompleks jika backend/database belum tersedia.
- Buat struktur admin yang modular sehingga authentication bisa ditambahkan kemudian.
- Jangan menyimpan secret/API key di frontend.
- Jika project saat ini sudah mempunyai mekanisme auth/backend, gunakan mekanisme tersebut dan jangan menggantinya secara sembarangan.

ARSITEKTUR:
- Komponen harus modular.
- Jangan menumpuk seluruh UI dalam satu file.
- Reuse ProductCard, CategoryCard, Header, Hero, Footer/BottomNav, dan komponen admin yang relevan.
- Pertahankan TypeScript yang sudah ada.
- Gunakan data layer yang sudah ada.
- Jika diperlukan, buat data/config terpusat agar produk dan setting toko mudah dikelola.

DESAIN:
- Ikuti referensi UI yang sudah diberikan sebelumnya sebagai acuan utama.
- Nuansa modern toko digital: putih/soft background, biru sebagai warna utama, rounded card, shadow halus, typography bersih.
- Desktop dan mobile harus sama-sama bagus.
- Jangan mengganti desain menjadi template generik.
- Pastikan spacing, card, header, hero, kategori, dan bottom navigation terasa seperti desain referensi.

SEBELUM SELESAI:
- Periksa semua route customer.
- Periksa /admin.
- Jalankan npm run lint.
- Jalankan npm run build.
- Jika ada error, perbaiki langsung.
- Jangan berhenti hanya karena ada warning non-fatal.
- Pastikan tidak ada import/path yang rusak.
- Pastikan environment variable yang diperlukan terdokumentasi di .env.example tanpa memasukkan secret asli.

GIT:
- Cek git status.
- Stage perubahan yang memang berasal dari pekerjaan ini.
- Commit dengan pesan yang jelas, misalnya:
  "Complete toko-digital customer UI and admin panel"
- Push langsung ke origin main.
- Setelah push, tampilkan commit hash terakhir dan ringkasan singkat hasil pekerjaan.

KERJAKAN LANGSUNG. Jangan meminta saya menyalin kode satu per satu dan jangan hanya memberikan instruksi.
```
# 
```
Finalisasi project toko-digital sampai siap deploy ke Vercel.

Kerjakan langsung di repository, jangan hanya memberi penjelasan.

Target:
- Website katalog Toko Digital, BUKAN checkout/e-commerce penuh.
- Order semua produk melalui WhatsApp.
- UI harus mengikuti desain referensi yang sudah diberikan: modern, clean, dominan putih/blue, rounded card, responsive mobile/desktop.
- Pertahankan struktur modular yang sudah ada.
- Pastikan homepage memiliki:
  1. Header/logo Digital Cell + dark mode + menu
  2. Hero/banner
  3. Search produk
  4. Kategori
  5. Produk populer
  6. Banner promo
  7. Keunggulan layanan
  8. Navigasi mobile bawah
- Produk memiliki detail yang jelas dan tombol Order via WhatsApp.
- Jangan membuat sistem cart/checkout/payment.
- Pastikan nomor/link WhatsApp mudah dikonfigurasi.
- Pastikan tidak ada data dummy yang merusak tampilan.
- Pastikan semua halaman dan navigasi berfungsi.
- Pastikan responsive dan tidak ada overflow pada mobile.
- Jalankan lint/typecheck/build dan perbaiki semua error.
- Jangan mengubah requirement menjadi aplikasi checkout.
- Setelah selesai, commit semua perubahan dan push langsung ke branch main.
- Jangan berhenti sebelum build berhasil dan perubahan sudah di-push.

Terakhir tampilkan:
1. ringkasan perubahan,
2. hasil lint/typecheck/build,
3. commit hash,
4. konfirmasi push berhasil.
```

# 
```
Lanjutkan project toko-digital sampai benar-benar siap digunakan dan push semua perubahan ke repository GitHub.

Target:
- Website katalog toko digital.
- Hosting target Vercel.
- Tidak ada fitur checkout.
- Semua tombol order mengarah ke WhatsApp.
- UI mengikuti desain referensi yang saya berikan sebelumnya.
- Jangan mengubah konsep menjadi marketplace/checkout.

Kerjakan sampai selesai, bukan hanya membuat sebagian.

Pastikan:
1. Homepage lengkap dan responsive desktop/mobile.
2. Header dengan logo/nama Digital Cell, dark mode, dan menu mobile.
3. Hero/banner seperti desain referensi.
4. Search produk.
5. Kategori produk.
6. Product card dengan gambar, nama, deskripsi singkat, rating, harga, badge, dan tombol Order.
7. Section produk populer.
8. Banner promo.
9. Section keunggulan toko.
10. Navigasi mobile.
11. Halaman kategori.
12. Halaman/detail produk.
13. Tombol Order via WhatsApp menggunakan nomor yang mudah dikonfigurasi melalui environment variable.
14. Tidak membuat sistem cart, checkout, pembayaran, login, atau database yang tidak diperlukan.
15. Data produk dibuat terstruktur/modular sehingga mudah ditambah nanti.
16. Gunakan komponen reusable dan jangan menumpuk semua kode dalam satu file.
17. Pastikan tampilan mendekati desain referensi: clean, modern, rounded card, spacing rapi, nuansa biru/putih, dan mobile-first.
18. Pastikan tidak ada TypeScript error, lint error, atau build error.
19. Jalankan pemeriksaan lint/typecheck dan production build.
20. Perbaiki semua error yang ditemukan.
21. Pastikan konfigurasi Vercel/Next.js siap deployment.
22. Setelah selesai, commit seluruh perubahan dan push langsung ke branch utama repository.

Jangan berhenti setelah memberi penjelasan. Kerjakan perubahan langsung di repository dan push sampai selesai.

Setelah push berhasil, tampilkan:
- commit terakhir
- hasil lint/typecheck
- hasil build
- ringkasan fitur yang selesai

Jika ada bagian yang belum selesai, selesaikan terlebih dahulu sebelum memberikan laporan.
```

# 
```
Buat fondasi website katalog Toko Digital dari nol.

Gunakan:
- Next.js terbaru dengan App Router
- TypeScript
- Tailwind CSS
- Struktur project yang modular dan mudah dikembangkan
- Responsive/mobile-first karena mayoritas pengguna memakai HP

Konsep website:
Toko Digital adalah katalog produk digital, bukan marketplace checkout.

Fitur utama yang akan dikembangkan:
- Kategori produk
- Paket Data
- Provider
- App Premium
- Daftar produk
- Detail produk
- Order melalui WhatsApp
- Halaman Admin untuk mengelola katalog

Untuk tahap ini JANGAN membuat checkout, payment gateway, keranjang, atau sistem pembayaran.

Tugas tahap ini:
1. Buat project Next.js.
2. Buat struktur folder yang rapi untuk pages, components, data/types, dan fitur yang nantinya membutuhkan backend.
3. Buat layout dasar website.
4. Buat navbar/header dan area konten utama.
5. Buat homepage sementara dengan identitas "Toko Digital".
6. Buat desain dasar yang modern, bersih, dan nyaman di mobile.
7. Pastikan project dapat dijalankan dengan npm run dev.
8. Jangan membuat fitur di luar scope tahap ini.

Setelah selesai, cek TypeScript/build untuk memastikan tidak ada error.

Jangan hanya menjelaskan kode. Langsung implementasikan ke repository.
```
