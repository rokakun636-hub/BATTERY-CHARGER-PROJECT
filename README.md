# BATTERY CHARGER PROJECT

Website pemantau baterai Android dengan tampilan dashboard profesional.

## Cara menjalankan
1. Buka `index.html` di browser untuk melihat tampilannya.
2. Untuk menerbitkan gratis, buat repository GitHub bernama `BATTERY-CHARGER-PROJECT`.
3. Upload `index.html` ke root repository.
4. Buka Settings > Pages.
5. Pada Build and deployment, pilih Deploy from a branch.
6. Pilih branch `main`, folder `/(root)`, lalu Save.
7. Tunggu proses selesai. Alamat website akan tampil di bagian GitHub Pages.

## Catatan
Data baterai real-time menggunakan Battery Status API (`navigator.getBattery()`).
API ini tidak didukung oleh semua browser. Browser juga umumnya tidak menyediakan
suhu, tegangan, kapasitas mAh, atau kesehatan baterai. Fitur tersebut ditampilkan
sebagai tidak tersedia bila perangkat/browser tidak memberikannya.
