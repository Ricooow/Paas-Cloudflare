# team-git-lab

feature about

## Struktur proyek

- `public/` berisi website statis yang akan disajikan oleh Cloudflare.
- `public/img/` berisi aset gambar, termasuk foto profil `me.jpg`.
- `wrangler.jsonc` mengatur nama proyek dan direktori aset untuk Cloudflare.

## Menjalankan secara lokal

Jalankan server pengembangan Cloudflare dari folder proyek:

```sh
npx wrangler dev
```

## Deploy ke Cloudflare

Pastikan sudah login ke Cloudflare dengan Wrangler, lalu jalankan:

```sh
npx wrangler deploy
```
