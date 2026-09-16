# Laporan Survei Petani Perempuan NTT — GitHub Pages

Paket ini siap dipublikasikan sebagai situs statis GitHub Pages.

## Cara unggah melalui situs GitHub

1. Buat repository baru di GitHub, misalnya `survey-ntt-2026`.
2. Ekstrak ZIP ini.
3. Unggah **isi folder hasil ekstraksi** ke bagian paling atas repository. Pastikan `index.html` terlihat di root, bukan berada di dalam subfolder lain.
4. Buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main`, folder `/ (root)`, lalu klik **Save**.
7. Setelah proses deployment selesai, situs tersedia pada alamat:
   `https://USERNAME.github.io/NAMA-REPOSITORY/`

## Catatan

- WebGIS memerlukan koneksi internet untuk memuat Leaflet, OpenStreetMap, dan citra satelit Esri.
- Jangan mengubah nama `index.html`.
- File `.nojekyll` sengaja disertakan agar GitHub Pages menyajikan berkas statis tanpa pemrosesan Jekyll.
- Jika peta belum muncul sesaat setelah halaman dibuka, muat ulang halaman dan pastikan browser tidak memblokir sumber eksternal.

