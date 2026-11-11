BRILink Smart Kasir V2 - Modern Fintech UI

Isi paket:
- index.html: aplikasi dengan tampilan Light/Dark modern fintech.
- assets/: lima logo sumber saldo yang diberikan pengguna.
- manifest.json, sw.js, icons/: dukungan instalasi PWA.

Cara pasang GitHub Pages:
1. Ekstrak ZIP.
2. Upload/replace index.html, manifest.json, sw.js, folder assets, dan folder icons ke folder utama repository GitHub Pages.
3. Commit changes.
4. Buka ulang website. Jika tampilan lama masih muncul, lakukan hard refresh (Ctrl+Shift+R) atau tutup-buka aplikasi.

Catatan:
- Integrasi Firebase dan alur transaksi dari file sumber dipertahankan.
- Tema tersimpan di perangkat masing-masing (Light/Dark).
- Dropdown sumber saldo dan jenis transaksi pada form Catat Transaksi menggunakan logo/ikon.
- CDN Tailwind, Firebase, dan Lucide memerlukan koneksi internet.
- Backup data sebelum mengganti file di repository.

CATATAN PERBAIKAN TRANSFER INTERNAL
- Transfer baru: saldo sumber berkurang sebesar nominal + biaya; saldo tujuan bertambah sebesar nominal.
- Biaya transfer mengurangi saldo sumber dan tetap dihitung sebagai biaya pada ringkasan profit.
- Transfer lama (tanpa ledgerVersion 2) tetap memakai rumus lama hanya saat dampaknya dibalik ketika diedit/dihapus, agar saldo tidak salah dibalik.
- Saat transfer lama diedit, dampak lama dibalik, lalu data baru diterapkan memakai logika yang benar.
- Saldo historis tidak dikoreksi otomatis. Rekonsiliasikan saldo aktual terlebih dahulu; jangan melakukan koreksi massal tanpa backup.
