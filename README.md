# Dashboard Operasional WTP

Dashboard HTML interaktif untuk monitoring kinerja WTP dengan filter **Nama WTP**, **Tanggal Mulai**, dan **Tanggal Akhir**.

## Isi paket

- `index.html` — file utama dashboard dan wajib berada di root repository GitHub Pages.
- `.nojekyll` — mencegah GitHub Pages memproses file sebagai situs Jekyll.
- `README.md` — petunjuk singkat penggunaan.
- `UPLOAD_KE_GITHUB.md` — panduan unggah dan pembaruan.

## Cara membuka secara lokal

Klik dua kali `index.html`. Dashboard tidak memerlukan instalasi atau koneksi ke database eksternal karena data saat ini sudah tertanam di dalam file HTML.

## Catatan pembaruan data

Versi ini menggunakan database yang tertanam di `index.html`. Ketika database Excel berubah, `index.html` perlu dibuat ulang lalu menggantikan file lama di GitHub.

## Privasi

Data dashboard akan dapat diakses publik apabila repository atau GitHub Pages bersifat publik. Jangan unggah file sumber Excel yang bersifat rahasia ke repository publik.
