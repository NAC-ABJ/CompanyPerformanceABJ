# Panduan Upload Dashboard ke GitHub Pages

## A. Membuat repository baru

1. Masuk ke GitHub.
2. Klik **New repository**.
3. Isi nama repository, misalnya `Dashboard-WTP`.
4. Pilih **Public** apabila akan menggunakan GitHub Pages publik.
5. Klik **Create repository**.

## B. Mengunggah file dashboard

Unggah seluruh isi folder ini ke bagian paling luar atau **root** repository:

```text
Dashboard-WTP/
├── index.html
├── .nojekyll
├── README.md
└── UPLOAD_KE_GITHUB.md
```

Langkah unggah:

1. Klik **Add file**.
2. Klik **Upload files**.
3. Tarik semua file di atas ke halaman GitHub.
4. Isi commit message, misalnya `Upload dashboard WTP`.
5. Klik **Commit changes**.

> Pastikan nama file utama tetap `index.html`, bukan `index (1).html`.

## C. Mengaktifkan GitHub Pages

1. Buka **Settings** pada repository.
2. Pilih menu **Pages**.
3. Pada bagian **Build and deployment**, pilih:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/(root)`
4. Klik **Save**.

Alamat website biasanya berbentuk:

```text
https://NAMA-USER.github.io/NAMA-REPOSITORY/
```

## D. Memperbarui dashboard

Karena data tertanam di dalam HTML, pembaruan dilakukan dengan mengganti `index.html`:

1. Siapkan `index.html` terbaru.
2. Buka repository.
3. Klik file `index.html` lama.
4. Pilih **Delete this file**, commit, lalu upload file baru; atau langsung upload file baru dengan nama yang sama dari menu **Add file → Upload files**.
5. Commit perubahan.
6. Buka website dan tekan `Ctrl + F5` atau `Ctrl + Shift + R`.

## E. Pemeriksaan ketika dashboard tidak berubah

- Pastikan file terbaru bernama `index.html`.
- Pastikan file berada di root repository.
- Pastikan GitHub Pages menggunakan branch `main` dan folder `/(root)`.
- Periksa tab **Actions** untuk melihat status deployment.
- Lakukan hard refresh pada browser.
