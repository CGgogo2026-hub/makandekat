# MakanDekat

Landing page statis untuk Milestone 10 Lab Startup Bisnis Digital.

## URL publik
https://cggogo2026-hub.github.io/makandekat/

## Isi
- `index.html`: landing page responsif, copywriting, CTA, FAQ, dan formulir minat.
- Formulir lead dikonfigurasi mengarah ke `Studyflow.planner7@gmail.com` melalui FormSubmit AJAX.
- Pengiriman pertama akan memicu email konfirmasi FormSubmit. Admin harus mengonfirmasi email tersebut agar pengiriman lead rutin aktif. FormSubmit menahan kiriman sampai form dikonfirmasi.
- Kode GA4 sudah disiapkan, tetapi Measurement ID belum dimasukkan sehingga analytics belum aktif.

## Pemeriksaan setelah perubahan
1. Buka URL publik di atas.
2. Kirim satu formulir uji menggunakan data uji milik pengelola.
3. Periksa inbox `Studyflow.planner7@gmail.com`, termasuk folder Spam, lalu klik tautan konfirmasi FormSubmit.
4. Kirim ulang formulir uji untuk memastikan notifikasi lead masuk.

## Mengaktifkan GA4
1. Buka Google Analytics dan pilih Admin.
2. Buat atau pilih property, lalu buat Web Data Stream.
3. Masukkan URL `https://cggogo2026-hub.github.io/makandekat/`.
4. Salin Measurement ID yang berawalan `G-` dari detail stream.
5. Ganti nilai `GA4_MEASUREMENT_ID` pada konfigurasi JavaScript di `index.html` dengan ID yang sebenarnya.
6. Commit perubahan, tunggu GitHub Pages deployment sukses, lalu periksa laporan Realtime GA4.

## Data dan privasi
Tidak ada testimoni, jumlah pengguna, harga tempat makan, rating, atau jam buka yang dibuat-buat. Landing page menjelaskan produk sebagai layanan tahap pengembangan/validasi. Formulir mengumpulkan data kontak dan preferensi hanya setelah pengunjung memberi persetujuan. Data lead dikirim ke alamat admin yang telah dikonfigurasi melalui layanan pihak ketiga FormSubmit.
