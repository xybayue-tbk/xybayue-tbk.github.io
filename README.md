# xybayue-tbk.github.io

Website portofolio pribadi untuk memperkenalkan siapa saya dan kegiatan saya di bidang teknologi informasi. Ini adalah hasil belajar membuat website dengan bantuan AI.

**Live demo:** https://xybayue-tbk.github.io/

## Tangkapan layar

Tambahkan tangkapan layar ke folder `assets/images/` lalu tampilkan di sini, contoh:

```md
![Beranda](assets/images/screenshot-beranda.webp)
```

## Fitur

- Empat halaman: `index.html` (Home), `about.html`, `projects.html` (Portfolio), `contact.html`
- HTML5 semantik dan CSS3 murni, tanpa framework
- Responsif untuk desktop, tablet, dan mobile (Media Queries)
- Menu hamburger di layar kecil, tanpa JavaScript
- Gambar dalam format `.webp`, ikon dalam format `.svg`

## Desain

| Peran | Warna |
|---|---|
| Primary | `#1B262C` |
| Secondary | `#0F4C75` |
| Background | `#3282B8` |
| Teks | `#BBE1FA` |

Font: **Lato** (judul) dan **Open Sans** (isi), dimuat dari Google Fonts.

## Struktur folder

```
project-root/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   └── style.css
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

## Menjalankan secara lokal

1. Clone repositori:
   ```bash
   git clone https://github.com/xybayue-tbk/xybayue-tbk.github.io.git
   cd xybayue-tbk.github.io
   ```
2. Buka `index.html` langsung di browser, atau jalankan server lokal:
   ```bash
   python3 -m http.server 8000
   ```
   lalu buka http://localhost:8000.

## Deploy ke GitHub Pages

1. Pastikan repositori bersifat **publik** dan bernama `xybayue-tbk.github.io`.
2. Push semua file ke cabang `main`.
3. Buka **Settings → Pages**, pilih **Deploy from a branch**, cabang `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu beberapa menit, situs akan aktif di https://xybayue-tbk.github.io/.

## Kontak

- Gmail: xybayue@gmail.com
- GitHub: https://github.com/xybayue-tbk
