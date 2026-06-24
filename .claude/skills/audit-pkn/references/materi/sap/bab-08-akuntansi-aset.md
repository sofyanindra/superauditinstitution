# Materi SAP — BAB VIII: Akuntansi Aset

> **Provenance.** Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan), BAB VIII.
> Sumber mentah: `materials/pelatihan-registrasi-kap-2026/sap/bab-08/`.

> **Nilai audit (tertinggi).** **Aset tetap** = akun **paling sering jadi
> temuan** di LKPD (tak ditemukan fisik, belum disusutkan, salah kapitalisasi,
> KDP mangkrak, belum bersertifikat). BAB ini = **kriteria akuntansi** yang
> dipakai pada prosedur substantif aset di `04-program-audit-per-akun.md`.

## Peta aset
**Lancar** (≤12 bln/kas): kas & setara kas · investasi jangka pendek · piutang ·
persediaan. **Nonlancar**: investasi jangka panjang · **aset tetap** · dana
cadangan · aset lainnya.

## Aset lancar — titik audit
| Akun | Kriteria SAP | 🔗 Prosedur audit (`04`) |
|---|---|---|
| **Kas & setara kas** | nominal; setara kas deposito **<3 bln**; valas kurs tengah BI | Cash opname, konfirmasi bank, rekonsiliasi |
| **Investasi jk pendek** | 3–12 bln, **risiko rendah**; hasil = PAD | Konfirmasi, uji penilaian |
| **Piutang** | pajak=SKP, retribusi=SKRD/STRD, BL-TPA, BL-TGR=SKTM; **nilai nominal** | Aging, **konfirmasi/SKP**, telusur ketetapan |
| **Penyisihan piutang** | NRV; berdasar **umur piutang**; bukan penghapusan | **Rekalkulasi penyisihan** sesuai kebijakan |
| **Penghapusbukuan** | intra→**ekstrakomptabel**; **PP 14/2005** | Uji dasar hukum & otorisasi |
| **Persediaan** | PSAP 5; **opname fisik**; harga perolehan **terakhir**/standar/wajar; rusak→CaLK | **Stock opname**, uji penilaian & cut-off |

> ⭐ **Piutang**: diakui saat **SKP/SKRD terbit** (akrual) → Dr Piutang / Cr
> Pendapatan-LO (↔ BAB VI). **Penyisihan** by aging → uji NRV. Persediaan
> **rusak/usang tak di neraca, hanya CaLK** → uji eksistensi & pengungkapan.

## Investasi jangka panjang — metode penilaian (uji penilaian)
| Kepemilikan / sifat | Metode |
|---|---|
| **<20%** | **Biaya** |
| **20–50%** atau <20% berpengaruh signifikan | **Ekuitas** |
| **>50%** | **Ekuitas** |
| **Nonpermanen** | **Nilai bersih realisasi (NRV)** |
- Penentu sebenarnya = **tingkat pengaruh/pengendalian** (komisaris/direksi/
  suara), bukan semata %.
- Metode **biaya**: dividen tunai = pendapatan (tak ubah investasi). Metode
  **ekuitas**: bagian laba menambah investasi & pendapatan; dividen tunai
  **mengurangi** investasi; stock dividend → CaLK.
> 🔗 Uji **penilaian investasi** & penyertaan modal (`04`-ekuitas/investasi):
> metode salah → salah saji nilai investasi.

## ⭐ ASET TETAP (fokus audit utama)

**6 kelompok**: Tanah; Peralatan & Mesin; Gedung & Bangunan; Jalan/Irigasi/
Jaringan; Aset Tetap Lainnya; **KDP**.

**Pengakuan** (kumulatif): masa manfaat **>12 bln**; terukur andal; tidak untuk
dijual; untuk digunakan; **hak kepemilikan/penguasaan berpindah**.
> 🔗 **Keberadaan & hak** → cek fisik + **bukti kepemilikan** (sertifikat tanah,
> BPKB); aset belum bersertifikat/dikuasai pihak lain = temuan.

**Pengukuran** = **biaya perolehan** (s.d. siap pakai). Donasi/hibah = **nilai
wajar** (di LRA tanpa jurnal — risiko **kelengkapan** aset hibah). Gabungan =
alokasi proporsional nilai wajar.

### Perlakuan setelah perolehan — 3 area temuan
| Area | Kaidah SAP | 🔗 Audit |
|---|---|---|
| **Kapitalisasi** | **pemeliharaan** (tak tambah nilai) vs **peningkatan** (kapasitas/masa manfaat/mutu → **kapitalisasi**) | Uji pemisahan belanja modal vs barang; salah klasifikasi = temuan |
| **Penyusutan** (PSAP 07) | semua aset tetap **kecuali tanah & KDP**; metode garis lurus / saldo menurun ganda / unit produksi | **Rekalkulasi** akumulasi penyusutan |
| **KDP** | dipindah ke aset definitif saat **substansi selesai & siap pakai**; bayar termin via BAST | Reviu progres fisik, **mangkrak**, reklasifikasi |
| **Revaluasi** | berdasar ketentuan nasional (UU/PP/Perpres) | Uji dasar & nilai |

> ⭐ **Penyusutan SAP ≠ alokasi biaya komersial** — tujuannya **penyesuaian
> nilai agar wajar**. Tetap: Dr Beban Penyusutan / Cr Akumulasi Penyusutan.

## Aset lainnya: TPA, TP/TGR, ATB, kemitraan
- **TP/TGR** (kerugian negara/daerah): tagihan ke pegawai yang menghilangkan/
  menyalahgunakan aset; dinilai sebesar **SKTM / SK Pembebanan**; rujukan
  **Bultek 20/2016 (Akuntansi Kerugian Negara)**.
- **ATB**: software, lisensi, paten, dll. **Kemitraan**: BOT/BOO/BOR.

> ⭐ **TP/TGR contoh kehilangan kendaraan dinas** (nilai buku 48jt = perolehan
> 120jt − akum. penyusutan 72jt):
> 1. Saat hilang (surat polisi): Dr Aset Lainnya 48jt; Dr Akum. Penyusutan 72jt
>    / Cr Aset Tetap 120jt.
> 2. Saat **SKTJM** (cicil 2 th): Dr **TGR** 48jt / Cr Aset Lainnya 48jt.
> 🔗 **Audit kerugian negara/daerah**: pastikan TGR diakui & ditagih; aset
> hilang tanpa TGR = temuan (`06`-PDTT investigatif & `07`-temuan nilai).

## Ringkasan jurnal siklus aset tetap (SKPD/PPKD)
Perolehan LS: BAST → Dr Aset Tetap / Cr **Utang**; SP2D → Dr Utang / Cr RK PPKD
+ Belanja Modal (LRA). Reklasifikasi ke aset lainnya, pelepasan (defisit
penghapusan), penyerahan ke PPKD, penghapusan (dijual → surplus/defisit + hasil
penjualan) — lihat sumber mentah.

> 🔗 Pasangan **RK PPKD ↔ RK SKPD** → eliminasi konsolidasi (BAB V).
> Perolehan LS via **BAST sebelum SP2D** → **utang belanja modal** akhir tahun
> (LATIHAN #3: progres 50% multi-year, BAST tanpa SP2D → akui **KDP/aset +
> utang**) → uji **cut-off & unrecorded liabilities** (BAB VII).

## Latihan (self-check)
1. Beli komputer (imprest) → Dr Aset Tetap / Cr Kas Bend. Peng + Belanja Modal.
2. Beli kendaraan SP2D LS → BAST: Dr Aset Tetap / Cr Utang; SP2D: Dr Utang / Cr
   RK PPKD + Belanja Modal / Cr Perubahan SAL.
3. 50% progres multi-year BAST tanpa SP2D → Dr **KDP** / Cr **Utang** (akui
   akrual; belanja-LRA menyusul saat dibayar).

---

## Catatan verifikasi
- Pengukuran/jurnal mengacu PSAP 05/06/07 + Permendagri 64/2013 & PMK 225/2016;
  TGR per Bultek 20/2016; penghapusan piutang PP 14/2005. Verifikasi versi
  berlaku & **kebijakan akuntansi entitas** (mis. **threshold kapitalisasi**,
  masa manfaat penyusutan) — ini kriteria spesifik temuan.
- KDP dibahas lebih rinci di modul Akuntansi KDP (tidak termasuk modul ini).
