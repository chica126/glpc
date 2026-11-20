# Brawijaya Gastro, Liver & Pancreas Center (GLPC)

Landing page Center of Excellence Gastro, Liver & Pancreas Brawijaya Hospital.
Dibangun dari template Brawijaya Comprehensive Pediatric Center (`bcpc`), dengan CSS, komponen, dan script yang sama.

- URL GitHub Pages: https://yanuarnorman.github.io/glpc/
- File utama: `index.html` (single file, inline `<style>` dan `<script>`)
- Aset lokal: `logo.svg`, `favicon.svg`, `award.png`, `ytc.png`, `heroimage.jpeg`
- Foto dokter: CDN Brawijaya (`dte49v1irn0nj.cloudfront.net/assets/<uuid>`), sama seperti BCPC

## Placeholder yang harus diganti sebelum tayang
1. `heroimage.jpeg`: masih gambar placeholder. Ganti dengan foto Center (1024 x 687 px, nama file tetap sama). File ini juga dipakai sebagai og:image.
2. Foto dr. Mohammad Julwan Pribadi: belum ada di CDN Brawijaya, sementara tampil inisial "MJ". Ganti `<div class="doc-ph noimg" ...>MJ</div>` dengan elemen foto seperti dokter lain setelah foto diunggah ke Directus.

## Video
- Edukasi (YouTube): KFOWQ4y9eww, -AmVj5zbUfQ, qe6dR71_OYs; vertikal: Shorts ROrqqSf1XPQ, Instagram Reels DfPDBbqvGoU, DPsfYXUCU9H
- Testimoni: YouTube zA2goL3_gTg, UJHoM2KqT-8; Instagram Reels DVU8lttCXYS
- Reels memakai embed resmi Instagram (`embed.js`), tingginya menyesuaikan otomatis.

## Rotator linktochat yang perlu dibuat
Semua CTA memakai format `https://linkto.chat/api/pr/sem-glpc-<slug>`. Buat rotator berikut di app.linktochat.id (33 rotator):
- sem-glpc-anak
- sem-glpc-anorektal
- sem-glpc-bedahanak
- sem-glpc-bedahdigestif
- sem-glpc-dralexander
- sem-glpc-dralifi
- sem-glpc-drannisa
- sem-glpc-drarnetta
- sem-glpc-drbarry
- sem-glpc-drdiah
- sem-glpc-drfaisal
- sem-glpc-drhaidar
- sem-glpc-drindah
- sem-glpc-drjulwan
- sem-glpc-drkaka
- sem-glpc-drnyoto
- sem-glpc-drrebekka
- sem-glpc-drruben
- sem-glpc-drsyahfreadi
- sem-glpc-empedu
- sem-glpc-endoskopi
- sem-glpc-ercp
- sem-glpc-floatingwa
- sem-glpc-hati
- sem-glpc-hernia
- sem-glpc-hero
- sem-glpc-herocta
- sem-glpc-kemoterapi
- sem-glpc-lambung
- sem-glpc-skrining
- sem-glpc-tindakanendoskopi
- sem-glpc-tumor
- sem-glpc-usus

## Sumber data dokter
Direktori resmi brawijayahospital.com/find-doctor (diakses 20 Nov 2026):
Mohammad Julwan Pribadi (660063, foto & lokasi belum ada di direktori), Kaka Renaldi (6051), Alexander Saudale (660209), Haidar Abdullah (6309), Ruben Selamat (8275),
Muhammad Faisal Prananda (8297),
Arnetta Lalisang (660029), Diah Asih Lestari (5997), Indah Jamtani (4275), Syahfreadi (6099),
Nyoto Widyo Astoro (4384), Rebekka Napitupulu (1290), Annisa Rahmania Yulman (7318), Barry Army Bakry (5395), Alifi Maulidyan (660134).

Alamat lokasi mengikuti situs resmi brawijayahospital.com.
