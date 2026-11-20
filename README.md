# Brawijaya Gastro, Liver & Pancreas Center (GLPC)

Landing page Center of Excellence Gastro, Liver & Pancreas Brawijaya Hospital.
Dibangun dari template Brawijaya Comprehensive Pediatric Center (`bcpc`), dengan CSS, komponen, dan script yang sama.

- URL GitHub Pages: https://yanuarnorman.github.io/glpc/
- File utama: `index.html` (single file, inline `<style>` dan `<script>`)
- Aset lokal: `logo.svg`, `favicon.svg`, `award.png`, `ytc.png`, `heroimage.jpeg`
- Foto dokter: CDN Brawijaya (`dte49v1irn0nj.cloudfront.net/assets/<uuid>`), sama seperti BCPC

## Placeholder yang harus diganti sebelum tayang
1. `heroimage.jpeg`: masih gambar placeholder. Ganti dengan foto Center (1024 x 687 px, nama file tetap sama). File ini juga dipakai sebagai og:image.
2. Video grid: 3 kartu bertanda "PLACEHOLDER VIDEO". Ganti `<div ...>PLACEHOLDER VIDEO...</div>` di dalam `.video-frame` dengan `<iframe src="https://www.youtube.com/embed/ID_VIDEO" title="..." allowfullscreen></iframe>`.

## Rotator linktochat yang perlu dibuat
Semua CTA memakai format `https://linkto.chat/api/pr/sem-glpc-<slug>`. Buat rotator berikut di app.linktochat.id:
- sem-glpc-anak
- sem-glpc-anorektal
- sem-glpc-bedahdigestif
- sem-glpc-dralexander
- sem-glpc-drannisa
- sem-glpc-drarnetta
- sem-glpc-drbarry
- sem-glpc-drdiah
- sem-glpc-drhaidar
- sem-glpc-drindah
- sem-glpc-drkaka
- sem-glpc-drnyoto
- sem-glpc-drrebekka
- sem-glpc-drruben
- sem-glpc-drsyahfreadi
- sem-glpc-empedu
- sem-glpc-floatingwa
- sem-glpc-hati
- sem-glpc-hernia
- sem-glpc-hero
- sem-glpc-herocta
- sem-glpc-kemoterapi
- sem-glpc-lambung
- sem-glpc-tumor
- sem-glpc-usus

## Sumber data dokter
Direktori resmi brawijayahospital.com/find-doctor (diakses 20 Nov 2026):
Kaka Renaldi (6051), Alexander Saudale (660209), Haidar Abdullah (6309), Ruben Selamat (8275),
Arnetta Lalisang (660029), Diah Asih Lestari (5997), Indah Jamtani (4275), Syahfreadi (6099),
Nyoto Widyo Astoro (4384), Rebekka Napitupulu (1290), Annisa Rahmania Yulman (7318), Barry Army Bakry.

Alamat lokasi mengikuti situs resmi brawijayahospital.com.
