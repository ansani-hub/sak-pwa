# SAK PWA V1

## Yang sudah aktif
- Beranda dan saldo otomatis
- Tambah pemasukan/pengeluaran
- IndexedDB offline-first
- Daftar, pencarian, filter tipe
- Detail, edit, hapus transaksi
- Laporan ringkas
- Backup/Restore JSON
- Export CSV
- PWA manifest + service worker

## Cara menjalankan
1. Install Python 3.
2. Extract ZIP ini.
3. Buka Terminal/CMD pada folder hasil extract.
4. Jalankan:
   python -m http.server 8080
5. Laptop: buka http://localhost:8080
6. HP pada Wi-Fi yang sama: buka http://IP-LAPTOP:8080

Untuk PWA install/offline penuh di HP, deploy ke hosting HTTPS. Contoh static hosting: GitHub Pages, Netlify, atau Cloudflare Pages.

## Cara install di HP
Setelah URL HTTPS online:
Chrome Android -> buka URL SAK -> menu ⋮ -> Install app / Add to Home screen.

## Catatan
Starter ini sengaja memprioritaskan core flow. Excel/PDF, receipt photo, kategori CRUD, PIN/biometric, filter periode lengkap, dan polish visual menjadi tahap berikutnya sebelum rilis.
