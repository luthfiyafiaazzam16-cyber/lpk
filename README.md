# Website Company Profile LPK Hanil Japanese Korean Center

Website company profile statis menggunakan HTML5, CSS3, Bootstrap 5.3, Bootstrap Icons

## 1. Cara membuka project
1. Ekstrak file ZIP.
2. Buka folder `lpk-hanil` melalui Visual Studio Code.
3. Buka `index.html` untuk melihat beranda.

## 2. Menjalankan dengan Live Server
1. Buka Visual Studio Code.
2. Pasang ekstensi **Live Server** jika belum tersedia.
3. Klik kanan `index.html`.
4. Pilih **Open with Live Server**.

Website juga dapat dibuka langsung dengan klik dua kali `index.html`. Koneksi internet diperlukan untuk memuat Bootstrap, Bootstrap Icons, dan Google Fonts dari CDN.

## 3. Fungsi file HTML
- `index.html`: Beranda.
- `tentang.html`: Profil, sejarah, visi, dan misi.
- `jepang.html`: Daftar bidang program Jepang.
- `korea.html`: Daftar bidang program Korea.
- `alur-pendaftaran.html`: Tahapan pendaftaran.
- `galeri.html`: Dokumentasi kegiatan.
- `kontak.html`: Alamat dan media sosial.

## 4. Lokasi CSS dan JavaScript
- CSS global: `assets/css/style.css`
- JavaScript minimal: `assets/js/script.js`
- Semua halaman memakai CSS global yang sama.

## 5. Cara mengganti logo
Ganti file `assets/images/logo.svg` dengan logo Anda. Jika menggunakan PNG/JPG, ubah juga nilai `src` logo pada navbar di setiap file HTML (cari `assets/images/logo.svg`). Cara termudah adalah mempertahankan nama file dan format SVG.

## 6. Cara mengganti foto hero
Ganti `assets/images/hero.svg` dengan gambar baru. Jika format gambar berubah menjadi JPG, ubah `src` pada `index.html`. Nama dan format harus sesuai dengan yang ditulis di HTML.

## 7. Cara mengganti foto galeri
Foto galeri berada di `assets/images/galeri/`. Ganti file placeholder dengan foto yang diinginkan dan pertahankan nama file/format, atau ubah atribut `src` pada `galeri.html` dan `index.html`.

## 8. Cara mengganti foto program
Foto program berada di `assets/images/` (misalnya `kaigo.svg`, `manufaktur.svg`, `program-jepang.svg`). Ganti file dengan gambar Anda dan sesuaikan atribut `src` bila format atau nama berubah.

## 9. Mengedit judul dan deskripsi
Buka file HTML halaman yang ingin diedit. Cari teks judul atau paragraf, lalu ubah langsung. Untuk judul tab browser dan SEO, edit elemen `<title>` dan `<meta name="description">` di bagian `<head>`.

## 10. Menambahkan foto galeri baru
1. Salin foto ke `assets/images/galeri/`, misalnya `kelas-bahasa.jpg`.
2. Buka `galeri.html`.
3. Salin satu blok `<div class="col-sm-6 col-lg-4">...</div>` pada bagian galeri.
4. Ubah `src`, `alt`, dan teks caption sesuai foto baru.

## 11. Mengganti data testimoni
Pada `index.html`, cari bagian `CERITA PESERTA` / `Testimoni peserta`. Ganti foto, nama, program/negara, dan isi dengan testimoni asli yang telah mendapat izin publikasi. Hapus kartu placeholder jika belum ada testimoni yang dapat dipublikasikan.

## 12. Mengubah WhatsApp dan media sosial
Nomor WhatsApp digunakan pada tautan `https://wa.me/6289522951158`. Untuk menggantinya, cari teks `6289522951158` di seluruh file HTML dan ubah ke nomor baru dengan kode negara tanpa tanda `+`, spasi, atau angka 0 di depan. Ubah juga tautan Instagram dan YouTube pada navbar/footer atau halaman kontak jika akun berubah.

## Catatan penting
- Gambar SVG yang tersedia adalah placeholder visual, bukan foto dokumentasi asli. Ganti dengan foto resmi sebelum website dipublikasikan.
- Canonical URL di setiap halaman masih menggunakan `https://www.example.com/`. Ganti dengan domain resmi setelah domain tersedia.
- `sitemap.xml` juga memakai domain placeholder.
- Peta kontak disediakan sebagai tautan pencarian Google Maps, bukan embed titik lokasi yang belum dikonfirmasi.
- Informasi biaya, gaji, persyaratan, durasi, kuota, legalitas, mitra, dan jaminan keberangkatan tidak dibuat-buat. Konfirmasikan langsung kepada LPK Hanil.
