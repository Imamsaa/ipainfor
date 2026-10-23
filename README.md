# Jelajah IPA — Presentasi Interaktif SMP

Web presentasi pembelajaran IPA dengan tema sekolah yang cerah. Materi disusun mengikuti urutan daftar isi diktat yang diberikan: Buku IPA 1a, 2a, dan 3a. Setiap bab memiliki lima bagian presentasi, sehingga guru dapat menyampaikan materi secara bertahap dari pertanyaan pembuka sampai kuis pemahaman.

## Isi presentasi

### Buku IPA 1a — IPA Dasar
1. Hakikat Ilmu Sains dan Metode Ilmiah
2. Zat dan Perubahannya
3. Gerak Benda dan Gaya

### Buku IPA 2a — Biologi
4. Pengenalan Sel
5. Struktur dan Fungsi Tubuh Makhluk Hidup

### Buku IPA 3a — Sistem dan Fisika
6. Sistem Koordinasi dan Zat Adiktif
7. Homeostasis
8. Sistem Reproduksi Manusia
9. Pewarisan Sifat
10. Tekanan

## Format setiap bab

- **Pembuka:** tujuan belajar, pertanyaan pemantik, dan ilustrasi.
- **Konsep inti:** gagasan utama dan tiga kartu penjelasan.
- **Jelajahi materi:** tiga bagian konsep beserta contoh sehari-hari.
- **Aktivitas kelas:** kasus diskusi, langkah kegiatan, dan panduan jawaban yang dapat dibuka saat mengajar.
- **Cek pemahaman:** kuis pilihan ganda dengan umpan balik jawaban.

## Fitur presentasi

- Navigasi bab di sisi kiri dan pencarian materi.
- Tombol sebelumnya/berikutnya dan indikator bagian pada setiap bab.
- Mode presentasi layar penuh.
- Catatan guru yang bisa ditampilkan atau disembunyikan.
- Ilustrasi SVG tertanam; tidak membutuhkan file gambar terpisah.
- Progres bab yang selesai mengerjakan kuis disimpan secara lokal di browser.
- Pintasan keyboard: **→ / spasi** untuk maju, **←** untuk mundur, **Home** untuk pembuka, **End** untuk slide terakhir, dan **N** untuk menampilkan/menyembunyikan catatan guru.
- Tidak membutuhkan framework, proses build, atau koneksi internet untuk fitur inti.

## Menjalankan secara lokal

1. Klik **Code → Download ZIP** pada repository dan ekstrak file.
2. Buka `index.html` dengan Chrome, Edge, atau Firefox.

Jika ingin menjalankan lewat server lokal:

```bash
py -m http.server 8000
```

Kemudian buka `http://localhost:8000`.

## Publikasi melalui GitHub Pages

1. Pastikan `index.html` berada di root branch `main`.
2. Buka **Settings → Pages**.
3. Pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu simpan.
4. Setelah deployment selesai, buka URL yang ditampilkan GitHub Pages.

## Catatan materi

Urutan bab dan submateri mengikuti daftar isi diktat IPA yang diberikan. Penjelasan ringkas, contoh sehari-hari, pertanyaan diskusi, dan kuis merupakan bahan ajar pendamping yang disusun untuk membantu guru menjelaskan konsep; bukan salinan lengkap isi buku.
