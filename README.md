# E-Portofolio Refleksi LK 2

Situs statis (HTML, CSS, JavaScript tanpa backend) untuk portofolio refleksi PPG Teknik Mesin.

## Struktur
- `index.html` seluruh situs dalam satu file (beranda, enam mata kuliah, pusat artefak; berpindah halaman lewat #etika, #pse, dst.)
- `dokumen/lk2/` lembar kerja LK 2 dalam PDF (dibuka/diunduh) dan .docx
- `dokumen/<kode>/` tempat berkas artefak per mata kuliah (etika, pse, pma, ppl, pk, elektif)

## Menambahkan artefak
1. Salin berkas ke folder yang sesuai, mis. `dokumen/pse/modul-ajar-mastercam.pdf`.
2. Di `js/data.js`, pada objek `ART`, isi `u` dengan jalur tersebut: `{t:"Modul ajar", u:"dokumen/pse/modul-ajar-mastercam.pdf"}`.
3. Video: isi `u` dengan tautan YouTube atau Google Drive (atur akses "Siapa saja yang memiliki tautan").
Nama berkas: huruf kecil, tanpa spasi, mis. `video-tutorial-toolpath.mp4`. Berkas besar (video) lebih baik ditautkan, bukan disimpan di repositori.

## Mengisi mata kuliah Elektif
Lengkapi entri `elektif` di `MK` (connection, challenge, concept, change, art) lalu hapus `kosong: true`.

## Publikasi dengan GitHub Pages
1. Buat repositori baru di GitHub, unggah seluruh isi folder ini.
2. Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. Tautan situs tampil di halaman Pages; salin ke LMS.
Pembaruan: ubah file, lalu commit; situs diperbarui dalam beberapa menit. Pengunjung tidak dapat mengunggah berkas langsung ke situs ini; semua berkas ditambahkan lewat repositori.
