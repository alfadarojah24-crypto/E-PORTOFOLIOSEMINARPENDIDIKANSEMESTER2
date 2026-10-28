# E-Portofolio Refleksi LK 2

Nurudlucha Alfa Darojah · PPG Teknik Mesin, Universitas Negeri Malang

Situs statis: seluruh halaman ada di satu file `index.html` (tanpa server atau database). Halaman berpindah lewat alamat `#`, misalnya `#pse`, `#pma`, `#ppl`, `#pk`, `#etika`, `#artefak`.

## Isi repositori
- `index.html` situs (beranda, 5 mata kuliah, Pusat Artefak)
- `dokumen/lk2/` lembar kerja LK 2 (PDF dan .docx)
- `dokumen/ppl/` modul ajar, modul Job 2/3/11, dan video praktik
- `dokumen/etika`, `pse`, `pma`, `pk` folder untuk artefak berikutnya
- `.nojekyll` agar GitHub Pages menampilkan file apa adanya

## Menerbitkan di GitHub Pages
1. Buat repositori baru (Public), misalnya `eportofolio`.
2. Add file → Upload files → seret seluruh isi folder ini (termasuk folder `dokumen` dan file `.nojekyll`), lalu Commit changes.
3. Settings → Pages → Source: Deploy from a branch → branch `main`, folder `/ (root)` → Save.
4. Setelah 1-3 menit, alamat situs muncul di halaman Pages (biasanya `https://namaakun.github.io/eportofolio/`). Salin ke LMS.

## Menambah atau mengganti artefak
1. Unggah berkas ke folder yang sesuai di `dokumen/` (nama huruf kecil, tanpa spasi).
2. Buka `index.html` di GitHub (ikon pensil), cari `var ART = {`.
3. Pada artefak yang dimaksud, isi `u:""` dengan jalur berkas, misalnya `u:"dokumen/pk/proposal.pdf"`, atau dengan tautan Google Drive/YouTube (akses "Siapa saja yang memiliki tautan").
4. Commit; situs diperbarui dalam beberapa menit.

Artefak yang masih berstatus "belum diunggah": laporan studi kasus dan jurnal (Etika), modul pembelajaran mendalam (PMA), proposal, laporan akhir, dan modul pelatihan SMAW (Projek Kepemimpinan).

Catatan: berkas maksimal 25 MB per unggahan lewat browser. Video besar sebaiknya ditautkan dari YouTube atau Drive. Pengunjung tidak dapat mengunggah berkas ke situs ini.
