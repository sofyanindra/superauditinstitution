# Indeks Modul SAP — Penyusunan LK Pemerintah Berbasis Akrual

> Peta isi modul **SAP** (Pelatihan Registrasi KAP 2026) + pelacak status
> ingest. Tiap BAB yang sudah diserap akan punya catatan
> `references/materi/sap/bab-XX-*.md` dan arsip mentah di
> `materials/pelatihan-registrasi-kap-2026/sap/bab-XX/`.

## Status ingest

Legenda: ✅ selesai · 🟡 sebagian (gambar/teks ada di Drive, belum didistilasi) · ⬜ belum

| Bagian | Judul | Status | Catatan |
|---|---|---|---|
| 00 | PENDAHULUAN | ✅ | Teks (paste) + diagram Peta Pelatihan |
| BAB I | Gambaran Umum Akuntansi Pemerintahan Berbasis Akrual | ✅ | Teks (paste) + 4 tabel gambar + klarifikasi tab → `bab-01-gambaran-umum-akuntansi-akrual.md` |
| BAB II | Kerangka Konseptual Penyusunan LK Pemerintah Berbasis Akrual | ✅ | Teks (paste) + piramida karakteristik kualitatif → `bab-02-kerangka-konseptual.md` |
| BAB III | Penyajian Laporan Keuangan | ✅ | Teks (paste) + 20+ format LK + diagram artikulasi & formula konversi → `bab-03-penyajian-laporan-keuangan.md` |
| BAB IV | Bagan Akun Standar (BAS) | ✅ | Teks (paste) + struktur 12 segmen pusat + 6 level daerah + banding Permendagri 64↔90 + contoh kode → `bab-04-bagan-akun-standar.md` |
| BAB V | Siklus Akuntansi Pemerintah | ✅ | Teks (paste) + SAKTI/SIPD + siklus 8 langkah + worked example Dinas Kesehatan → `bab-05-siklus-akuntansi.md` (LATIHAN belum) |
| BAB VI | Akuntansi Pendapatan | ✅ | Teks (paste) + standar LRA/LO + azas bruto + IPSAP 02 + 4 pola jurnal + rangkuman SKPD/PPKD + LATIHAN → `bab-06-akuntansi-pendapatan.md` |
| BAB VII | Akuntansi Belanja dan Beban | ✅ | Teks (paste) + Belanja vs Beban + pengakuan + 4 pola jurnal + ringkasan UP/GU/LS + LATIHAN → `bab-07-akuntansi-belanja-beban.md` |
| BAB VIII | Akuntansi Aset | ✅ | Teks (paste) + aset lancar/nonlancar/tetap + penyisihan/penyusutan/kapitalisasi/KDP/TGR + 2 gambar jurnal + LATIHAN → `bab-08-akuntansi-aset.md` |
| BAB IX | Akuntansi Kewajiban | ⬜ | |
| BAB X | Laporan Keuangan Konsolidasian | ⬜ | |
| BAB XI | Kebijakan Akuntansi, Perubahan Kebijakan, Kesalahan, Perubahan Estimasi, & Operasi yang Dihentikan | ⬜ | |

## Ringkasan cakupan tiap BAB (dari Struktur Modul)

- **BAB I** — Konsepsi akuntansi akrual; persamaan & perbedaan akuntansi
  pemerintahan vs sektor bisnis; LK pemerintahan; kedudukan & fungsi SAP;
  entitas akuntansi & pelaporan; konsepsi dasar; sistem pencatatan.
- **BAB II** — Tujuan kerangka konseptual; lingkungan penyusunan LK pemerintah;
  pengguna LK; entitas pelaporan; peranan & tujuan LK; asumsi dasar &
  karakteristik kualitatif.
- **BAB III** — Tujuan & komponen LK; konsep LRA, LP-SAL, Neraca, LO, LPE, LAK,
  dan CaLK.
- **BAB IV** — Gambaran umum BAS; BAS Pemerintah Pusat; BAS Pemerintah Daerah.
- **BAB V** — Gambaran umum & langkah-langkah siklus akuntansi pemerintah.
- **BAB VI** — Pendapatan: definisi, jenis, pengakuan, pengukuran, pencatatan.
- **BAB VII** — Belanja & beban: definisi, jenis, pengakuan, pengukuran,
  pencatatan.
- **BAB VIII** — Aset: definisi, jenis, pengakuan, pengukuran, pencatatan.
- **BAB IX** — Kewajiban: definisi, jenis, pengakuan, pengukuran, pencatatan.
- **BAB X** — Konsep & prosedur penyusunan LK konsolidasian.
- **BAB XI** — Kebijakan akuntansi, perubahan kebijakan, kesalahan, perubahan
  estimasi, operasi yang dihentikan.

## Cara kerja ingest (ringkas)

1. **Arsip mentah** → `materials/.../sap/bab-XX/` (teks paste verbatim &/atau
   transkripsi gambar). Provenance dicatat di `MANIFEST.md`.
2. **Distilasi** → `references/materi/sap/bab-XX-*.md` (ringkasan terstruktur,
   poin kunci, tabel, definisi + sumber).
3. **Integrasi** → tautkan ke referensi audit yang relevan & perbarui status di
   tabel ini.
