# Portofolio Pribadi - Tude Praba

Website portofolio pribadi untuk **Tude Praba**, Front End Web Developer yang berdomisili di Denpasar, Bali. Dibangun dengan HTML, CSS, dan JavaScript murni, tampilan responsif di semua perangkat.

## Struktur Halaman

- **Tentang** — perkenalan singkat, layanan, testimoni, dan klien
- **Resume** — riwayat pendidikan, pengalaman kerja, dan keahlian
- **Portofolio** — daftar proyek dengan filter kategori
- **Blog** — daftar artikel (contoh, bisa diisi tulisan sendiri)
- **Kontak** — peta lokasi dan formulir kontak

## Yang Perlu Diedit Sebelum Publish

File utama yang perlu disesuaikan ada di `index.html`:

1. **Foto profil** — ganti `assets/images/my-avatar.png` dengan foto asli.
2. **Email** — cari `tudepraba@email.com` di bagian sidebar, ganti dengan email aktif.
3. **Riwayat pendidikan & pengalaman** — bagian `Resume` masih placeholder, ganti dengan data asli (nama sekolah/perusahaan, tahun, deskripsi).
4. **Keahlian (skills)** — sesuaikan persentase dan nama skill di bagian `Keahlian Saya`.
5. **Proyek portofolio** — ganti gambar di `assets/images/project-*.jpg/png` dan judul "Nama Proyek 1", "Nama Proyek 2", dst. dengan proyek nyata beserta link jika ada.
6. **Testimoni & Klien** — opsional, bisa diedit atau dihapus jika belum relevan.
7. **Blog** — opsional, bisa diisi tulisan sendiri atau dihapus dari menu navigasi jika tidak dipakai.

> Catatan: formulir kontak di halaman ini hanya tampilan (front end saja) dan belum terhubung ke layanan pengiriman email, karena situs ini nantinya berupa static site di GitHub Pages. Untuk membuatnya benar-benar mengirim pesan, kamu bisa memakai layanan gratis seperti [Formspree](https://formspree.io) atau mengganti tombol kirim dengan link `mailto:`.

## Cara Upload ke GitHub

1. **Buat repository baru** di GitHub, misalnya beri nama `portofolio-tudepraba`. Jangan centang "Add README" karena sudah ada.
2. Buka terminal di folder project ini, lalu jalankan:

   ```bash
   git init
   git add .
   git commit -m "Portofolio awal Tude Praba"
   git branch -M main
   git remote add origin https://github.com/USERNAME-KAMU/portofolio-tudepraba.git
   git push -u origin main
   ```

   Ganti `USERNAME-KAMU` dengan username GitHub kamu.

3. **Aktifkan GitHub Pages**:
   - Buka repository di GitHub → tab **Settings** → menu **Pages** (di sidebar kiri).
   - Pada bagian **Source**, pilih branch `main` dan folder `/ (root)`.
   - Klik **Save**.
   - Tunggu 1-2 menit, lalu website akan bisa diakses di:
     `https://USERNAME-KAMU.github.io/portofolio-tudepraba/`

4. Setiap kali ada perubahan, ulangi:

   ```bash
   git add .
   git commit -m "Update portofolio"
   git push
   ```

## Lisensi

MIT — bebas digunakan dan dimodifikasi untuk keperluan pribadi.
