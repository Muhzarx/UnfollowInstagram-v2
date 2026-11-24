# UnfollowInstagram — v2 UI/UX

Instagram relationship analyzer berbasis browser. Tidak membutuhkan login Instagram, password, API, database, atau backend.

## Fitur
- Upload ZIP ekspor Instagram langsung (tidak perlu ekstrak manual).
- Mendukung file JSON `followers_*.json` dan `following.json`.
- Not Following Back, Mutual Followers, All Followers, All Following.
- Unfollowed You dan New Followers dengan membandingkan dua ekspor followers.
- Pencarian username, copy username, ekspor CSV.
- Klik username atau tombol **View profile** untuk membuka profil Instagram.
- File diproses di browser pengguna.

## Cara menjalankan
1. Buka `index.html` melalui GitHub Pages atau browser modern.
2. Pilih ZIP ekspor Instagram terbaru di kotak pertama.
3. (Opsional) Pilih ZIP ekspor lama di kotak kedua untuk membandingkan unfollower dan followers baru.
4. Klik **Analyze my account**.

## Catatan penting
- Untuk mengetahui siapa yang unfollow, diperlukan dua ekspor followers dari waktu berbeda.
- Satu ekspor terbaru hanya dapat digunakan untuk melihat siapa yang tidak follow back, mutual followers, serta daftar followers/following saat ini.
- ZIP diproses secara lokal di browser. Library JSZip dan font dimuat dari CDN; file pengguna tidak dikirim ke CDN atau server aplikasi.
- Tombol profil hanya membuka halaman profil Instagram. Tools ini tidak melakukan unfollow otomatis.
- Format ekspor Instagram dapat berubah. Jika struktur JSON berbeda, parser mungkin perlu diperbarui.

## Deploy ke GitHub Pages
Commit `index.html` ke branch `main` pada root repository. Di Settings → Pages, pilih Deploy from a branch → `main` → `/(root)`.

Made with care by Muhzarx.
