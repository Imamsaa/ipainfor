# Kuis IPA — 100 Soal SMP

Website kuis IPA sederhana dan responsif untuk latihan mandiri siswa kelas 7, 8, dan 9.

## Isi kuis

Ada tepat **100 soal pilihan ganda** yang dibagi merata menjadi 10 soal untuk setiap bab:

| Kelas | Buku | Materi | Jumlah |
|---|---|---|---:|
| 7 | Buku 1A | Hakikat Ilmu Sains dan Metode Ilmiah | 10 |
| 7 | Buku 1A | Zat dan Perubahannya | 10 |
| 7 | Buku 1A | Gerak Benda dan Gaya | 10 |
| 8 | Buku 2A | Pengenalan Sel | 10 |
| 8 | Buku 2A | Struktur dan Fungsi Tubuh Makhluk Hidup | 10 |
| 9 | Buku 3A | Sistem Koordinasi dan Zat Adiktif | 10 |
| 9 | Buku 3A | Homeostasis | 10 |
| 9 | Buku 3A | Sistem Reproduksi Manusia | 10 |
| 9 | Buku 3A | Pewarisan Sifat | 10 |
| 9 | Buku 3A | Tekanan | 10 |
| | | **Total** | **100** |

Label kelas mengikuti pengelompokan buku/materi yang dibahas sebelumnya: Buku 1A untuk kelas 7, Buku 2A untuk kelas 8, dan Buku 3A untuk kelas 9.

## Penyimpanan sesi dan tampilan kuis

- Sesi kuis, urutan soal yang diacak, pilihan jawaban, status jawaban sudah diperiksa, posisi soal aktif, dan hasil disimpan pada `localStorage` browser.
- Jika halaman tidak sengaja di-refresh, sesi yang sedang berjalan dipulihkan pada soal yang sama.
- Jika pengguna kembali ke beranda sebelum selesai, tombol **Lanjutkan sesi** dapat membuka kembali sesi tersimpan.
- Sesi disimpan secara lokal pada browser/perangkat yang sama. Data tidak otomatis tersinkron antarperangkat atau antarbrowser; menghapus data situs/browser dapat menghapus sesi.
- Saat mode kuis aktif, halaman dirancang agar soal dan pilihan pas dalam tinggi layar tanpa menggulir seluruh halaman. Ukuran font pilihan jawaban juga diperbesar dan tata letak menyesuaikan layar kecil.

## Fitur

- Urutan 100 soal diacak setiap kali sesi baru dimulai.
- Opsi jawaban setiap soal juga diacak, tanpa mengubah kunci jawaban.
- Setiap soal menampilkan label kelas, bab, dan kelompok buku.
- Terdapat empat pilihan jawaban, pemeriksaan jawaban, dan penjelasan.
- Progres sesi ditampilkan pada bilah kemajuan.
- Hasil akhir berisi skor keseluruhan, ringkasan per kelas, dan hasil per bab.
- Sesi ulang untuk semua soal atau hanya soal yang salah.
- Desain clean, responsif di desktop dan ponsel.
- Tidak memakai framework, server, database, atau proses build.

## Menjalankan

Unduh ZIP repository, ekstrak, lalu buka `index.html` di Chrome, Edge, atau Firefox. Semua kuis tersimpan di dalam file HTML sehingga dapat digunakan secara lokal tanpa koneksi internet.

## Catatan

Bank soal ini merupakan latihan pilihan ganda yang dirancang berdasarkan cakupan daftar isi yang dibahas. Guru tetap dapat meninjau istilah, kedalaman, dan pemetaan kelas sebelum dipakai sebagai penilaian resmi.


## Batas kesesuaian materi

Bank soal ditujukan untuk siswa SMP pada Kurikulum Merdeka (IPA Fase D). Soal harus mengukur materi yang tercantum pada daftar isi dan yang sudah diajarkan, bukan pengetahuan tambahan yang belum dipelajari.

- Utamakan bahasa sederhana, konsep inti, contoh sehari-hari, dan penerapan satu langkah.
- Hindari detail mekanisme tingkat lanjut, istilah yang belum dikenalkan, rumus panjang, serta perhitungan bertahap yang belum diajarkan.
- Setiap soal harus sesuai dengan bab dan label kelasnya; opsi pengecoh tetap masuk akal, tetapi tidak mengandalkan jebakan bahasa.
- Pembahasan harus singkat, membantu belajar, dan menggunakan istilah yang sesuai dengan materi siswa.
- Pemetaan per kelas mengikuti daftar isi/bahan ajar sekolah yang diberikan guru. Capaian Pembelajaran IPA Fase D secara nasional mencakup kelas VII–IX, sedangkan urutan dan kedalaman per kelas ditetapkan melalui perencanaan pembelajaran sekolah.
- Sebelum dipakai sebagai penilaian resmi, guru meninjau kesesuaian soal dengan materi yang sudah disampaikan di kelas.
