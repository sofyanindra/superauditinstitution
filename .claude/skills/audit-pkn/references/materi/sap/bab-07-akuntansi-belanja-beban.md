# Materi SAP — BAB VII: Akuntansi Belanja dan Beban

> **Provenance.** Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan), BAB VII.
> Sumber mentah: `materials/pelatihan-registrasi-kap-2026/sap/bab-07/`.

> **Nilai audit (tertinggi).** Belanja = **area temuan terbesar** di LKPD
> (kekurangan volume, kelebihan bayar, salah klasifikasi, belanja fiktif).
> Pembedaan **Belanja (kas/LRA)** vs **Beban (akrual/LO)**, pengakuan, dan
> klasifikasi langsung jadi **kriteria temuan**.

## Belanja vs Beban (inti)
| | **Belanja** | **Beban** |
|---|---|---|
| Basis | **Kas** | **Akrual** |
| Laporan | **LRA** | **LO** |
| Kode (Permendagri 64) | **5** | **9** |
| Diakui saat | pengeluaran dari RKU / pengesahan SPJ (UP) | timbul kewajiban / konsumsi aset / penurunan manfaat |

## A. Belanja (LRA)
- **Pengakuan**: saat keluar dari RKU; via bendahara → saat **SPJ disahkan**.
- **Klasifikasi**: ekonomi (jenis), organisasi, fungsi.
  - **Belanja operasi** (jangka pendek) vs **Belanja modal** (>1 periode → aset
    tetap/lainnya) vs **lain-lain/tak terduga**. **Transfer keluar** terpisah.
- **Koreksi belanja**: periode sama → pengurang belanja; **periode berikutnya →
  pendapatan lain-lain-LRA** (bukan mengurangi belanja tahun berjalan).

> 🔗 **⭐ Audit belanja** (`04`):
> - **Klasifikasi belanja modal vs barang/jasa** → uji **kapitalisasi**: belanja
>   yang menambah masa manfaat = modal (kapitalisasi ke aset); salah klasifikasi
>   = temuan + salah saji aset.
> - **Pengakuan via SPJ/SP2D** → **vouching** ke SP2D-UP/GU/LS, **BAST**, bukti
>   bayar; uji **validitas & cut-off**.
> - **Koreksi periode lalu** → pastikan ke **pendapatan lain-lain-LRA**, bukan
>   mengurangi belanja → cegah salah saji.

## B. Beban (LO)
- **Tiga saat pengakuan**: (1) **timbulnya kewajiban** (peralihan hak tanpa kas
  keluar — mis. tagihan listrik belum dibayar); (2) **konsumsi aset**; (3)
  **penurunan manfaat** (penyusutan/amortisasi).
- Penyusutan: garis lurus / saldo menurun ganda / unit produksi.
- **Koreksi beban**: periode sama → pengurang beban; periode berikutnya →
  pendapatan lain-lain; bila **menambah beban** → **pembetulan ekuitas**.

> 🔗 **Audit beban** (`04`): **timbulnya kewajiban** → **utang belanja/beban
> YMHD** akhir tahun → uji *cut-off* & **search for unrecorded liabilities**.
> **Penyusutan** → rekalkulasi (↔ BAB III & VIII).

## C. Empat pola jurnal Belanja-LRA vs Beban-LO
| Pola | Contoh | Catatan audit |
|---|---|---|
| **Sama** | Belanja operasional/bansos tunai | Belanja (LRA) **dan** Beban (LO) tercatat |
| **LRA saja** (LO=Neraca) | **Belanja modal** beli aset; penyertaan modal (pembiayaan) | Belanja-LRA + aset/investasi (Neraca), **tanpa beban** |
| **LO saja** (LRA tanpa jurnal) | Penurunan nilai investasi; **hibah barang non-tunai** | **Beban tanpa belanja** — risiko kelengkapan beban in-kind |
| (Pembiayaan) | Penyertaan modal | Masuk **pengeluaran pembiayaan**, bukan belanja |

## ⭐ Mekanisme UP/GU/LS & akrual akhir tahun (titik audit kunci)
- **UP/GU** (uang persediaan/ganti uang) via Bendahara Pengeluaran; **LS** via
  Kas Umum Daerah.
- **Belanja Barang/Modal LS**: saat **BAST** → Dr Beban/Aset / Cr **Utang**
  (akrual, **belum** ada SP2D); saat **SP2D-LS** → Dr Utang / Cr RK-PPKD +
  Belanja (LRA).

> 🔗 **⭐ Skenario LATIHAN #3** (BAST diterima akhir tahun tapi SP2D LS tak
> terbit karena tutup buku) = kasus **utang belanja / beban YMHD** klasik:
> **beban & utang/aset diakui akrual** (LO/Neraca) meski **belanja (LRA) belum**
> tercatat (kas belum keluar). Inilah **gap LRA-kas vs LO-akrual** (BAB III) dan
> area **cut-off + unrecorded liabilities** yang wajib diuji pemeriksa.
> Pasangan **RK-PPKD ↔ RK-SKPD** → eliminasi konsolidasi (BAB V).

## Rujukan
- Daerah: **Lampiran II Permendagri 64/2013**. Pusat: **PMK 225/PMK.05/2016** &
  **Perdirjen 291/PB/2022**.

## Latihan (self-check)
1. Beli ATK kas kecil (imprest) → Dr Beban/Belanja Barang / Cr Kas Bend. Peng.
2. Jasa pemeliharaan SP2D LS → BAST: Dr Beban / Cr Utang; SP2D: Dr Utang / Cr
   RK-PPKD + Belanja / Cr Est. Perubahan SAL.
3. BAST akhir tahun tanpa SP2D LS → Dr Beban/Aset / Cr **Utang** (akui akrual;
   belanja-LRA menyusul tahun berikutnya saat dibayar) → **temuan utang belanja
   bila tak diakui**.

---

## Catatan verifikasi
- ⚠️ Intro bagian B materi tertulis "terkait belanja LRA" → seharusnya
  **beban-LO** (artefak salin). Indikator bab juga campur.
- ⚠️ Contoh jurnal beban bansos (Perbendaharaan Umum): baris LO di materi
  tertulis "Kas Umum Daerah / Kas Umum Daerah" → seharusnya **Dr Beban Bantuan
  Sosial / Cr Kas Umum Daerah**.
- Kode akun memakai skema **Permendagri 64** (5=Belanja, 9=Beban); pada SIPD
  (Permendagri 90) penomoran berbeda — sesuaikan dengan BAS yang berlaku.
