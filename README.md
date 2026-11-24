# BATTERY CHARGER PROJECT 3.0

Files: index.html (dashboard, alarm penuh/lemah, volume, tes suara, tema, fullscreen, grafik dan riwayat lokal), manifest.json (PWA), sw.js (cache offline), icon.svg.

## Update via Android
1. Ekstrak ZIP.
2. Buka repository BATTERY-CHARGER-PROJECT.
3. Code > Add file > Upload files.
4. Upload/replace index.html, manifest.json, sw.js, icon.svg di root.
5. Commit changes. Pages tetap main / (root).
6. Tunggu deploy lalu tutup tab/app dan buka ulang. Cache service worker menggunakan nama v3.

## Batasan
Battery Status API tidak didukung semua browser. Suhu, voltase, kapasitas mAh dan kesehatan baterai tidak tersedia lewat API web standar. Alarm dan grafik berjalan saat halaman aktif; alarm ketika aplikasi ditutup tidak dijamin. Riwayat lokal hanya merekam sampel berkala selama website dipakai pada browser ini. Notifikasi memerlukan izin. Website tidak mengubah kecepatan atau menghentikan pengisian fisik.
