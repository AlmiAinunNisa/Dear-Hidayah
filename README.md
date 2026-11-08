# Dear Hidayah — From Ainun, with love ♡
Website statis HTML, CSS, JavaScript. Bisa dibuka langsung di browser dan dipublikasikan melalui GitHub Pages. Tidak perlu PHP/Herd.

## Cara melihat
Klik dua kali `index.html` atau gunakan Live Server di VS Code.

## Cara memasang foto
1. Buka folder `galeri` (sudah tersedia).
2. Salin foto kalian ke folder itu, lalu **ubah nama foto persis** sesuai daftar di bawah. Gunakan format JPG. Jika foto berupa PNG/JPEG/HEIC, konversi ke JPG atau sesuaikan ekstensi di `index.html`.
3. Refresh halaman browser (Ctrl+R). Placeholder akan otomatis tergantikan.

| Nama foto di galeri | Lokasi website |
| --- | --- |
| `cover.jpg` | Foto utama di pembukaan |
| `matrikulasi.jpg` | Bab awal pertemuan |
| `gumpala.jpg` | Bab GUMPALA |
| `tektok.jpg` | Bab perjalanan/tektok |
| `bem.jpg` | Bab BEM |
| `kenangan-1.jpg` sampai `kenangan-6.jpg` | Galeri 6 foto |

Foto akan terpotong menyesuaikan bingkai (`object-fit: cover`), tetapi foto asli tidak berubah. Untuk mengubah posisi foto tertentu, dapat ditambahkan `object-position` pada CSS.

## GitHub Pages
1. Buat repository publik `dear-hidayah`.
2. Upload `index.html`, `style.css`, `script.js`, folder `galeri` berisi foto-foto, dan `README.md` langsung ke root repository. Jangan upload ZIP.
3. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
4. Tunggu publikasi; alamat biasanya `https://USERNAME.github.io/dear-hidayah/`.

**Privasi:** Website GitHub Pages publik. Minta persetujuan Hidayah untuk foto atau cerita yang sifatnya pribadi sebelum membagikan link. Jangan menyimpan informasi sensitif di repository.

## Personalisasi cerita
Teks ditulis dari pengalaman yang diceritakan Ainun: awal matrikulasi, GUMPALA, tektok, masa sulit dan saling memahami, serta peran di BEM. Ubah detail kalimat mana pun sesuai ingatan asli sebelum dibagikan.
