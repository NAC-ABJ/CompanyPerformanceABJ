# Cara Update Data Dashboard di GitHub

## Pemasangan pertama

1. Ekstrak ZIP ini.
2. Buka repository GitHub dashboard.
3. Upload seluruh isi folder ke root repository.
4. Pastikan `index.html` dan `database.xlsx` berada pada lokasi yang sama.
5. Commit perubahan.
6. Aktifkan GitHub Pages dari branch `main` dan folder `/(root)`.

## Update data berikutnya

1. Buka file Excel sumber.
2. Tambahkan data terbaru tanpa mengubah nama sheet dan susunan kolom.
3. Simpan file dengan nama tepat: `database.xlsx`.
4. Di repository GitHub, klik **Add file → Upload files**.
5. Upload `database.xlsx` terbaru pada root repository.
6. Commit dengan pesan, misalnya: `Update database WTP 20 Juli 2026`.
7. Setelah deployment selesai, buka dashboard dan klik **Muat Ulang Data**.

## File yang tidak perlu diupload ulang

- `index.html`
- `.nojekyll`
- `README.md`
- `UPLOAD_KE_GITHUB.md`

File tersebut hanya perlu diganti apabila desain atau fungsi dashboard diubah.

## Jika dashboard gagal membaca data

Periksa:

- Nama file harus `database.xlsx`.
- File harus satu folder dengan `index.html`.
- Nama sheet harus `BU 1,2`, `B3`, `P1`, dan `P2`.
- Susunan kolom tidak boleh dipindahkan.
- File harus disimpan dalam format `.xlsx`, bukan `.xls` atau CSV.
