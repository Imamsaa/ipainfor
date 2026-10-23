# Jelajah IPA — Adventure Mode SMP

Media belajar IPA berbasis HTML, CSS, dan JavaScript murni. Setiap bab dikemas sebagai petualangan game dengan cerita misi, tiga level tantangan, umpan balik jawaban, XP, dan aktivitas mini interaktif yang disesuaikan dengan materinya.

## Mode petualangan

- **Buku 1a:** Detektif Sains, Alkemis Partikel, Roket Newton.
- **Buku 2a:** Arsitek Sel, Tim Penyelamat Tubuh.
- **Buku 3a:** Agen Indra, Kapten Homeostasis, Penjaga Siklus Hidup, Detektif Genetika, Insinyur Tekanan.

Setiap bab memiliki tiga level: mengamati petunjuk, menerapkan konsep, dan menuntaskan tantangan. Siswa mendapatkan penjelasan setelah menjawab, serta bisa mencoba mini-simulasi seperti mengatur energi partikel, menggerakkan kendaraan, memeriksa organel, menjaga suhu, dan menguji tekanan.

## Menjalankan di komputer

1. Unduh repository melalui **Code → Download ZIP**, lalu ekstrak.
2. Buka `index.html` dengan Chrome, Edge, atau Firefox.
3. Jika browser membatasi fitur saat membuka file langsung, jalankan server lokal dari folder ini:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000`.

Tidak perlu Node.js, framework, paket tambahan, atau koneksi internet untuk fitur inti.

## Publikasi di GitHub Pages

1. Pastikan `index.html` berada di root repository.
2. Buka **Settings → Pages**.
3. Di **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
5. Setelah deployment selesai, gunakan URL yang ditampilkan pada bagian Pages.

## Penyimpanan dan catatan pembelajaran

- XP, aktivitas yang sudah diberi XP, level petualangan, dan bab yang tuntas disimpan dalam `localStorage` pada browser/perangkat yang sama.
- Data tidak tersinkron otomatis antarperangkat atau antarsiswa; ini bukan sistem akun atau dashboard guru.
- Materi merujuk pada daftar isi diktat IPA 1a, 2a, dan 3a yang diberikan. Game dan simulasi merupakan media latihan, bukan pengganti praktikum nyata.
