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
