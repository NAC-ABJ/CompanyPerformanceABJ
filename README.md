# Dashboard WTP – Update Data Melalui Excel

Dashboard ini membaca data langsung dari file `database.xlsx`.

## File yang diunggah pertama kali

- `index.html`
- `database.xlsx`
- `.nojekyll`
- `README.md`
- `UPLOAD_KE_GITHUB.md`

## File yang diganti saat data diperbarui

Setelah pemasangan pertama, cukup ganti:

- `database.xlsx`

Jangan mengganti nama file menjadi `database (1).xlsx` atau nama lain.

## Struktur sheet wajib

Nama sheet harus tetap tersedia:

- `BU 1,2`
- `B3`
- `P1`
- `P2`

Tambahkan data baru di bawah data lama dan jangan menggeser urutan kolom yang sudah digunakan dashboard.

## Setelah upload Excel baru

1. Tunggu GitHub Pages selesai melakukan deployment.
2. Buka website dashboard.
3. Klik **Muat Ulang Data**, atau tekan `Ctrl + Shift + R`.
