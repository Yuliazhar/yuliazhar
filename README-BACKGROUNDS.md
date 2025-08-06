# Cara Mengganti Background Image Setiap Section

## File yang Perlu Diubah

Untuk mengganti background image setiap section, Anda perlu mengubah file `style.css` pada bagian CSS yang sudah ditambahkan.

## Daftar Background Image yang Dapat Diganti

### 1. Hero Section (Bagian Utama)
- **File CSS**: `style.css`
- **Class**: `.section-bg-hero`
- **Ganti**: `url('img/hero-bg.jpg')` dengan path gambar Anda
- **Contoh**: `url('img/background-hero-saya.jpg')`

### 2. Couple Section (Bagian Pasangan)
- **File CSS**: `style.css`
- **Class**: `.section-bg-couple`
- **Ganti**: `url('img/couple-bg.jpg')` dengan path gambar Anda
- **Contoh**: `url('img/background-couple-saya.jpg')`

### 3. Info Section (Bagian Informasi)
- **File CSS**: `style.css`
- **Class**: `.section-bg-info`
- **Ganti**: `url('img/info-bg.jpg')` dengan path gambar Anda
- **Contoh**: `url('img/background-info-saya.jpg')`

### 4. Gallery Section (Bagian Galeri)
- **File CSS**: `style.css`
- **Class**: `.section-bg-gallery`
- **Ganti**: `url('img/gallery-bg.jpg')` dengan path gambar Anda
- **Contoh**: `url('img/background-gallery-saya.jpg')`

### 5. Wishes Section (Bagian Ucapan)
- **File CSS**: `style.css`
- **Class**: `.section-bg-wishes`
- **Ganti**: `url('img/wishes-bg.jpg')` dengan path gambar Anda
- **Contoh**: `url('img/background-wishes-saya.jpg')`

### 6. Gift Section (Bagian Hadiah)
- **File CSS**: `style.css`
- **Class**: `.section-bg-gift`
- **Ganti**: `url('img/gift-bg.jpg')` dengan path gambar Anda
- **Contoh**: `url('img/background-gift-saya.jpg')`

## Cara Mengganti Background Image

1. **Siapkan gambar** yang ingin digunakan sebagai background
2. **Simpan gambar** di folder `img/` dengan nama yang sesuai
3. **Buka file** `style.css`
4. **Cari class** yang ingin diubah (misalnya `.section-bg-hero`)
5. **Ganti path gambar** pada bagian `url('img/nama-gambar.jpg')`
6. **Simpan file** dan refresh browser

## Contoh Penggunaan

```css
/* Sebelum */
.section-bg-hero {
  background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('img/hero-bg.jpg');
  /* ... */
}

/* Sesudah */
.section-bg-hero {
  background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('img/wedding-background.jpg');
  /* ... */
}
```

## Tips untuk Background Image

1. **Ukuran gambar**: Gunakan gambar dengan resolusi tinggi (minimal 1920x1080px)
2. **Format file**: Gunakan format JPG atau PNG
3. **Ukuran file**: Usahakan file tidak terlalu besar (max 2MB) untuk loading yang cepat
4. **Overlay**: Setiap background sudah diberi overlay untuk memastikan teks tetap terbaca
5. **Responsive**: Background akan otomatis menyesuaikan dengan ukuran layar

## Struktur Folder yang Disarankan

```
your-wedding-website/
├── index.html
├── style.css
├── img/
│   ├── hero-bg.jpg
│   ├── couple-bg.jpg
│   ├── info-bg.jpg
│   ├── gallery-bg.jpg
│   ├── wishes-bg.jpg
│   └── gift-bg.jpg
└── README-BACKGROUNDS.md
```

## Catatan Penting

- Pastikan gambar yang digunakan memiliki lisensi yang sesuai
- Test website di berbagai ukuran layar untuk memastikan background terlihat baik
- Jika background terlalu gelap/terang, Anda bisa mengubah opacity overlay di CSS 