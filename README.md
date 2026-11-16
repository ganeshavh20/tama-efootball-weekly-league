# Turnamen eFootball (Home & Away)

Website turnamen liga kandang-tandang. Satu file HTML, tanpa server dan tanpa instalasi.

## Cara upload ke GitHub (lewat browser)
1. Masuk ke github.com, klik **New repository**. Beri nama, misalnya `turnamen-efootball`, pilih **Public**, lalu **Create repository**.
2. Klik **uploading an existing file**, lalu seret semua isi folder ini (`index.html`, `README.md`, dan folder `logos`) ke halaman tersebut.
3. Klik **Commit changes**.
4. Buka **Settings > Pages**. Pada *Build and deployment*, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu 1-2 menit. Alamat website muncul di halaman yang sama: `https://USERNAME.github.io/turnamen-efootball/`

## Cara upload lewat Git (terminal)
```
git init
git add .
git commit -m "Turnamen eFootball"
git branch -M main
git remote add origin https://github.com/USERNAME/turnamen-efootball.git
git push -u origin main
```
Lalu aktifkan Pages seperti langkah 4 di atas.

## Memasang logo club asli
Di GitHub Pages gambar dari folder yang sama bisa dimuat. Simpan logo (PNG) di folder `logos/` dengan nama seperti daftar berikut. Website akan memakainya otomatis; jika file tidak ada, dipakai lambang bawaan.

- `logos/fc-barcelona.png`  (FC Barcelona)
- `logos/real-madrid.png`  (Real Madrid)
- `logos/atletico-madrid.png`  (Atlético Madrid)
- `logos/sevilla.png`  (Sevilla)
- `logos/manchester-city.png`  (Manchester City)
- `logos/manchester-united.png`  (Manchester United)
- `logos/liverpool.png`  (Liverpool)
- `logos/arsenal.png`  (Arsenal)
- `logos/chelsea.png`  (Chelsea)
- `logos/tottenham-hotspur.png`  (Tottenham Hotspur)
- `logos/newcastle-united.png`  (Newcastle United)
- `logos/aston-villa.png`  (Aston Villa)
- `logos/bayern-munchen.png`  (Bayern München)
- `logos/borussia-dortmund.png`  (Borussia Dortmund)
- `logos/bayer-leverkusen.png`  (Bayer Leverkusen)
- `logos/rb-leipzig.png`  (RB Leipzig)
- `logos/juventus.png`  (Juventus)
- `logos/ac-milan.png`  (AC Milan)
- `logos/inter-milan.png`  (Inter Milan)
- `logos/napoli.png`  (Napoli)
- `logos/as-roma.png`  (AS Roma)
- `logos/lazio.png`  (Lazio)
- `logos/paris-saint-germain.png`  (Paris Saint-Germain)
- `logos/marseille.png`  (Marseille)
- `logos/ajax.png`  (Ajax)
- `logos/feyenoord.png`  (Feyenoord)
- `logos/benfica.png`  (Benfica)
- `logos/fc-porto.png`  (FC Porto)
- `logos/sporting-cp.png`  (Sporting CP)
- `logos/celtic.png`  (Celtic)

Untuk club lain, nama file adalah nama club huruf kecil, spasi diganti tanda hubung, tanpa aksen (contoh: `Real Sociedad` menjadi `logos/real-sociedad.png`).
Atau isi `LOGO_DB` di bagian atas script di `index.html` dengan alamat gambar dari database Anda.
Pastikan Anda memiliki hak pakai untuk logo yang diunggah.

## Catatan
- Data turnamen (jadwal, skor, riwayat) tersimpan di browser masing-masing pengguna, bukan di GitHub.
- Untuk memperbarui website, edit atau unggah ulang `index.html` di repositori.
