# Brawijaya Gastro, Liver & Pancreas Center (GLPC)

Landing page Center of Excellence Gastro, Liver & Pancreas Brawijaya Hospital.
Dibangun dari template Brawijaya Comprehensive Pediatric Center (`bcpc`), dengan CSS, komponen, dan script yang sama.

- URL GitHub Pages: https://yanuarnorman.github.io/glpc/
- File utama: `index.html` (single file, inline `<style>` dan `<script>`)
- Aset lokal: `logo.svg`, `favicon.svg`, `award.png` (versi Sep 2026, keterangan diubah jadi putih agar terbaca di hero ungu), `ytc.png`, `heroimage.jpeg`, `teknologi-*.jpg`, `images/partner-*.webp` (logo mitra asuransi, disalin dari repo `pci`)
- Foto dokter: CDN Brawijaya (`dte49v1irn0nj.cloudfront.net/assets/<uuid>`), sama seperti BCPC

## Placeholder yang harus diganti sebelum tayang
1. `heroimage.jpeg`: masih gambar placeholder. Ganti dengan foto Center (1024 x 687 px, nama file tetap sama). File ini juga dipakai sebagai og:image.
2. Gambar seksi "Teknologi Modern Kami": `teknologi-ct-mri.jpg`, `teknologi-endoskopi.jpg`, `teknologi-ercp.jpg`, `teknologi-laparoskopi.jpg` masih placeholder. Ganti dengan foto alat/tindakan (800 x 940 px, nama file tetap sama).

## Video
- Semua iframe YouTube memakai atribut embed resmi (allow + referrerpolicy). Pratinjau dari file lokal (file://) dapat menampilkan "Error 153"; uji di URL GitHub Pages.
- Edukasi (YouTube): KFOWQ4y9eww, -AmVj5zbUfQ, qe6dR71_OYs; vertikal: Shorts ROrqqSf1XPQ, Instagram Reels DfPDBbqvGoU
- Testimoni: YouTube zA2goL3_gTg, UJHoM2KqT-8
- Video endoskopi kapsul (Reels DPsfYXUCU9H, DVU8lttCXYS) tidak dipasang karena endoskopi kapsul di luar scope layanan.
- Reels memakai embed resmi Instagram (`embed.js`), tingginya menyesuaikan otomatis.

## Rotator linktochat yang perlu dibuat
Semua CTA memakai format `https://linkto.chat/api/pr/sem-glpc-<slug>`. Buat rotator berikut di app.linktochat.id (37 rotator):
- sem-glpc-anak
- sem-glpc-anorektal
- sem-glpc-asuransi
- sem-glpc-bedahanak
- sem-glpc-bedahdigestif
- sem-glpc-cakupan
- sem-glpc-carakerja
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
- sem-glpc-lambung
- sem-glpc-lokasi
- sem-glpc-skrining
- sem-glpc-teknologi
- sem-glpc-tentang
- sem-glpc-testimoni
- sem-glpc-tindakanendoskopi
- sem-glpc-usus
- sem-glpc-video

## Sumber data dokter
Direktori resmi brawijayahospital.com/find-doctor (diakses 20 Nov 2026):
Mohammad Julwan Pribadi (660063), Kaka Renaldi (6051), Alexander Saudale (660209), Haidar Abdullah (6309), Ruben Selamat (8275),
Muhammad Faisal Prananda (8297),
Arnetta Lalisang (660029), Diah Asih Lestari (5997), Indah Jamtani (4275), Syahfreadi (6099),
Annisa Rahmania Yulman (7318), Barry Army Bakry (5395), Alifi Maulidyan (660134).

Alamat lokasi mengikuti situs resmi brawijayahospital.com.
