# Berkarya untuk Indonesia

Landing page statis untuk test Web Developer Internship dengan tema **"Berkarya untuk Indonesia"**. Proyek ini dibuat untuk Mahreen Indonesia sebagai ajakan bagi generasi muda Indonesia agar berani menciptakan karya bermakna melalui kreativitas, teknologi, dan kontribusi nyata.

Live URL target: `https://mrivaldodestadhiohamzah.github.io/berkarya-untuk-indonesia/`

## Fitur

- Hero section dengan visual abstrak Indonesia dan teknologi berbasis CSS.
- Logo Berkarya ID pada navbar dan animasi maskot pada Hero Section.
- About Program section dengan tiga kartu fitur: Kreativitas, Teknologi, dan Kontribusi.
- Call To Action section yang jelas, kuat, dan tetap statis.
- Navbar responsif dengan anchor link ke setiap section.
- Tema merah-putih elegan dengan pattern geometris, gradient, dan dekorasi CSS-only.
- Layout responsif untuk desktop, tablet, dan mobile.
- Struktur HTML semantik, meta description, dan kontras teks yang nyaman dibaca.
- Siap di-host sebagai website statis melalui GitHub Pages.

## Teknologi yang Digunakan

- HTML5
- CSS3
- Tanpa JavaScript
- Tanpa framework
- Asset lokal dari folder `assets`

## Struktur Folder

```text
berkarya-untuk-indonesia/
+-- assets/
+   +-- LogoB.png
+   `-- MaskotB.webm
+-- index.html
+-- style.css
`-- README.md
```

## Cara Menjalankan Secara Lokal

1. Clone atau unduh project ini.
2. Masuk ke folder project.
3. Buka `index.html` langsung di browser.

Alternatif menggunakan local server sederhana:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000`.

## Cara Deploy ke GitHub Pages

1. Buat repository GitHub bernama `berkarya-untuk-indonesia`.
2. Push file project ke branch `main`.
3. Buka repository di GitHub.
4. Masuk ke `Settings` > `Pages`.
5. Pada bagian `Build and deployment`, pilih:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Simpan pengaturan.
7. Website akan tersedia di:

```text
https://mrivaldodestadhiohamzah.github.io/berkarya-untuk-indonesia/
```
