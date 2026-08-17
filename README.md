# Portfolio AINUN — Deploy ke GitHub Pages

Panduan singkat untuk menghosting project ini di GitHub Pages.

Persyaratan
- Akun GitHub
- Git terpasang di komputer

Langkah cepat (lokal → GitHub)

1. Inisialisasi repo lokal (jika belum):

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
```

2. Buat repo baru di GitHub (mis. `portfolio-ainun`) lalu tambahkan remote dan push:

```bash
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

3. Workflow GitHub Actions (sudah ada di `.github/workflows/deploy.yml`) akan otomatis menjalankan deploy ke GitHub Pages saat kamu push ke `main`.

Verifikasi
- Buka tab Pages pada halaman repo GitHub — alamat situs biasanya `https://USERNAME.github.io/REPO/`.

Catatan responsif & mobile
- Pastikan `index.html` sudah memiliki tag meta viewport (sudah ada).
- Cek tampilan di ponsel, perbaiki CSS responsif bila perlu (saya bisa bantu jika ada yang pecah).

Jika mau, saya bisa:
- Membantu membuat repository di GitHub (kamu perlu memberi akses atau melakukannya sendiri),
- Menambahkan file README lebih lengkap dan metadata SEO,
- Menyiapkan domain kustom.
