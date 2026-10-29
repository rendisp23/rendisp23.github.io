# Eres — Portofolio Rendi Saputra

Versi portofolio IT Support, Helpdesk, dan Infrastructure. Situs statis tanpa database dan tanpa proses build.

## Berkas yang diedit

| Berkas | Isi |
|---|---|
| index.html | Profil, keahlian, pengalaman, kartu proyek, kontak |
| app.js | Tutorial, cerita lengkap proyek, filter dan penghitung status |
| style.css | Tampilan dasar dan diagram |
| readability.css | Ukuran teks, tampilan responsif, prosesor RS dan efek cahaya |

Baca [PANDUAN-UPDATE.md](PANDUAN-UPDATE.md) untuk langkah perubahan langsung melalui GitHub.

## Membuka web

Buka index.html di browser untuk melihat situs lokal. Tidak perlu npm install. Google Fonts membutuhkan internet; font cadangan tetap tersedia.

## Hosting

Untuk CWP/Jagoweb, unggah index.html, app.js, style.css, dan readability.css ke folder publik domain. Untuk GitHub Pages, gunakan folder root repositori ini setelah pembaruan digabungkan ke branch yang digunakan Pages. File .nojekyll menandai situs sebagai berkas statis.

Alamat Sites yang sudah dibuat tidak otomatis mengikuti perubahan GitHub. Unggahan GitHub ini menyimpan sumber web; aktivasi hosting atau sinkronisasi perlu dikonfigurasi tersendiri.

## Data proyek

Status live = Go Live, ongoing = Progress, plan = Rancangan. Jumlah status dihitung otomatis dari kartu proyek. Angka kebutuhan perangkat dan kabel diberi konteks sesuai dokumen pendukung. CV, dokumen internal asli, kredensial, dan konfigurasi layanan Sites tidak disertakan.

Folder lama css/, js/, img/, scss/, vendor/ dan berkas build lama merupakan bagian versi terdahulu dan tidak diperlukan oleh index.html Eres yang baru. Berkas lama tetap dipertahankan untuk referensi.
