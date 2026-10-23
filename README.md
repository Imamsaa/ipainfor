# Jelajah IPA — Virtual Lab Interaktif SMP

Media praktikum digital berbasis HTML, CSS, dan JavaScript murni. Setiap bab dari diktat IPA 1a, 2a, dan 3a memiliki ruang eksperimen tersendiri. Siswa dapat mengubah variabel, melihat visualisasi berubah langsung, menjalankan simulasi, membaca penjelasan, dan menyimpan catatan pengamatan.

## Laboratorium per bab

- **1a Bab 1 — Hakikat Sains dan Metode Ilmiah:** rumah kaca virtual untuk mengubah cahaya, air, dan nutrien serta mencatat hasil model.
- **1a Bab 2 — Zat dan Perubahannya:** ruang partikel; ubah energi dan amati model wujud padat, cair, dan gas.
- **1a Bab 3 — Gerak Benda dan Gaya:** atur kecepatan awal, percepatan, dan waktu untuk membandingkan jarak gerak.
- **2a Bab 1 — Pengenalan Sel:** mikroskop digital dengan struktur sel yang dapat dipilih, serta pilihan sel hewan/tumbuhan.
- **2a Bab 2 — Struktur dan Fungsi Tubuh Makhluk Hidup:** telusuri jalur sistem pernapasan, peredaran darah, pencernaan, dan ekskresi.
- **3a Bab 1 — Sistem Koordinasi dan Zat Adiktif:** kirim rangsangan dari beberapa indra dan pelajari respons serta pilihan aman.
- **3a Bab 2 — Homeostasis:** terapkan gangguan model pada suhu, cairan, atau glukosa, lalu aktifkan regulasi.
- **3a Bab 3 — Sistem Reproduksi Manusia:** simulasikan urutan tahap pembelahan sel dan hubungkan dengan pertumbuhan serta kesehatan.
- **3a Bab 4 — Pewarisan Sifat:** ubah genotipe induk dan amati kotak Punnett serta peluang genotipe.
- **3a Bab 5 — Tekanan:** uji tekanan zat padat, cair, dan gas dengan mengubah parameter eksperimen.

Setiap ruang lab berisi panel instrumen, visualisasi, hasil langsung, pertanyaan ilmiah, dan buku catatan pengamatan. XP diberikan ketika siswa merekam eksperimen untuk pertama kali pada bab tersebut.

## Menjalankan secara lokal

1. Unduh repository melalui **Code → Download ZIP**, lalu ekstrak.
2. Buka `index.html` menggunakan Chrome, Edge, atau Firefox.
3. Bila browser membatasi fitur tertentu saat membuka file secara langsung, jalankan server lokal dari folder tersebut:

```bash
python -m http.server 8000
```

Kemudian buka `http://localhost:8000`.

Tidak membutuhkan Node.js, framework, paket tambahan, database, atau koneksi internet untuk fitur inti.

## Publikasi di GitHub Pages

1. Pastikan `index.html` berada di root repository.
2. Buka **Settings → Pages**.
3. Di **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
5. Gunakan URL yang ditampilkan GitHub Pages setelah deployment selesai.

## Catatan

- Pengaturan eksperimen, XP, dan log pengamatan disimpan di `localStorage` browser/perangkat yang sama. Data belum tersinkron antarperangkat maupun ke dashboard guru.
- Simulasi pertumbuhan tanaman, homeostasis, dan beberapa visual lain adalah model pembelajaran sederhana, bukan data eksperimen nyata atau alat diagnosis.
- Virtual lab adalah media belajar dan persiapan konsep; tidak menggantikan praktikum nyata.
- Isi dan pengelompokan materi mengikuti daftar isi diktat IPA yang diberikan.
