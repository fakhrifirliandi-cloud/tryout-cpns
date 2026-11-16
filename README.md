# Portal Simulasi CAT & Latihan Soal SKD CPNS

Website ini siap di-deploy gratis ke **Vercel**, **Cloudflare Pages**, atau **GitHub Pages**.

## Struktur File
- `index.html`: Aplikasi web utama (sudah memuat Paket 1 Try Out SKD Utuh 110 Soal + Paket 1 Latihan TWK, TIU, TKP sehingga langsung jalan cepat tanpa loading).
- `data/daftar-paket.json`: Daftar metadata seluruh paket soal.
- `data/paket-tryout-1.json`: Bank soal utuh 110 soal (30 TWK, 35 TIU, 45 TKP) beserta pembahasan dan skor.
- `data/latihan-twk-1.json`, `data/latihan-tiu-1.json`, `data/latihan-tkp-1.json`: File JSON terpisah per subtes.

## Cara Upload Pertama Kali ke GitHub & Vercel
1. Buat repository baru di GitHub (misal `tryout-cpns`), klik **Add file -> Upload files**.
2. Ekstrak file ZIP ini, lalu seret `index.html` dan folder `data/` ke GitHub, klik **Commit changes**.
3. Buka Vercel.com, login dengan GitHub, klik **Add New Project**, pilih `tryout-cpns`, lalu klik **Deploy**.
