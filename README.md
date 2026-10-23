# Jelajah IPA — Interactive 3D Virtual Lab SMP

Media belajar IPA berbasis HTML, CSS, JavaScript, dan Three.js. Antarmuka terinspirasi dari meja kerja laboratorium interaktif: kanvas 3D besar di tengah, panel ringkasan dan kontrol di kanan, rail ikon di kiri, serta kartu pelajaran horizontal di bagian bawah.

## Pengalaman antarmuka

- **Kanvas eksperimen utama:** objek 3D yang dapat diputar dengan drag, di-zoom dengan scroll, dan di-reset menggunakan toolbar.
- **Panel kanan bertab:** Ringkasan, Variabel, Data, dan Materi.
- **Kontrol cepat:** setiap bab memiliki kontrol ringkas yang tetap terlihat sambil mengamati model 3D.
- **Catatan eksperimen:** rekam kondisi yang diuji dan buka tab Data untuk membaca kembali pengamatan.
- **Navigasi pelajaran:** deretan kartu bab di bawah untuk berpindah laboratorium dengan cepat.
- **Tampilan responsif:** panel kontrol berpindah ke bawah viewport pada layar sempit.

## Laboratorium per bab

- **Buku 1a Bab 1 — Hakikat Sains dan Metode Ilmiah:** greenhouse virtual; atur cahaya, air, nutrien, dan catat hasil model.
- **Buku 1a Bab 2 — Zat dan Perubahannya:** wadah partikel 3D; ubah energi dan amati gerak pada model padat, cair, dan gas.
- **Buku 1a Bab 3 — Gerak Benda dan Gaya:** kendaraan 3D di lintasan; atur kecepatan awal, percepatan, dan waktu.
- **Buku 2a Bab 1 — Pengenalan Sel:** model sel hewan/tumbuhan; klik struktur untuk mempelajari fungsi organel.
- **Buku 2a Bab 2 — Struktur dan Fungsi Tubuh Makhluk Hidup:** model tubuh dan jalur sistem pernapasan, peredaran darah, pencernaan, dan ekskresi.
- **Buku 3a Bab 1 — Sistem Koordinasi dan Zat Adiktif:** model kepala, organ indra, ragam rangsangan, dan pilihan aman.
- **Buku 3a Bab 2 — Homeostasis:** model tubuh dan indikator suhu, cairan, atau glukosa.
- **Buku 3a Bab 3 — Sistem Reproduksi Manusia:** simulator visual tahapan pembelahan sel.
- **Buku 3a Bab 4 — Pewarisan Sifat:** model DNA, kombinasi alel, dan kotak Punnett yang dihitung langsung.
- **Buku 3a Bab 5 — Tekanan:** model benda, cairan, dan gas untuk eksperimen tekanan.

## Menjalankan secara lokal

Three.js dimuat sebagai JavaScript module dari CDN, jadi koneksi internet diperlukan. Cara yang paling andal adalah menjalankan server lokal (bukan membuka HTML lewat `file://`):

```bash
py -m http.server 8000
```

Jalankan dari folder yang berisi `index.html`, kemudian buka `http://localhost:8000`. Bila modul 3D tidak tersedia, skema 2D dapat dibuka dari area eksperimen.

## Publikasi GitHub Pages

Repository ini menggunakan file statis dan tidak memerlukan proses build:
1. Pastikan `index.html` dan `README.md` berada di root branch `main`.
2. Buka **Settings → Pages**.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/(root)`, lalu simpan.
5. Buka URL yang diberikan GitHub Pages setelah deployment selesai.

## Penyimpanan dan batas simulasi

- Variabel eksperimen, XP, progres bab, dan catatan disimpan di `localStorage` browser/perangkat yang sama. Belum ada akun, sinkronisasi antargawai, atau dashboard guru.
- Simulasi tanaman, gerak tubuh, homeostasis, dan beberapa visual lain adalah model konseptual sederhana; bukan data eksperimen nyata atau alat diagnosis.
- Model 3D dibuat secara prosedural untuk pembelajaran; tidak dimaksudkan menggantikan alat praktikum atau mikroskop nyata.
- Materi mengikuti daftar isi diktat IPA 1a, 2a, dan 3a yang diberikan.
