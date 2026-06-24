# SUMBER MENTAH — BAB VII (verbatim/terstruktur)

> Arsip untuk provenance. Versi terstruktur ada di
> `references/materi/sap/bab-07-akuntansi-belanja-beban.md`.
>
> - **Sumber**: Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan). Bagian:
>   **BAB VII — Akuntansi Belanja dan Beban**.
> - **Cara perolehan**: paste manual + 2 gambar (tabel banding Beban vs Belanja;
>   ringkasan jurnal belanja UP/GU/LS SKPD–PPKD).
> - **Tanggal ingest**: 2026-06-24.

Tujuan: memahami akuntansi belanja & beban. Indikator: menjelaskan akuntansi
belanja; akuntansi beban; menyusun akuntansi belanja & beban.

## Beban vs Belanja (gambar)
| | Beban | Belanja |
|---|---|---|
| a | Diukur & diakui basis **akrual** | Diukur & diakui basis **kas** |
| b | Unsur **LO** | Unsur **LRA** |
| c | **Kode Akun 9** (skema Permendagri 64) | **Kode Akun 5** |

## A. AKUNTANSI BELANJA (LRA, basis kas)
- Diakui saat **pengeluaran dari Rekening Kas Umum**. Pengeluaran via bendahara
  pengeluaran → diakui saat **pertanggungjawaban disahkan** unit perbendaharaan.
- BLU mengacu peraturan BLU.
- Klasifikasi: **ekonomi (jenis), organisasi, fungsi**.
  - Ekonomi pusat: pegawai, barang, modal, bunga, subsidi, hibah, bansos,
    lain-lain. Daerah: + **tak terduga**.
  - **Belanja operasi** (manfaat jangka pendek): pegawai, barang, bunga,
    subsidi, hibah, bansos.
  - **Belanja modal** (manfaat >1 periode): tanah, gedung & bangunan, peralatan,
    aset tak berwujud (aset tetap & lainnya).
  - **Belanja lain-lain/tak terduga**: tidak biasa & tidak berulang (bencana).
  - **Transfer keluar**: pengeluaran ke entitas pelaporan lain (dana
    perimbangan, bagi hasil).
  - Organisasi: per K/L (pusat) / Sekretariat DPRD, Sekretariat & dinas/lembaga
    teknis provinsi/kab/kota (daerah). Fungsi: fungsi utama pelayanan.
- **Koreksi belanja (penerimaan kembali)**: periode sama → pengurang belanja;
  periode berikutnya → **pendapatan lain-lain-LRA**.

## B. AKUNTANSI BEBAN (LO, basis akrual)
*(Catatan: intro materi tertulis "terkait belanja LRA" — artefak salin; bagian
ini mengatur BEBAN-LO.)*
- Beban diakui saat: **(1) timbulnya kewajiban; (2) konsumsi aset; (3) penurunan
  manfaat ekonomi/potensi jasa**.
  - Timbul kewajiban = peralihan hak ke pemerintah tanpa kas keluar (mis.
    tagihan telepon/listrik belum dibayar).
  - Konsumsi aset = pengeluaran kas tanpa kewajiban / konsumsi aset nonkas.
  - Penurunan manfaat = **penyusutan/amortisasi**.
- BLU mengacu peraturan BLU.
- Klasifikasi ekonomi (jenis beban) pusat: pegawai, barang, bunga, subsidi,
  hibah, bansos, **penyusutan aset tetap/amortisasi**, transfer, lain-lain.
  Daerah: + **tak terduga**.
- Penyusutan/amortisasi: **garis lurus; saldo menurun ganda; unit produksi**.
- **Beban transfer**: kewajiban mengeluarkan uang ke entitas pelaporan lain
  (diwajibkan peraturan).
- **Koreksi beban (penerimaan kembali)**: periode sama → pengurang beban;
  periode berikutnya → **pendapatan lain-lain**; bila menambah beban →
  pembetulan **ekuitas**.

## C. ILUSTRASI JURNAL BELANJA & BEBAN (4 kondisi)

### 1. Unit Perbendaharaan Umum
- **Sama LRA & LO** (realisasi belanja bansos via SP2D LS):
  - LRA: Dr Belanja Bantuan Sosial / Cr Estimasi Perubahan SAL.
  - LO: Dr **Beban Bantuan Sosial** / Cr Kas Umum Daerah. *(di materi baris LO
    tertulis "Kas Umum Daerah / Kas Umum Daerah" — typo; seharusnya Dr Beban
    Bansos.)*
- **LRA ada, LO tidak (Neraca)** (penyertaan modal via Perda):
  - LRA: Dr Pengeluaran Pembiayaan / Cr Estimasi Perubahan SAL.
  - Neraca: Dr Investasi Jangka Panjang / Cr Kas Umum Daerah.
- **LO ada, LRA tidak** (penurunan nilai investasi non permanen):
  - LRA: Tanpa Jurnal.
  - LO: Dr Beban kerugian penurunan nilai investasi non permanen / Cr Investasi
    non permanen.

### 2. SKPD
- **Sama** (belanja operasional tunai via SP2D LS):
  - LRA: Dr Belanja Operasional / Cr Estimasi Perubahan SAL.
  - LO: Dr Beban Operasional / Cr RK PPKD.
- **Sama** (belanja honorarium via UP/GU):
  - LRA: Dr Belanja honorarium / Cr Estimasi Perubahan SAL.
  - LO: Dr Beban honorarium / Cr Kas di Bendahara Pengeluaran.
  - Mencatat GU: Dr Kas di Bendahara Pengeluaran / Cr RK PPKD.
- **LRA ada, LO tidak (Neraca)** (beli aset via SP2D LS):
  - LRA: Dr Belanja Modal / Cr Estimasi Perubahan SAL.
  - Neraca: Dr Aset / Cr RK PPKD.
- **LO ada, LRA tidak** (hibah barang non-tunai):
  - LRA: Tanpa Jurnal.
  - LO: Dr Beban Hibah-LO / Cr Aset.

## Ringkasan jurnal belanja UP/GU/LS (gambar) — SKPD & PPKD
| Transaksi | Metode | Dok. Sumber | SKPD | PPKD |
|---|---|---|---|---|
| Pencairan UP | UP | SP2D-UP | Dr Kas di Bend.Peng / Cr RK-PPKD | Dr RK-SKPD / Cr Kas di Kasda |
| Belanja Pegawai | UP | Daftar Nominatif | Dr Beban Pegawai / Cr Kas di Bend.Peng; Dr Belanja Pegawai / Cr Est. Perubahan SAL | No Entry |
| Belanja Pegawai | Revolving (GU) | SP2D-GU | Dr Kas di Bend.Peng / Cr RK-PPKD | Dr RK-SKPD / Cr Kas di Kasda |
| Belanja Pegawai | LS | SP2D-LS | Dr Beban Pegawai / Cr RK-PPKD; Dr Belanja Pegawai / Cr Est. Perubahan SAL | Dr RK-SKPD / Cr Kas di Kasda |
| Belanja Barang/Jasa | UP | Bukti Pengel. diotorisasi KPA | Dr Beban Barang/Jasa / Cr Kas di Bend.Peng; Dr Belanja Barang/Jasa / Cr Est. Perubahan SAL | No Entry |
| Belanja Barang/Jasa | Revolving (GU) | SP2D-GU | Dr Kas di Bend.Peng / Cr RK-PPKD | Dr RK-SKPD / Cr Kas di Kasda |
| Belanja Barang/Jasa | Transaksi-LS | BAST | Dr Beban Barang/Jasa / Cr **Utang** | No Entry |
| Belanja Barang/Jasa | Pencairan LS | SP2D-LS | Dr Utang / Cr RK-PPKD; Dr Belanja Barang/Jasa / Cr Est. Perubahan SAL | Dr RK-SKPD / Cr Kas di Kasda |
| Belanja Modal/Aset Tetap | Transaksi-LS | BAST | Dr **Aset Tetap** / Cr **Utang** | No Entry |
| Belanja Modal/Aset Tetap | Pencairan LS | SP2D-LS | Dr Utang / Cr RK-PPKD; Dr Belanja Modal / Cr Est. Perubahan SAL | Dr RK-SKPD / Cr Kas di Kasda |
| Setor sisa UP | — | STS | Dr RK-PPKD / Cr Kas di Bend.Peng | Dr Kas di Kasda / Cr RK-SKPD |

## Catatan rujukan
1. SKPD belanja dari Bendahara Pengeluaran (UP/GU/TU) atau Kas Umum Daerah
   (SP2D LS). Ilustrasi lengkap: **Lampiran II Permendagri 64/2013**.
2. Nama akun pusat ≠ daerah; ilustrasi pusat: **PMK 225/PMK.05/2016** &
   **Perdirjen Perbendaharaan 291/PB/2022**.

## LATIHAN
1. Jurnal jika OPD membeli persediaan ATK dengan dana kas kecil **metode dana
   tetap (imprest fund)**.
2. Jurnal jika OPD membayar jasa pemeliharaan via **SP2D LS**.
3. Jurnal jika akhir tahun **rekanan menyerahkan barang/jasa (BAST)** namun
   **SP2D LS sudah tidak diterbitkan** (tutup buku anggaran).
