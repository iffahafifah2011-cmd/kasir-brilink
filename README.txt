BRILink Smart Kasir V2 - Update Koreksi Saldo Digital & Cash

PERUBAHAN:
1. Saldo Digital:
   - Setelah koreksi, saldo tercatat aplikasi disamakan dengan saldo real yang diinput.
   - Kolom saldo real yang dikoreksi otomatis dikosongkan untuk pemeriksaan berikutnya.
   - Riwayat pemeriksaan/koreksi tetap tersimpan.
   - Hasil pemeriksaan lama tidak lagi ditampilkan sebagai saldo real aktif jika saldo aplikasi sudah berubah setelah pemeriksaan.
   - Akun digital yang tidak diisi tetap dianggap sama dengan saldo aplikasi hanya untuk ringkasan; tidak ikut dikoreksi.
2. Cash:
   - Koreksi menyamakan saldo cash aplikasi dengan total pecahan real.
   - Rincian pecahan tetap disimpan setelah koreksi.
   - Jika saldo cash berubah karena transaksi/mutasi setelah pemeriksaan terakhir, ringkasan menampilkan "Perlu hitung ulang" alih-alih menampilkan selisih lama sebagai kurang/lebih baru.
   - Riwayat pemeriksaan dan koreksi tetap tersimpan.
3. Koreksi tidak mengubah laba transaksi.
4. Versi cache Service Worker dinaikkan ke v10.

PEMASANGAN:
1. Ekstrak ZIP.
2. Upload seluruh isi folder brilink-smart-kasir-modern ke root repository GitHub Pages.
3. Replace file lama jika diminta.
4. Commit perubahan.
5. Refresh aplikasi dengan Ctrl + Shift + R.

CATATAN:
- Tetap menggunakan Firebase dan struktur data yang sama.
- Jangan reset Firebase atau mengganti PIN.
- Setelah update, uji dulu dengan nominal kecil dan pastikan kolom saldo real digital kosong setelah koreksi.
