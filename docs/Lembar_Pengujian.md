# Lembar Pengujian

Nama / NPM:
Tanggal / browser / OS:
Kondisi awal: hapus key praktikum-favorites-v1 dan reload sebelum kasus pertama.
Untuk setiap kasus, catat langkah aktual dan beri nama berkas bukti.
Status belum diisi karena pengujian mahasiswa harus dilakukan pada perangkat sendiri.

| No | Langkah uji | Hasil yang diharapkan | Hasil aktual | Status | Bukti |
|---|---|---|---|---|---|
| 1 | Tambah Buku React dari katalog | Badge 1 dan tombol Hapus favorit | | | |
| 2 | Buka detail 1 dan halaman favorit | Produk tetap ditandai dan muncul | | | |
| 3 | Hapus produk dari halaman favorit | Kartu hilang dan badge 0 | | | |
| 4 | Tambah dua favorit dan reload | Dua favorit dipulihkan | | | |
| 5 | Buka /products?q=Buku | Dua produk buku dan input Buku | | | |
| 6 | Cari zzz | Pesan kosong tanpa error | | | |
| 7 | Cari Buku lalu reset lalu Back dan Forward | URL dan input konsisten | | | |
| 8 | Buka /products/999 lalu /acak | Pesan ID lalu halaman tidak ditemukan | | | |
| 9 | Isi key storage dengan teks rusak dan reload | Pulih menjadi daftar kosong | | | |
| 10 | Klik favorit berulang lalu pindah route | Badge dan isi favorit konsisten | | | |
| 11 | Gunakan Tab dan Enter | Fokus terlihat dan kontrol dapat digunakan | | | |
| 12 | Refresh /products/1 pada server tujuan | Halaman detail terbuka dengan fallback | | | |
| 13 | Uji filter kategori setelah tugas selesai | q dan category tetap terjaga | | | |
| 14 | Uji Hapus semua setelah tugas selesai lalu reload | Badge 0 dan daftar kosong tetap tersimpan | | | |

Kasus 12 dapat diberi status belum diuji bila belum tersedia server tujuan.
Catat terpisah hasil refresh pada Vite dev atau preview; itu bukan bukti konfigurasi hosting produksi.
