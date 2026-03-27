# Portfolio Ardi Kamal Karima

Web portofolio statis siap deploy ke **Vercel**.

## Struktur Folder

```
portfolio-ardi/
├── public/
│   ├── index.html          ← halaman utama
│   └── images/
│       ├── profil.jpg
│       ├── sd.jpg
│       ├── smp.jpg
│       ├── smk.jpg
│       └── kuliah.jpg
└── vercel.json             ← konfigurasi Vercel
```

## Deploy ke Vercel

### Cara 1 — Via Vercel CLI
```bash
npm i -g vercel
cd portfolio-ardi
vercel
```

### Cara 2 — Via GitHub (Recommended)
1. Upload folder ini ke GitHub repo baru
2. Buka [vercel.com](https://vercel.com) → **Add New Project**
3. Import repo GitHub kamu
4. Vercel otomatis deteksi `vercel.json` → klik **Deploy**
5. Selesai! Kamu dapat URL live gratis

### Cara 3 — Drag & Drop
1. Buka [vercel.com/new](https://vercel.com/new)
2. Drag & drop seluruh folder `portfolio-ardi` ini
3. Deploy otomatis

## Ganti Email
Di `public/index.html`, cari `ardikamalkarima@gmail.com` dan ganti dengan email kamu yang sebenarnya.
