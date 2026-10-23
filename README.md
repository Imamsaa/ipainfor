# Jelajah IPA — Presentasi Interaktif SMP

Web presentasi pembelajaran IPA bertema sekolah yang cerah, disusun mengikuti daftar isi Diktat IPA Jawara 1a, 2a, dan 3a.


## Presentasi PPT asli sebagai rangkaian slide

Pada Bab 1 **Hakikat Ilmu Sains dan Metode Ilmiah**, presentasi SlideShare tidak lagi ditampilkan sebagai halaman berisi banyak teks. Web menampilkan **28 slide asli satu per satu** sebagai gambar besar dari CDN SlideShare, dengan tombol sebelumnya/berikutnya, indikator slide, dan tautan ke sumber. Setelah slide ke-28, navigasi langsung masuk ke 5 soal kuis berbasis materi.

Gambar dicoba pada ukuran tinggi terlebih dahulu, lalu diturunkan ke ukuran yang lebih kecil jika sumber tidak menyediakan ukuran tersebut. Koneksi internet diperlukan karena slide dimuat langsung dari SlideShare. Ini adalah tampilan slide sebagai gambar, bukan file PowerPoint yang diunduh ke proyek dan bukan pemutar PPTX mandiri; pengguna tetap bisa membuka sumber aslinya.

Sumber: [Hakikat ilmu sains dan metode ilmiah.pptx — SlideShare](https://www.slideshare.net/slideshow/hakikat-ilmu-sains-dan-metode-ilmiahpptx/259870373).

## Gambar pembelajaran dari internet

Cover setiap bab dan slide pendalaman menampilkan foto atau diagram sains dari Wikimedia Commons yang sesuai dengan topik—misalnya mikroskop, model partikel, Hukum Newton, struktur sel, sistem pencernaan, saraf, homeostasis, DNA, dan tekanan fluida.

Setiap gambar mencantumkan kredit, lisensi, dan tautan sumber di dekat gambar. Gambar ditampilkan dari server Wikimedia Commons, jadi koneksi internet dibutuhkan agar gambar dapat dimuat. Jika gambar cover gagal dimuat, ilustrasi SVG lokal tetap ditampilkan sebagai fallback. Tautan sumber membuka halaman sumber gambar, tempat detail lisensi dan versi resolusi lain dapat diperiksa.


## Gambar lebih besar dan mode perbesar

Gambar di cover bab dibuat lebih besar, dan gambar pada slide pendalaman memakai area yang lebih lebar/tinggi. Klik atau ketuk gambar untuk membukanya di lightbox hampir layar penuh. Viewer mencoba memuat berkas resolusi asli Wikimedia Commons, lalu memakai thumbnail sebagai fallback bila gambar aslinya gagal dimuat. Kredit, lisensi, dan tautan sumber tetap tersedia.

## Isi presentasi

Terdapat 126 entri slide navigasi, termasuk halaman pembuka, 28 slide gambar dari PPT SlideShare, dan kuis. Setiap bab memiliki:
1. Pembuka dan pertanyaan pemantik.
2. Konsep inti.
3. Peta materi.
4. Beberapa slide pendalaman submateri yang memuat konsep, contoh, rumus jika sesuai, gambar, dan pertanyaan refleksi.
5. Aktivitas/diskusi kelas.
6. Kuis pilihan ganda dengan umpan balik.

## Bab dan cakupan

### Buku 1a — IPA Dasar
1. **Hakikat Ilmu Sains dan Metode Ilmiah:** sains, observasi dan inferensi, laboratorium dan keselamatan kerja, rancangan percobaan, variabel, pengukuran, besaran pokok dan turunan, konversi dan awalan satuan, pelaporan data.
2. **Zat dan Perubahannya:** model partikel, wujud zat, perubahan wujud, perubahan fisika dan kimia, campuran serta metode pemisahannya.
3. **Gerak Benda dan Gaya:** jarak dan perpindahan, kelajuan/kecepatan/percepatan, GLB dan GLBB, rumus dasar, grafik, percobaan gerak, gaya, dan Hukum Newton.

### Buku 2a — Biologi
4. **Pengenalan Sel:** mikroskop, struktur sel, sel hewan/tumbuhan, spesialisasi sel, jaringan, organ, dan sistem organ.
5. **Struktur dan Fungsi Tubuh Makhluk Hidup:** nutrien, zat aditif, diet sehat, pencernaan, peredaran darah, pernapasan, ekskresi, gangguan dan pemeliharaan kesehatan.

### Buku 3a — Sistem dan Fisika
6. **Sistem Koordinasi dan Zat Adiktif:** jalur rangsangan-respons, indra, hormon, zat adiktif, risiko, dan pencegahan.
7. **Homeostasis:** umpan balik, suhu tubuh, keseimbangan cairan, dan pengaturan glukosa.
8. **Sistem Reproduksi Manusia:** pembelahan sel, organ, pubertas, proses reproduksi, kesehatan, penyakit, dan pencegahan.
9. **Pewarisan Sifat:** istilah genetika, kromosom-DNA-gen, ekspresi gen, monohibrid/dihibrid, dan bioteknologi.
10. **Tekanan:** tekanan zat padat, cair, gas, rumus, dan penerapan pada makhluk hidup.

## Fitur mengajar

- Navigasi bab dan pencarian materi.
- Tombol sebelumnya/berikutnya dan indikator slide.
- Mode presentasi layar penuh.
- Catatan guru.
- Pertanyaan diskusi dengan panduan jawaban.
- Kuis pilihan ganda dengan penjelasan.
- Pintasan keyboard: **→ / spasi** untuk maju, **←** untuk mundur, **Home** untuk pembuka, **End** untuk slide terakhir, dan **N** untuk catatan guru.
- Tidak memerlukan framework atau proses build.

## Menjalankan secara lokal

Unduh ZIP dari repository lalu ekstrak. Buka `index.html` dengan Chrome, Edge, atau Firefox. Untuk menjalankan melalui server lokal:

```bash
py -m http.server 8000
```

Buka `http://localhost:8000`.

## Referensi guru

- [Panduan Mata Pelajaran IPA Fase D (2025)](https://kurikulum.kemendikdasmen.go.id/file/panduan/dokumen/8.%20Final%20Panduan%20Mata%20Pelajaran%20IPA_16_OKT_2025_revisi%204.pdf)
- [Buku IPA Kelas VII Edisi Revisi](https://static.sc.cloudapp.web.id/content/pdf/bukuteks/kurikulum21/IPA_BS_KLS_VII_Rev.pdf)
- [Buku IPA Kelas VIII Edisi Revisi](https://static.sc.cloudapp.web.id/content/pdf/bukuteks/kurikulum21/IPA_BS_KLS_VIII_Rev.pdf)
- [Buku IPA Kelas IX Edisi Revisi](https://static.sc.cloudapp.web.id/content/pdf/bukuteks/kurikulum21/IPA_BS_KLS_IX_Rev.pdf)

Pembagian bab buku edisi revisi dapat berbeda dari diktat sekolah. Presentasi ini mempertahankan urutan judul dari diktat dan melengkapinya dengan rangkuman ajar, contoh, ilustrasi, aktivitas, serta kuis. Guru perlu menyesuaikan tingkat kedalaman materi dengan tujuan pembelajaran sekolah.
