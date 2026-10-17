# Halaman Profil Kota Bandung

Situs satu halaman tentang sejarah, geografis, dan wisata Bandung. Dibuat dengan HTML, CSS, dan JavaScript murni (tanpa framework).

## Struktur

```
index.html
css/        base, themes, layout, components
js/         main.js + modules/
assets/     image/, icons/
docs/       PRD
```

## Menjalankan

Karena memakai ES modules, buka lewat server lokal, bukan dengan klik dua kali:

```
npx serve .
# atau
python3 -m http.server 8000
```

## Rencana

Lihat PRD (bagian 10) untuk fase pengerjaan. Status saat ini: **Fase 1 selesai** (HTML, CSS dasar, hero, tema light/dark mengikuti sistem). Berikutnya: Fase 2 (JavaScript inti).

## Aset gambar

Letakkan di `assets/image/`: `history.jpg`, `geografis.jpg`, `farm-house.jpg`, `bosscha.jpg`, `bandung-badge.png`. Tambahkan juga foto hero.
