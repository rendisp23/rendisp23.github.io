# Panduan update web Eres tanpa ChatGPT

## Mengedit langsung di GitHub

1. Buka repositori dan pilih branch yang sedang Anda kelola.
2. Buka berkas yang ingin diperbarui, lalu tekan ikon pensil (Edit this file).
3. Gunakan pencarian browser untuk menemukan judul proyek, nama perusahaan, atau teks yang ingin diganti.
4. Perbarui teks, kemudian pilih Commit changes. Tulis ringkasan perubahan agar riwayat mudah ditelusuri.
5. Jika perubahan berada di branch terpisah, buka Pull request, periksa Files changed, lalu gabungkan ketika siap.
6. Jika hosting sudah dihubungkan ke GitHub, ikuti proses publikasi hosting tersebut. Jika memakai CWP manual, unduh berkas yang diperbarui dan unggah ke folder publik domain.

## Mengubah profil dan kontak

Edit index.html. Cari Rendi Saputra, nama jabatan, atau nomor WhatsApp. Untuk WhatsApp gunakan nomor internasional tanpa tanda + dan tanpa angka 0 awal: 6285274784570. Ubah semua tautan wa.me terkait jika nomor berganti.

## Mengubah proyek

Informasi ringkas berada di kartu article pada index.html. Setiap kartu memiliki data-status dan tombol data-detail.

- data-status="live": Go Live.
- data-status="ongoing": Progress.
- data-status="plan": Rancangan.

Cerita lengkap berada pada objek details di app.js. Nilai data-detail pada tombol harus cocok dengan kunci di details, misalnya opening, cctv, lan, support, atau knowledge.

Untuk menambah proyek, salin satu kartu article secara lengkap, ubah judul dan isinya, tentukan status, lalu tambahkan cerita dengan kunci baru di details. Gunakan kunci unik. Penghitung filter otomatis mengikuti jumlah kartu; tidak perlu mengedit angkanya manual.

## Mengubah tutorial

Edit daftar tutorials di app.js. Setiap tutorial berisi title, category, time, description, dan body. Pertahankan tanda kutip, koma, dan kurung JavaScript. body berisi HTML untuk artikel. Ubah judul dan isi bersama-sama.

## Mengubah tampilan

Gunakan readability.css untuk warna, ukuran teks, jarak, dan penyesuaian ponsel. style.css adalah gaya dasar. readability.css dimuat terakhir sehingga dapat menimpa gaya dasar.

## Memeriksa sebelum publikasi

- Buka index.html dan baca bagian yang diubah.
- Coba filter Semua, Go Live, Progress, Rancangan.
- Buka detail proyek dan artikel.
- Coba pencarian tutorial dan tautan kontak.
- Periksa pada layar ponsel.
- Jika memiliki Node.js, jalankan: node --check app.js

GitHub menyimpan riwayat perubahan sehingga versi lama dapat ditelusuri. Jangan unggah kata sandi, token, CV pribadi lengkap, atau dokumen internal perusahaan ke repositori publik.

## Hubungan dengan web yang sekarang

Repositori GitHub dan situs eres-rendi-portfolio.sprymule128.chatgpt.site adalah dua tempat terpisah. Commit di GitHub tidak otomatis memperbarui alamat Sites. Untuk pembaruan mandiri penuh, gunakan hosting yang mengambil sumber dari repositori, GitHub Pages yang sudah dikonfigurasi, atau unggah manual ke CWP.
