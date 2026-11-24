# UnfollowInstagram v2

<p align="center">
  <strong>Instagram Follower Analyzer</strong><br>
  Analisis followers dan following Instagram dengan tampilan modern langsung dari browser.
</p>

<p align="center">
  <a href="https://github.com/Muhzarx/UnfollowInstagram-v2">Repository</a>
  ·
  <a href="https://muhzarx.github.io/UnfollowInstagram-v2/">Live Demo (aktif setelah GitHub Pages diterbitkan)</a>
</p>

---

## Tentang

UnfollowInstagram v2 membantu membaca data ekspor Instagram untuk melihat hubungan followers dan following. Aplikasi berjalan di browser dan **tidak meminta username, password, atau akses login Instagram**.

## Fitur

- **Not Following Back** — akun yang kamu ikuti, tetapi tidak mengikuti balik.
- **Mutual Followers** — akun yang saling mengikuti.
- **All Followers** — daftar seluruh followers.
- **All Following** — daftar seluruh akun yang kamu ikuti.
- **Unfollowed You** — membandingkan dua ekspor untuk menemukan akun yang sudah tidak mengikuti kamu.
- **New Followers** — membandingkan dua ekspor untuk melihat followers baru.
- Pencarian username dan ringkasan statistik.
- Salin username, ekspor hasil ke CSV, dan buka profil Instagram.
- Mendukung unggahan ZIP ekspor Instagram maupun file JSON.

## Cara menggunakan

1. Buka aplikasi melalui halaman web setelah GitHub Pages diaktifkan.
2. Unduh data Instagram melalui **Accounts Center → Your information and permissions → Download your information**.
3. Pilih format **JSON** saat meminta unduhan data.
4. Unggah ZIP ekspor Instagram terbaru ke aplikasi.
5. Untuk memeriksa **Unfollowed You** atau **New Followers**, unggah juga ekspor lama sebagai pembanding.
6. Tekan **Analyze my account** dan pilih kategori hasil yang ingin dilihat.

## Privasi dan keamanan

- Aplikasi tidak meminta kata sandi Instagram.
- File ekspor dibaca dan diproses secara lokal di browser.
- Tidak ada proses login Instagram atau pengiriman data ekspor ke backend aplikasi.
- Tombol profil hanya membuka halaman profil Instagram; aplikasi tidak melakukan unfollow otomatis.

> Gunakan file ekspor resmi milik akunmu sendiri. Untuk mengetahui siapa yang berhenti mengikuti, kamu perlu menyimpan ekspor followers dari waktu sebelumnya dan membandingkannya dengan ekspor terbaru.

## Teknologi

- HTML, CSS, dan JavaScript
- JSZip untuk membaca arsip ZIP di browser
- GitHub Pages untuk hosting statis

## Menjalankan secara lokal

Unduh atau clone repository, lalu buka `index.html` menggunakan browser modern. Koneksi internet diperlukan untuk memuat library JSZip dan font eksternal yang digunakan antarmuka.

```bash
git clone https://github.com/Muhzarx/UnfollowInstagram-v2.git
cd UnfollowInstagram-v2
```

Kemudian buka `index.html`.

## Publikasi dengan GitHub Pages

1. Pastikan `index.html` berada di root repository.
2. Buka **Settings → Pages**.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/(root)`, lalu simpan.
5. Setelah proses publikasi selesai, aplikasi dapat diakses melalui:

   **https://muhzarx.github.io/UnfollowInstagram-v2/**

---

<p align="center">Dibuat oleh <a href="https://github.com/Muhzarx">Muhzarx</a></p>
