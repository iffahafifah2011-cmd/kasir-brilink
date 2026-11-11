BRILink Smart Kasir V2 - Update Tombol Lunasi Penuh

ISI UPDATE:
- Menambahkan tombol "Lunasi penuh" pada setiap rincian piutang yang masih memiliki sisa.
- Tombol mencatat pelunasan sebesar seluruh sisa piutang secara langsung.
- Sumber penerimaan dan tanggal mengikuti pilihan pada formulir "Catat pelunasan berdasarkan ID piutang".
- Input nominal pembayaran pada formulir tetap tersedia untuk pembayaran sebagian.
- Pembayaran masuk ke saldo Cash/digital sesuai sumber yang dipilih dan tercatat pada riwayat pelunasan.
- Cache service worker diperbarui agar browser mengambil versi aplikasi terbaru.

PEMASANGAN:
1. Ekstrak ZIP.
2. Upload seluruh isi folder brilink-smart-kasir-modern ke root repository GitHub Pages.
3. Replace file lama jika diminta.
4. Commit perubahan.
5. Refresh aplikasi dengan Ctrl + Shift + R.

CATATAN:
- Firebase dan struktur data lama tetap digunakan.
- Tombol Lunasi penuh menggunakan sumber dan tanggal yang dipilih pada formulir pelunasan.
- Untuk pembayaran sebagian, tetap gunakan kolom Nominal pembayaran dan tombol Simpan pelunasan.

Update layout Saldo & Cash: pada layar lebar, kartu Cash berdasarkan pecahan kini sejajar dengan kartu Saldo Digital dan memiliki lebar yang sama. Pada layar kecil, kedua kartu tersusun vertikal agar tetap nyaman digunakan.
