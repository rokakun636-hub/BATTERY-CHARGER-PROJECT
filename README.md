# BATTERY CHARGER PROJECT 2.0

## Isi paket
- `index.html` — dashboard profesional, animasi baterai 3D, jam digital, suara, permintaan izin notifikasi, dan pembacaan Battery Status API.
- `manifest.json` — metadata instalasi PWA.
- `sw.js` — cache offline dasar.
- `icon.svg` — ikon aplikasi.

## Update GitHub Pages melalui Android
1. Ekstrak ZIP.
2. Buka repository `BATTERY-CHARGER-PROJECT`.
3. Masuk tab Code.
4. Pilih Add file > Upload files.
5. Unggah ke root repository: `index.html`, `manifest.json`, `sw.js`, `icon.svg`.
6. Jika nama file sudah ada, unggah versi baru dengan nama yang sama dan konfirmasi replace/commit.
7. Tekan Commit changes.
8. Buka Settings > Pages. Pastikan source tetap Deploy from a branch, branch `main`, folder `/(root)`.
9. Tunggu GitHub Pages selesai deploy, lalu buka alamat website dan refresh.

## Catatan fitur
Battery Status API tidak didukung semua browser. Suhu, tegangan, kapasitas mAh, dan battery health tidak tersedia melalui API browser standar. Notifikasi memerlukan izin dan browser/perangkat dapat membatasi notifikasi ketika halaman tertutup. PWA memerlukan HTTPS (GitHub Pages sudah HTTPS).
