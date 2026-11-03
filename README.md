# The Shop

The Shop adalah marketplace fashion tempat banyak penjual pakaian membuka toko online, dan pembeli bisa belanja dari beberapa toko sekaligus dengan satu kali pembayaran. Proyek ini dibangun sebagai proyek belajar full stack, menjalani seluruh siklus pengembangan software: perencanaan, desain, coding, testing, sampai deployment.

## Fitur MVP

- **Akun**: daftar, login, dan membuka toko
- **Katalog**: kategori Pria, Wanita, Anak, Aksesoris, dan Luxury Brand, dengan pencarian serta filter ukuran dan harga
- **Varian produk**: stok dihitung per kombinasi ukuran dan warna
- **Belanja**: keranjang multi-toko dan checkout dengan pembayaran Midtrans (mode sandbox)
- **Pesanan**: status pesanan dan nomor resi untuk pembeli maupun penjual
- **Saldo penjual**: penghasilan setelah komisi platform 5% dan pengajuan penarikan
- **Panel admin**: kelola kategori, pengguna, toko, pesanan, dan penarikan saldo

## Alur pesanan

```
Menunggu Pembayaran → Dibayar → Diproses → Dikirim → Selesai
```

Pesanan dibatalkan jika tidak dibayar dalam 24 jam atau ditolak penjual. Pesanan yang sudah dikirim otomatis selesai setelah 7 hari jika pembeli tidak mengonfirmasi.

## Tech stack

Akan ditentukan di Fase 3 (perancangan teknis).

## Status

🚧 **Sprint 0**: belajar fondasi (cara kerja web, Git, HTML, CSS, JavaScript).

## Catatan

Proyek ini hanya memakai data uji. Tidak ada transaksi dengan uang sungguhan.

## Lisensi

[MIT](LICENSE)
