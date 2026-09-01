# prompt-toko-digital


# 
```

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
