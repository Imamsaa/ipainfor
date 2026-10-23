# Jelajah IPA — Media Belajar Interaktif SMP

Web belajar IPA berbasis HTML, CSS, dan JavaScript murni. Tidak membutuhkan framework, proses build, database, atau koneksi internet untuk menjalankan fitur inti.

## Menjalankan secara lokal
1. Ekstrak folder/ZIP ini.
2. Buka `index.html` dengan Chrome, Edge, atau Firefox.
3. Progres XP dan bab tersimpan di `localStorage` browser yang digunakan.

Jika browser membatasi fitur tertentu saat membuka file langsung, jalankan server lokal sederhana dari folder ini:

**Python:**
```bash
python -m http.server 8000
```
Lalu buka `http://localhost:8000`.

## Publikasi di GitHub Pages
1. Buat repository baru di GitHub.
2. Unggah `index.html` dan `README.md` ke root repository (atau unggah isi folder ini).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu proses deployment selesai; URL Pages akan ditampilkan pada bagian Pages.

Alternatif: jika repository sudah dibuat, unggah kedua file ke root melalui **Add file → Upload files**, lalu commit.

## Catatan
- Tidak ada dependensi eksternal yang diperlukan untuk fitur inti.
- Progres disimpan secara lokal per browser/perangkat, tidak tersinkron antarperangkat atau antarsiswa.
- Isi materi mengikuti daftar isi buku IPA 1a, 2a, dan 3a yang diberikan; aktivitas merupakan simulasi belajar sederhana, bukan pengganti praktikum nyata.
