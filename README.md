# Moncer Active: Landing Page

Situs statis (HTML, CSS, JS biasa). Tidak perlu build.

## Deploy ke Vercel

**Lewat CLI**
1. `npm i -g vercel`
2. Masuk ke folder ini, jalankan `vercel` lalu `vercel --prod`
3. Saat ditanya Framework Preset pilih **Other**, Build Command dan Output Directory dikosongkan.

**Lewat GitHub**
1. Push folder ini ke repo GitHub.
2. Di vercel.com pilih Add New > Project > import repo.
3. Framework Preset: **Other**, tanpa build command, lalu Deploy.

## Yang bisa diedit
- Nomor WhatsApp: cari `WA_NUMBER` di `index.html` (format 62...).
- Harga mulai dari: cari `PRICE=40000` di `index.html`, dan teks "Rp 40.000" di beberapa tempat.
- Foto: ganti file di `assets/` dengan nama sama.

## Setelah punya domain
Tambahkan di `<head>` agar preview link (WhatsApp/Facebook) menampilkan gambar:
`<meta property="og:image" content="https://DOMAINMU/assets/hero.jpg">`
