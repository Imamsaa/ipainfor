# Kuis IPA — 100 Soal SMP

Website kuis IPA sederhana dan responsif untuk latihan mandiri siswa kelas 7, 8, dan 9.

## Isi kuis

Ada tepat **100 soal pilihan ganda** dengan komposisi 40 soal kelas 7, 40 soal kelas 8, dan 20 soal kelas 9. Pembagian per bab mengikuti banyaknya materi pada setiap kelas:

| Kelas | Buku | Materi | Jumlah |
|---|---|---|---:|
| 7 | Buku 1A | Hakikat Ilmu Sains dan Metode Ilmiah | 13 |
| 7 | Buku 1A | Zat dan Perubahannya | 13 |
| 7 | Buku 1A | Gerak Benda dan Gaya | 14 |
| 8 | Buku 2A | Pengenalan Sel | 20 |
| 8 | Buku 2A | Struktur dan Fungsi Tubuh Makhluk Hidup | 20 |
| 9 | Buku 3A | Sistem Koordinasi dan Zat Adiktif | 4 |
| 9 | Buku 3A | Homeostasis | 4 |
| 9 | Buku 3A | Sistem Reproduksi Manusia | 4 |
| 9 | Buku 3A | Pewarisan Sifat | 4 |
| 9 | Buku 3A | Tekanan | 4 |
| | | **Total** | **100** |

Label kelas mengikuti pengelompokan buku/materi yang dibahas sebelumnya: Buku 1A untuk kelas 7, Buku 2A untuk kelas 8, dan Buku 3A untuk kelas 9.

## Penyimpanan sesi dan tampilan kuis

- Sesi kuis, urutan soal yang diacak, pilihan jawaban, status jawaban sudah diperiksa, posisi soal aktif, dan hasil disimpan pada `localStorage` browser.
- Jika halaman di-refresh saat kuis belum selesai, aplikasi kembali ke beranda dan menawarkan pilihan **Lanjutkan sesi** atau **Mulai sesi baru**.
- **Lanjutkan sesi** mempertahankan urutan soal, jawaban, dan posisi terakhir. **Mulai sesi baru** mengacak urutan soal dan meminta konfirmasi sebelum mengganti progres yang masih tersimpan.
- Sesi disimpan secara lokal pada browser/perangkat yang sama. Data tidak otomatis tersinkron antarperangkat atau antarbrowser; menghapus data situs/browser dapat menghapus sesi.
- Saat mode kuis aktif, halaman dirancang agar soal dan pilihan pas dalam tinggi layar tanpa menggulir seluruh halaman. Ukuran font pilihan jawaban juga diperbesar dan tata letak menyesuaikan layar kecil.

## Fitur

- Urutan 100 soal diacak setiap kali sesi baru dimulai.
- Komposisi kelas: 40 soal kelas 7, 40 soal kelas 8, dan 20 soal kelas 9.
- Opsi jawaban setiap soal juga diacak, tanpa mengubah kunci jawaban.
- Setiap soal menampilkan label kelas, bab, dan kelompok buku.
- Terdapat empat pilihan jawaban, pemeriksaan jawaban, dan penjelasan.
- Progres sesi ditampilkan pada bilah kemajuan.
- Shortcut keyboard saat kuis aktif: **A/B/C/D** untuk memilih jawaban, **Enter** untuk memeriksa jawaban, dan **Backspace** untuk kembali ke soal sebelumnya.
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
