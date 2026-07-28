# Strategic Communication Dashboard

Prototype frontend untuk monitoring berita, rekomendasi komunikasi harian, dan isu krisis daerah. Aplikasi ini berjalan sepenuhnya di browser: tidak memiliki login, backend, atau database eksternal.

## Fitur

- Total berita, OPD terdampak, isu prioritas, dan indikator berita pimpinan.
- Filter periode monitoring.
- Tabel berita dengan pencarian, sorting, dan pagination menggunakan TanStack Table.
- Rekomendasi komunikasi harian untuk Pimpinan Daerah dan OPD teknis.
- Daftar isu krisis dan panel detail isu.
- Data demo tersimpan di `localStorage` browser; tombol **Reset data demo** mengembalikan data awal.

## Cara menjalankan

1. Instal Node.js versi LTS (18 atau lebih baru) dari https://nodejs.org.
2. Buka Terminal atau PowerShell pada folder proyek ini.
3. Jalankan `npm install`.
4. Jalankan `npm run dev`.
5. Buka alamat yang dicetak terminal (biasanya `http://localhost:5173`) di browser.

Untuk membuat versi produksi, jalankan `npm run build`. Hasilnya dibuat di folder `dist`.

## Struktur utama

- `src/main.jsx` — komponen dashboard dan data demo.
- `src/styles.css` — tampilan responsif.
- `package.json` — skrip dan dependensi Node.js.
