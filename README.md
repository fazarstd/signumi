# Signumi — Paket website statis

Demo konsep website oleh FAZARSTD. Paket berisi HTML, CSS, JavaScript, dan gambar.
Tidak perlu npm, proses build, database, atau konfigurasi ChatGPT Sites.

## GitHub Pages

1. Ekstrak ZIP ini.
2. Buat repository GitHub atau buka repository tujuan.
3. Upload seluruh isi hasil ekstraksi ke direktori utama repository, termasuk folder assets. Pastikan index.html berada di direktori utama, bukan di dalam folder pembungkus. Jangan hanya mengunggah file ZIP.
4. Commit perubahan ke branch main (atau branch yang Anda gunakan).
5. Buka Settings → Pages.
6. Pada Build and deployment, pilih Deploy from a branch.
7. Pilih branch main dan folder / (root), lalu Save.
8. Tunggu deployment selesai, lalu buka alamat website yang ditampilkan GitHub.

Path aset relatif sehingga mendukung GitHub Pages dengan subfolder nama repository.

## Cloudflare Pages — Direct Upload

1. Buka dashboard Cloudflare → Workers & Pages.
2. Pilih Create application → Get started → Drag and drop your files pada alur Pages.
3. Beri nama proyek, lalu unggah ZIP ini atau folder hasil ekstraksinya.
4. Pilih Deploy site dan buka alamat pages.dev yang diberikan.

Paket sudah siap unggah: tidak perlu menjalankan build.
Jika ingin deployment otomatis dari GitHub, buat proyek Pages dengan Git integration sejak awal. Proyek Direct Upload tidak dapat langsung diubah menjadi Git integration; perlu proyek baru.

## Pratinjau dan pengeditan

- Buka index.html di browser untuk pratinjau lokal.
- index.html: konten dan struktur halaman.
- styles.css: warna, tipografi, dan tata letak responsif.
- app.js: menu seluler, tab layanan, dialog inspirasi, dan pembuat pesan WhatsApp.
- assets/hero.png: ilustrasi utama website.
- .nojekyll: menandai situs statis untuk GitHub Pages.

Google Fonts dimuat melalui internet. Jika tidak tersedia, browser menggunakan Arial/sans-serif.
Formulir menyiapkan pesan untuk ditinjau. Pengguna perlu menekan tombol WhatsApp dan mengirim sendiri pesannya; tidak ada penyimpanan data atau pengiriman otomatis.
Nomor tujuan saat ini 0821-8888-7226, sesuai bio Instagram Signumi saat pembuatan konsep. Cari 6282188887226 di app.js untuk mengubahnya.

Label demo, penjelasan ilustrasi, dan meta noindex tetap dipertahankan. noindex bukan pembatas akses: website dapat diakses publik setelah Anda menerbitkannya. Paket ekspor tidak membawa akses privat dari demo ChatGPT Sites.

## Pemeriksaan paket

File utama, referensi aset lokal, anchor bagian, sintaks JavaScript, serta integritas ZIP telah diperiksa. Belum dilakukan pengujian visual browser atau deployment ke akun GitHub/Cloudflare Anda.

## Dokumentasi resmi

- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://developers.cloudflare.com/pages/get-started/direct-upload/

Panduan disiapkan 5 Oktober 2026.
