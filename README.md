# NIGHTWATCH 3D — The Last Shift

Game survival horror 3D berbasis HTML + Three.js. Model lingkungan dan monster dibuat secara procedural dari geometri 3D, sehingga tidak membutuhkan file model tambahan.

## Menjalankan game
- Cara paling stabil: jalankan melalui server lokal (karena menggunakan JavaScript ES Modules).
- Dengan VS Code, pasang ekstensi Live Server, klik kanan `index.html` → **Open with Live Server**.
- Alternatif Python: dari folder game jalankan `python -m http.server 8000`, lalu buka `http://localhost:8000`.
- Koneksi internet diperlukan untuk memuat Three.js dari jsDelivr dan Google Fonts.

## Kontrol
- Mouse: lihat sekitar (klik area game untuk mengaktifkan pointer lock).
- A / D: pintu kiri / kanan.
- Q / E: lampu kiri / kanan.
- Space: buka/tutup monitor kamera.
- M: mute/unmute suara.
- Esc: tutup monitor / lepas pointer lock.

## Gameplay
Bertahan dari 12 AM sampai 6 AM. Pantau 8 kamera, gunakan pintu dan lampu dengan hemat, dan jangan biarkan makhluk mencapai ruang keamanan. Listrik terbatas dan pemakaian perangkat mempercepat pengurasan.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub.
2. Upload `index.html`, `README.md`, `LICENSE`, dan `.nojekyll` ke root repository.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu Save.
5. Tunggu GitHub Pages selesai menerbitkan situs. Buka URL yang ditampilkan pada halaman Pages.

## Kredit & catatan
- Judul: NIGHTWATCH 3D — The Last Shift
- Watermark: **ABELINO PUTRA**
- Game horor original yang terinspirasi dari genre penjagaan malam dan kamera keamanan. Bukan produk resmi Five Nights at Freddy's dan tidak menggunakan karakter/aset resminya.
- Teknologi: HTML5, CSS, JavaScript, Three.js.
