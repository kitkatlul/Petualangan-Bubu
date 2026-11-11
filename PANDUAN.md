# 🐻 Panduan Petualangan Bubu (untuk pemula)

Isi folder ini = 1 game lengkap. Kamu tidak perlu install apa pun.

| File | Fungsinya |
|---|---|
| `index.html` | Halaman utama |
| `style.css` | Warna & tampilan |
| `game.js` | Semua permainan & suara |
| `sounds/` | (Opsional) tempat suara hewan asli |

## Langkah 0 — Coba dulu di komputer
1. Ekstrak ZIP `petualangan-bubu.zip`.
2. Klik 2x `index.html` → terbuka di browser. **Pakai Google Chrome** agar suara Indonesia berjalan.
3. Tekan **▶ Mulai** (tombol ini wajib, karena browser baru mau bersuara setelah disentuh).

## Langkah 1 — Upload ke GitHub
1. Buat akun di **github.com** (gratis) lalu login.
2. Klik tanda **+** di kanan atas → **New repository**.
3. Isi nama: `petualangan-bubu` → pilih **Public** → klik **Create repository**.
4. Klik tulisan **uploading an existing file**.
5. Buka folder hasil ekstrak, **pilih semua isinya** (`index.html`, `style.css`, `game.js`, `sounds`, `PANDUAN.md`), lalu **drag** ke halaman GitHub.
   - Seret *isi* folder, bukan folder luarnya, supaya `index.html` berada paling depan.
6. Tunggu selesai → klik tombol hijau **Commit changes**.

## Langkah 2 — Deploy di Vercel
1. Buka **vercel.com** → **Sign Up** → pilih **Continue with GitHub**.
2. Klik **Add New… → Project**.
3. Cari repo `petualangan-bubu` → klik **Import**.
4. Jangan ubah pengaturan apa pun (Framework: *Other*). Klik **Deploy**.
5. Tunggu ±30 detik. Muncul 🎉 dan alamat seperti `petualangan-bubu.vercel.app`. Buka di HP/tablet anak!

## Langkah 3 — Mengubah isi game (opsional)
- Setiap mengubah file di GitHub (ikon ✏️ → **Commit changes**), Vercel otomatis memperbarui dalam semenit.
- Ubah warna: buka `style.css`, cari kode warna seperti `#ff8fab`.
- Ubah kalimat Bubu: buka `game.js`, cari kalimat yang ingin diganti, edit teks di dalam tanda petik.

## Suara hewan asli (opsional)
Secara bawaan Bubu menirukan suara hewan dengan suaranya ("Meong, meong"). Untuk suara asli, taruh file MP3 di folder `sounds/` dengan nama persis:
`kucing.mp3, anjing.mp3, sapi.mp3, ayam.mp3, kambing.mp3, bebek.mp3, singa.mp3, kuda.mp3`
Game otomatis memakainya. Cari yang gratis di freesound.org atau pixabay.com/sound-effects.

## Kalau ada masalah
- **Tidak ada suara / suaranya bukan bahasa Indonesia**: suara Bubu memakai suara bawaan perangkat. Android + Chrome biasanya sudah ada. Di iPhone: Pengaturan → Aksesibilitas → Konten Lisan → Suara → tambahkan *Bahasa Indonesia*. Pastikan HP tidak mode senyap.
- **Halaman kosong setelah deploy**: pastikan `index.html` ada di paling depan repo (bukan di dalam folder lagi).
- **Bintang hilang**: bintang tersimpan di browser perangkat masing-masing.
