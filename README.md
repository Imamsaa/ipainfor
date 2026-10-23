# Jelajah IPA — Interactive Virtual Lab SMP

Web lab IPA berbasis HTML, CSS, JavaScript, dan Three.js. Setiap bab memiliki visualisasi 3D yang dapat diputar dan di-zoom, kontrol eksperimen, hasil yang merespons parameter, dan buku catatan pengamatan.

## Laboratorium 3D

- **Buku 1a Bab 1 — Hakikat Sains dan Metode Ilmiah:** greenhouse virtual; atur cahaya, air, nutrien, dan catat hasil model.
- **Buku 1a Bab 2 — Zat dan Perubahannya:** wadah partikel 3D; ubah energi dan amati gerak pada model padat, cair, dan gas.
- **Buku 1a Bab 3 — Gerak Benda dan Gaya:** kendaraan 3D di lintasan; atur kecepatan awal, percepatan, dan waktu.
- **Buku 2a Bab 1 — Pengenalan Sel:** model sel hewan/tumbuhan; klik struktur untuk mempelajari fungsi organel.
- **Buku 2a Bab 2 — Struktur dan Fungsi Tubuh Makhluk Hidup:** model tubuh dan jalur sistem pernapasan, peredaran darah, pencernaan, dan ekskresi.
- **Buku 3a Bab 1 — Sistem Koordinasi dan Zat Adiktif:** model kepala, organ indra, dan ragam rangsangan.
- **Buku 3a Bab 2 — Homeostasis:** model tubuh, organ, dan indikator suhu/cairan/glukosa.
- **Buku 3a Bab 3 — Sistem Reproduksi Manusia:** simulator visual tahapan pembelahan sel.
- **Buku 3a Bab 4 — Pewarisan Sifat:** DNA heliks, kombinasi alel, dan kotak Punnett yang dihitung langsung.
- **Buku 3a Bab 5 — Tekanan:** model benda, cairan, dan gas untuk eksperimen tekanan.

### Kontrol lab

- **Drag mouse / sentuh lalu geser:** putar model 3D.
- **Scroll / gerakan zoom:** mendekatkan dan menjauhkan kamera.
- **Klik bagian model tertentu:** pilih struktur, node jalur organ, atau kombinasi genetika.
- **Panel eksperimen:** ubah variabel dan lihat hasil model diperbarui.
- **Rekam eksperimen:** simpan kondisi dan hasil ke buku pengamatan lokal.

## Menjalankan secara lokal

Karena halaman memakai ES module Three.js dari CDN, cara yang paling andal adalah menjalankan server lokal (bukan membuka HTML melalui `file://`):

```bash
python -m http.server 8000
```

Jalankan perintah di folder yang berisi `index.html`, lalu buka `http://localhost:8000`. Koneksi internet diperlukan untuk mengambil Three.js dari CDN. Bila modul 3D tidak tersedia, skema 2D tersedia sebagai alternatif pada masing-masing lab.

## Publikasi GitHub Pages

Repository sudah menggunakan file statis, jadi tidak memerlukan langkah build:
1. Pastikan `index.html` dan `README.md` ada di root branch `main`.
2. Buka **Settings → Pages**.
3. Pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu simpan.
4. Setelah selesai, buka URL yang ditampilkan GitHub Pages.

## Penyimpanan dan batas simulasi

- Variabel eksperimen, XP, dan catatan disimpan di `localStorage` browser/perangkat yang sama. Belum ada akun, sinkronisasi daring, atau dashboard guru.
- Simulasi tanaman dan homeostasis adalah model konseptual sederhana. Hasilnya bukan data eksperimen nyata atau alat diagnosis.
- Model 3D dibuat secara prosedural untuk pembelajaran; tidak dimaksudkan menggantikan praktikum, mikroskop asli, atau alat ukur nyata.
- Materi mengikuti daftar isi diktat IPA 1a, 2a, dan 3a yang diberikan.
