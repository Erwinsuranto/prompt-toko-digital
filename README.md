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
