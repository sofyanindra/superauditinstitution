# SUMBER MENTAH — BAB VI (verbatim/terstruktur)

> Arsip untuk provenance. Versi terstruktur ada di
> `references/materi/sap/bab-06-akuntansi-pendapatan.md`.
>
> - **Sumber**: Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan). Bagian:
>   **BAB VI — Akuntansi Pendapatan**.
> - **Cara perolehan**: paste manual + 2 gambar (rangkuman jurnal standar
>   pendapatan SKPD & PPKD).
> - **Tanggal ingest**: 2026-06-24.

Tujuan: memahami akuntansi pendapatan. Indikator: menjelaskan standar akuntansi
pendapatan-LO & LRA; (di materi tertulis juga "menganalisis akuntansi belanja
dan beban" — tampaknya artefak salin dari BAB VII).

## A. STANDAR AKUNTANSI PENDAPATAN

### Pendapatan-LRA
- **PSAP 02 par 21**: Pendapatan-LRA diakui saat **diterima pada RKUN/RKUD**.
- **IPSAP 02** memperluas cakupan, pendapatan-LRA mencakup:
  1. Kas diterima pada RKUN/RKUD.
  2. Kas diterima **bendahara penerimaan** (bagian BUN/BUD), belum disetor ke
     RKUN/RKUD s.d. tanggal pelaporan.
  3. Kas diterima **satker/SKPD & digunakan langsung** tanpa disetor, syarat
     wajib lapor ke BUN/BUD untuk diakui.
  4. Kas dari **hibah langsung DN/LN** untuk mendanai pengeluaran entitas,
     wajib lapor ke BUN/BUD.
  5. Kas diterima **entitas lain di luar pemerintah** berdasar otoritas BUN/BUD.
- Diklasifikasikan menurut jenis pendapatan. **Transfer masuk** = penerimaan
  dari entitas pelaporan lain (dana perimbangan pusat, bagi hasil provinsi).
- **Azas bruto**: membukukan penerimaan **bruto**, tidak neto. Dikecualikan bila
  pengurang (biaya) bersifat **variabel** & tak dapat dianggarkan (proses belum
  selesai).
- BLU: pendapatan diakui mengacu peraturan BLU.
- **Pengembalian/koreksi**:
  - Recurring (normal & berulang) → pengurang pendapatan-LRA.
  - Nonrecurring periode penerimaan sama → pengurang pendapatan-LRA periode sama.
  - Nonrecurring periode sebelumnya → **pengurang Saldo Anggaran Lebih (SAL)**
    pada periode ditemukan.

### Pendapatan-LO
- Diakui saat: (a) **timbulnya hak** atas pendapatan; (b) **direalisasi** (aliran
  masuk sumber daya ekonomi).
- Berdasar peraturan → diakui saat **timbul hak menagih**. Imbalan pelayanan
  selesai → saat timbul hak menagih imbalan. Direalisasi → hak diterima tanpa
  penagihan terlebih dahulu.
- Diklasifikasikan menurut **sumber pendapatan** (pusat: perpajakan, bukan
  pajak, hibah; daerah: PAD, transfer, lain-lain pendapatan yang sah).
- **Azas bruto** (kecuali pengurang variabel & tak dapat diestimasi). BLU
  mengacu peraturan BLU.
- **Pengembalian/koreksi**:
  - Recurring → pengurang pendapatan.
  - Nonrecurring periode sama → pengurang pendapatan periode sama.
  - Nonrecurring periode sebelumnya → **pengurang ekuitas** pada periode
    ditemukan.

## B. Akuntansi pendapatan pada SKPD & PPKD (rangkuman jurnal — gambar)

**Jurnal standar pendapatan di SKPD:**
| No | Transaksi | Pencatatan SKPD | Pencatatan PPKD |
|---|---|---|---|
| 1 | Penerbitan SK | Dr Piutang / Cr Pendapatan…-LO | No Entry |
| 2 | Penerimaan pembayaran | Dr Kas di Bend. Penerimaan / Cr Piutang; Dr Perubahan SAL / Cr Pendapatan…-LRA | No Entry |
| 3 | Penyetoran pendapatan SKPD ke Kas Daerah | Dr RK PPKD / Cr Kas di Bend. Penerimaan | Dr Kas di Kas Daerah / Cr RK SKPD |
| 4 | Pendapatan langsung disetor ke kas umum daerah | Dr RK PPKD / Cr Piutang; Dr Perubahan SAL / Cr Pendapatan…-LRA | Dr Kas di Kas Daerah / Cr RK SKPD |

**Jurnal standar pendapatan di PPKD:**
| No | Transaksi | Pencatatan SKPD | Pencatatan PPKD |
|---|---|---|---|
| 1 | Penetapan pendapatan | No Entry | Dr Piutang / Cr Pendapatan…-LO |
| 2 | Penerimaan pendapatan | No Entry | Dr Kas di Kas Daerah / Cr Piutang; Dr Perubahan SAL / Cr Pendapatan…-LRA |
| 3 | Pendapatan tanpa penetapan | No Entry | Dr Kas di Kas Daerah / Cr Pendapatan…-LO; Dr Perubahan SAL / Cr Pendapatan…-LRA |

## C. Ilustrasi jurnal pendapatan (4 kondisi)

### 1. Perbendaharaan Umum
- **Sama LRA & LO** (realisasi pendapatan pajak Rp xxx):
  - LRA: Dr Estimasi Perubahan SAL / Cr Pendapatan Pajak.
  - LO: Dr Kas Umum Daerah / Cr Pendapatan Pajak-LO.
- **Beda LRA & LO** (jual aset investasi permanen, nilai buku Rp xxx, harga Rp
  xxx+3):
  - LRA: Dr Estimasi Perubahan SAL Rp xxx+3 / Cr Pendapatan penjualan aset Rp xxx+3.
  - LO: Dr Kas Umum Daerah Rp xxx+3 / Cr Aset Investasi-Neraca Rp xxx; Cr Surplus
    penjualan aset-LO Rp +3.
- **LRA ada, LO tidak (hanya Neraca)** (jual aset = nilai buku):
  - LRA: Dr Estimasi Perubahan SAL / Cr Pendapatan penjualan aset.
  - Neraca: Dr Kas Umum Daerah / Cr Aset Investasi-Neraca.
- **LO ada, LRA tidak (non-tunai)** (hibah barang Rp xxx):
  - LRA: **Tanpa Jurnal** (LRA basis kas).
  - LO: Dr Aset / Cr Pendapatan Hibah-LO.

### 2. SKPD
- **Sama** (pendapatan pajak Rp xxx):
  - LRA: Dr Estimasi Perubahan SAL / Cr Pendapatan Pajak.
  - LO (via Bend. Penerimaan): Dr Kas di Bend. Penerimaan / Cr Pendapatan
    Pajak-LO; saat setor: Dr RK PPKD / Cr Kas di Bend. Penerimaan.
  - LO (WP setor langsung ke Kasda): Dr RK PPKD / Cr Pendapatan Pajak-LO.
- **Beda** (jual aset Rp xxx, akum. penyusutan Rp 5, harga Rp xxx-2):
  - LRA: Dr Estimasi Perubahan SAL Rp xxx-2 / Cr Pendapatan penjualan aset Rp xxx-2.
  - LO: Dr RK PPKD Rp xxx-2; Dr Akumulasi Penyusutan Rp 5 / Cr Aset-Neraca Rp xxx;
    Cr Surplus penjualan aset-LO Rp +3.
- **Contoh SKP PKB** (terbit 31 Mar Rp50jt, dibayar via Kasda Agustus):
  - Saat terbit SKP (LO): Dr Piutang Pajak 50jt / Cr Pendapatan PKB-LO 50jt.
  - Saat bayar (LO): Dr R/K PPKD 50jt / Cr Piutang Pajak 50jt.
  - Saat bayar (LRA): Dr Estimasi Perubahan SAL 50jt / Cr Pendapatan PKB-LRA 50jt.
- **LRA ada, LO tidak** (jual aset = nilai buku, akum. penyusutan Rp 5):
  - LRA: Dr Estimasi Perubahan SAL Rp xxx-5 / Cr Pendapatan penjualan aset Rp xxx-5.
  - Neraca: Dr RK PPKD Rp xxx-5; Dr Akumulasi Penyusutan Rp 5 / Cr Aset-Neraca Rp xxx.
- **LO ada, LRA tidak** (hibah barang non-tunai Rp xxx):
  - LRA: Tanpa Jurnal. LO: Dr Aset / Cr Pendapatan Hibah-LO.

### Catatan rujukan
1. Ilustrasi lengkap jurnal pendapatan daerah: **Lampiran II Permendagri No. 64
   Tahun 2013** (Penerapan SAP Akrual pada Pemda).
2. Nama akun pusat ≠ daerah; ilustrasi pusat: **PMK No. 225/PMK.05/2016**
   (Penerapan SAP Akrual pada Pemerintah Pusat).

## LATIHAN
1. Jurnal saat dinas pendapatan menerbitkan Surat Ketetapan Pajak Daerah (SKPD).
2. Jurnal saat wajib pajak menghitung & menyetor pajak secara self assessment.
3. Jurnal saat pengumpul retribusi menyetorkan hasil pengumpulan ke Kasda.
