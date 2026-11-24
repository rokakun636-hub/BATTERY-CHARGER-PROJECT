# BATTERY CHARGER PROJECT 5.0 – EXTREME EDITION

## Isi proyek
- `index.html` – aplikasi utama
- `manifest.json` – konfigurasi PWA
- `sw.js` – cache/offline dasar
- `icon.svg` – ikon aplikasi

## Deploy gratis di GitHub Pages
Upload semua file ke root repository, lalu commit ke branch `main`. Pastikan Settings > Pages menggunakan Deploy from a branch, `main`, dan `/(root)`.

## Fitur
- Pembacaan persentase dan status charging jika browser mendukung Battery Status API
- Charging screen dan jam digital
- Grafik riwayat level baterai lokal
- Tema warna dan wallpaper lokal
- Alarm saat ambang baterai lemah/penuh tercapai ketika halaman berjalan
- Efek suara sederhana
- PWA dan cache offline dasar

## Batasan browser
Battery Status API tidak didukung oleh semua browser Android. Suhu, tegangan, arus, kesehatan baterai, dan alarm andal ketika aplikasi tertutup tidak dijamin. Website tidak dapat mempercepat pengisian daya atau mengubah pengaturan hardware baterai. Riwayat disimpan lokal pada browser/perangkat ini.
