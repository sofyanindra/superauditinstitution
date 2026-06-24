# SUMBER MENTAH — BAB V (verbatim/terstruktur)

> Arsip untuk provenance. Versi terstruktur ada di
> `references/materi/sap/bab-05-siklus-akuntansi.md`.
>
> - **Sumber**: Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan). Bagian:
>   **BAB V — Siklus Akuntansi Pemerintah**.
> - **Cara perolehan**: paste manual (multi-batch) + gambar (diagram siklus,
>   tabel jenis LK per level, jurnal ledger akrual/kas, ilustrasi posting,
>   neraca saldo).
> - **Tanggal ingest**: 2026-06-24.
> - **Catatan**: bagian penjurnalan memakai skema kode **Permendagri 64/2013**
>   (8=Pendapatan-LO, 9=Beban; 4/5/6/7 untuk LRA) — berbeda dari pergeseran
>   Permendagri 90 di BAB IV. Worked example = SKPD Dinas Kesehatan (Pemkab).

---

## A. Gambaran umum sistem & siklus

Akuntansi = sistem yang mengolah **input** (bukti transaksi/dokumen) → **proses**
(jurnal, buku besar/BB, buku pembantu/BP) → **output** (laporan keuangan).

### Sistem Akuntansi Pemerintah Pusat — SAKTI
SAKTI (Sistem Aplikasi Keuangan Tingkat Instansi) = aplikasi satker pendukung
implementasi **SPAN**, dari perencanaan hingga pertanggungjawaban. Konsep:
**single database, single entry point, basis akrual**. Periodisasi: Jan–Des,
unaudited, audited. Proses: Penganggaran (modul Penganggaran); Pelaksanaan
(modul Komitmen [Manajemen Supplier & Komitmen], Bendahara, Aset Tetap,
Persediaan, Pembayaran); Pelaporan (modul GL & Pelaporan).
- **Portal SPAN**: interkoneksi SPAN–SAKTI; kirim/terima ADK & validasi (tanpa
  datang ke KPPN). **SMS SPAN**: monitor status ADK. **PIN** menggantikan tanda
  tangan basah.
- **Perbedaan SAKTI vs aplikasi lama**: satu database terpusat; keamanan lebih
  tinggi (enkripsi/dekripsi ADK); multi-OS; user friendly; spesifikasi minimum;
  kinerja konsisten.
- **Keamanan data**: kerahasiaan (enkripsi ADK + registrasi user), integritas
  (hash code), keaslian (PIN).
- **Modul**: Penganggaran, Komitmen, Pembayaran, Bendahara, Persediaan, Aset
  Tetap, Pelaporan, Administrator.
- **Fitur**: Integrasi Database; **Single Entry Point**; konsep **MAKER,
  CHECKER, APPROVER**; **Tracing Jurnal** (telusur jurnal→sumber transaksi via
  double click); **ACL (Access Control List)** (izin rekam/ubah/hapus);
  **Closing Period** (tutup buku; modul lain ikut otomatis); **14 Periode**
  (12 normal + unaudited + audited).

### Kebijakan Umum Akuntansi SAKTI — 2 ledger (double entry)
1. **Accrual Ledger**: transaksi berbasis akrual; jurnal pada titik pengakuan
   akrual; mendukung Neraca, LO, LPE; pendekatan **due to / due from**.
2. **Cash Ledger**: transaksi berbasis kas; jurnal saat kas masuk/keluar dari
   BUN; mendukung **LRA**; pendekatan due to / due from.
Jurnal lainnya (single entry): jurnal anggaran (allotment), jurnal komitmen
(encumbrance), jurnal sub ledger bendahara.

### Jenis LK per level (Tabel 1)
| Laporan | SA-SKPD | SA-PPKD (Konsolidator) |
|---|---|---|
| LRA | YA | YA |
| LO | YA | YA |
| Neraca | YA | YA |
| LPE | YA | YA |
| **LP-SAL** | **TIDAK** | YA |
| **LAK** | **TIDAK** | YA |
| CaLK | YA | YA |

### Sistem Akuntansi Pemerintah Daerah
- **SA-SKPD**: SKPD = entitas akuntansi (pengguna anggaran: dinas/badan/kantor);
  menyusun LRA, LO, Neraca, LPE, CaLK; menyampaikan ke kepala daerah via PPKD.
  Semua penerimaan disetor ke **Kas Umum Daerah (Kasda)**; pengeluaran dari
  Kasda. Pengelola Kasda = **PPKD** (selaku **BUD**). Pembayaran belanja: (1)
  Langsung (LS) oleh BUD; (2) via bendahara pengeluaran (Uang Persediaan/UP).
- **SA-PPKD** terbagi 2: (a) **SA-PPKD sebagai pengguna anggaran** (entitas
  akuntansi) → LRA PPKD, LP-SAL, LO-PPKD, Neraca PPKD, CaLK PPKD; (b)
  **SA-Konsolidator** (wakil pemda, entitas pelaporan) → mencatat transaksi
  **resiprokal** SKPD↔PPKD & konsolidasi seluruh LK → LRA, LP-SAL, LO, Neraca,
  LPE, LAK, CaLK Pemda.
- Hubungan SKPD↔PPKD = analogi **kantor pusat–cabang**: PPKD=pusat, SKPD=cabang.
  Akun resiprokal: SKPD memakai **RK-PPKD**, PPKD memakai **RK-SKPD** (saling
  timbal balik). **SKPKD** (Satuan Kerja Pengelola Keuangan Daerah) menjalankan
  fungsi PPKD **dan** sekaligus SKPD; DPA SKPKD paling lengkap.
- **SIPD** (Permendagri 70/2019): Sistem Informasi Pemerintahan Daerah (info
  pembangunan, keuangan, pemerintahan daerah). **SIPKD**: aplikasi pengelolaan
  keuangan daerah (efisien, ekonomis, efektif, transparan, akuntabel,
  auditabel).

### Siklus akuntansi — 8 langkah (overview)
1. Pencatatan Jurnal Anggaran & Saldo Awal di Buku Jurnal.
2. Analisis Transaksi & Pencatatan Transaksi di Buku Jurnal.
3. Pencatatan Jurnal Penyesuaian.
4. Posting ke Buku Besar.
5. Penyusunan Neraca Saldo Setelah Penyesuaian.
6. Penyusunan Laporan Keuangan (LO, LPE, Neraca, LRA).
7. Pencatatan Jurnal Penutup.
8. Penyusunan Neraca Saldo Setelah Penutupan.

**Penjurnalan dibedakan 2 (skema Permendagri 64):**
- **Jurnal Finansial (LO & Neraca)**: default semua transaksi; akun **1-Aset,
  2-Kewajiban, 3-Ekuitas, 8-Pendapatan-LO, 9-Beban**.
- **Jurnal Anggaran (LRA)**: jika akun **4-Pendapatan-LRA, 5-Belanja,
  6-Transfer, 7-Pembiayaan** & melibatkan **kas** → catat jurnal anggaran
  (selain finansial).

## B. Langkah-langkah siklus (worked example: SKPD Dinas Kesehatan)

### 1. Jurnal Anggaran (LRA) — berdasar DPA
- **PPKD**: Dr Estimasi Pendapatan; Dr Estimasi Penerimaan Pembiayaan; Dr
  Apropriasi Belanja; Dr Apropriasi Pengeluaran Pembiayaan; Dr/Cr Estimasi
  Perubahan SAL. (3.1.2.xx)
- **SKPD**: Dr Estimasi Pendapatan; Dr Estimasi Perubahan SAL; Cr Apropriasi
  Belanja.
- Jurnal Anggaran DIPA = **single entry**, bukan untuk LK tujuan umum.

### 2. Analisis & pencatatan transaksi
- Dasar: **Permendagri 64/2013** (akrual pemda, double entry); BAS s.d. level 5
  (rincian objek).
- **Individual vs Resiprokal**: resiprokal = melibatkan 2 pihak (SKPD & PPKD) →
  SKPD pakai akun **RK-PPKD**, PPKD pakai **RK-SKPD**. Individual = dicatat satu
  pihak.
- Contoh jurnal **finansial** SKPD: Dr Kas di Bendahara Penerimaan (1.1.1.02.01)
  / Cr Pelayanan kesehatan Puskesmas-LO (8.1.2.01.01).
- Contoh jurnal **anggaran** SKPD: Dr Estimasi Perubahan SAL (3.1.2.05.01) / Cr
  Pelay. kesehatan-LRA (4.1.2.01.01).
- **Belanja gaji LS lintas SKPD–PPKD**:
  - Dinas Kesehatan: Dr Belanja Gaji Pegawai / Cr Estimasi Perubahan SAL
    (anggaran); Dr Beban Gaji Pegawai / Cr **RK PPKD** (finansial).
  - PPKD: Dr **RK SKPD** / Cr Estimasi Perubahan SAL.
- Beban (UP): Dr Honorarium (9.1.2.25.03), Dr Beban Persediaan ATK (9.1.2.01.01)
  / Cr Kas di Bendahara Pengeluaran (1.1.1.03.01).
- Pembelian aset LS: Dr Kendaraan Dinas (1.3.2.04.01) / Cr RK PPKD (3.1.3.01.01).

**Jurnal modul SAKTI (pusat):**
- Modul **Bendahara – BPN (Bukti Penerimaan Negara)**: akrual Dr **DDEL**
  (Diterima dari Entitas Lain)/Cr Pendapatan-LO; kas Dr DDEL/Cr Pendapatan-LRA.
- Modul **Pembayaran – SPP (resume tagihan)**: Dr Beban / Cr Belanja yang Masih
  Harus Dibayar (akrual).
- Modul **Pembayaran – SP2D**: akrual Dr Belanja YMHD / Cr **DKEL** (Ditagihkan
  ke Entitas Lain); kas Dr Belanja / Cr DKEL.

### 3. Jurnal Penyesuaian (hanya jurnal finansial, basis akrual)
Tujuan: akui pendapatan pada periode diperoleh & beban pada periode terjadi;
sajikan aset/kewajiban/ekuitas wajar. Contoh:
- Dr Persediaan ATK (1.1.7.01.01) / Cr Beban Persediaan ATK (9.1.2.01.01).
- Dr Beban Penyusutan Alat Angkutan (9.1.7.01.04) / Cr Akumulasi Penyusutan
  (1.3.7.01.04).
- Dr Beban Jasa Listrik (9.1.2.03.03) / Cr Utang Belanja Jasa (2.1.5.02.01).

### 4. Posting ke Buku Besar
Pemindahan jurnal → BB (penggolongan & peringkasan). Contoh: terima UP Rp50jt →
BB Kas di Bendahara Pengeluaran (saldo 1,5jt → 51,5jt) & BB RK PPKD (0 → 50jt).

### 5. Neraca Saldo Setelah Penyesuaian (Dinas Kesehatan, 31/12/2014)
Total Debit = Kredit = **Rp4.312.625.000**. Memuat akun riil (1,2,3) + nominal
LRA (4,5) + nominal LO (8,9) berpasangan (mis. Gaji Pokok di 5.1.1.01.01 belanja
**dan** 9.1.1.01.01 beban-LO). Saldo a.l.: RK PPKD (Cr) Rp1.768.415.000;
Estimasi Perubahan SAL (Cr) Rp1.781.750.000; Ekuitas (Cr) Rp639.500.000.

### 6. Penyusunan Laporan Keuangan
LK pokok 7 komponen (LRA, LP-SAL, LO, LPE, Neraca, LAK, CaLK). Mekanisme:
saldo akun di neraca saldo dengan **3 digit awal sama** dengan pos LK
dipindahkan ke LK; bila >1 akun → total saldo.

### 7. Jurnal Penutup (setelah LK disusun)
Menihilkan akun nominal/sementara LRA & LO agar tak jadi saldo awal tahun
berikutnya.
- **Penutup LRA**: tutup Apropriasi Belanja, Estimasi Pendapatan, Estimasi
  Perubahan SAL, pendapatan-LRA & belanja → **Surplus/Defisit-LRA (3.1.2.06.01)
  = Rp1.781.750.000** → ditutup ke Estimasi Perubahan SAL.
- **Penutup LO**: tutup pendapatan-LO & beban-LO → **Surplus/Defisit-LO
  (3.1.1.02.01) = Rp1.726.875.000** → ditutup ke **Ekuitas (3.1.1.01.01)**.

### 8. Neraca Saldo Setelah Penutupan (Dinas Kesehatan, 31/12/2014)
Setelah posting jurnal penutup, akun nominal nihil; tersisa akun riil (neraca).
Total Debit = Kredit = **Rp3.620.625.000**. Saldo a.l.: Surplus/Defisit-LO (Dr)
Rp1.726.875.000; Surplus/Defisit-LRA (Dr) Rp1.781.750.000; RK PPKD (Cr)
Rp1.768.415.000; Akumulasi Penyusutan, Utang PPh 21/PPN/Belanja Jasa, dll.

*(Catatan: pada contoh materi ada beda angka kecil antara neraca saldo
penyesuaian vs penutupan — mis. Persediaan ATK 1.000.000 → 500.000; Utang PPh 21
5.235.000 → 3.885.000 — kemungkinan artefak/penyederhanaan contoh.)*

*(Status: bagian LATIHAN BAB V belum di-paste pada saat ingest; akan ditambahkan
bila tersedia.)*
