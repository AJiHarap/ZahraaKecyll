# 📸 Cara Ganti Foto Zahraa

Folder `photos/` berisi 5 foto placeholder.
**Ganti dengan foto asli Zahraa caranya mudah:**

## Cara Ganti Foto

1. Buka folder `photos/`
2. Ganti file-file ini dengan foto Zahraa yang asli:
   - `photo1.jpg`
   - `photo2.jpg`
   - `photo3.jpg`
   - `photo4.jpg`
   - `photo5.jpg`

> **Tips:** Pastikan nama file tetap sama persis (`photo1.jpg`, `photo2.jpg`, dst.)
> Format yang didukung: `.jpg`, `.jpeg`, `.png`, `.webp`
> Ukuran foto bebas — sistem otomatis resize jadi bulat

## Cara Tambah Foto Lebih Banyak

Buka `index.html`, cari baris ini:

```js
const PHOTO_SRCS = [
  'photos/photo1.jpg',
  'photos/photo2.jpg',
  'photos/photo3.jpg',
  'photos/photo4.jpg',
  'photos/photo5.jpg',
];
```

Tambahkan foto baru:

```js
const PHOTO_SRCS = [
  'photos/photo1.jpg',
  'photos/photo2.jpg',
  'photos/photo3.jpg',
  'photos/photo4.jpg',
  'photos/photo5.jpg',
  'photos/photo6.jpg',  // ← tambah di sini
];
```

## Cara Share ke iPhone Zahraa

### Opsi 1 — Netlify Drop (Gratis, Mudah)
1. Buka https://app.netlify.com/drop
2. Drag & drop seluruh folder `ZahraaKecyll`
3. Dapat link → kirim ke Zahraa via WhatsApp

### Opsi 2 — GitHub Pages (Gratis)
1. Upload folder ke GitHub repo baru
2. Settings → Pages → Deploy from main branch
3. Link otomatis aktif dalam 1-2 menit

### Opsi 3 — Buka Langsung di HP (Offline)
1. Copy folder ke HP via USB / Google Drive
2. Buka `index.html` pakai browser (Chrome / Safari)
