# Materi SAP — BAB IV: Bagan Akun Standar (BAS)

> **Provenance.** Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan), BAB IV.
> Sumber mentah: `materials/pelatihan-registrasi-kap-2026/sap/bab-04/` (narasi +
> tabel banding Permendagri 64↔90 + struktur kode 6 level + contoh kode akun).

> **Nilai audit.** BAS = "bahasa" pencatatan keuangan negara. Memahami
> kodefikasi akun membuat pemeriksa bisa **menelusuri transaksi**, mendeteksi
> **salah klasifikasi** (mis. belanja modal dicatat sebagai belanja barang),
> memahami sistem **SAKTI (pusat)** & **SIPD (daerah)**, dan menghubungkan
> akun kas↔akrual.

## A. Gambaran umum
BAS = *chart of accounts* (COA): kodefikasi & klasifikasi transaksi, dipakai
**terintegrasi** lintas tahap (perencanaan → penganggaran → pelaksanaan →
pelaporan) dalam **single framework**. Akun disusun berpedoman **PP 71/2010**.
Fungsi: pedoman pencatatan, pusat aliran data, pengendalian disiplin fiskal,
struktur pelaporan.

## B. BAS Pemerintah Pusat
- Dasar: **PMK 214/PMK.05/2013**; pemutakhiran via Kepdirjen Perbendaharaan
  (terakhir **Kep-291/PB/2022** atas Kep-331/PB/2021).
- **12 segmen**: Satker (6) · KPPN (3) · Akun (6) · Program (7) · Output (7) ·
  Dana (10) · Bank (5) · Kewenangan (1) · Lokasi (4) · Anggaran (1) · Antar
  Entitas (6) · Cadangan (6, belum dipakai).

### ⭐ Kodefikasi akun (digit awal) — paling berguna untuk audit
| Digit awal | Akun |
|---|---|
| **1** | Aset |
| **2** | Kewajiban |
| **3** | Ekuitas |
| **4** | Pendapatan (LRA & LO) |
| **5 & 6** | Belanja/Transfer & Beban |
| **49 & 59** | Pendapatan-LO & **beban non-kas** (penyusutan, amortisasi, penyisihan piutang) |
| **7** | Pembiayaan |
| **8** | Transitoris (non-anggaran) |

> 🔗 **Sambungan ke BAB III**: akun **49/59** = pos akrual yang **tidak ada di
> basis kas** → persis yang muncul saat konversi **LRA→LO** (`bab-03`, formula
> beban penyusutan/penyisihan). Saat audit, akun-akun ini titik fokus uji
> akrual.

### Kelompok akun (tahapan): APBN · DIPA · Komitmen · Realisasi · Transitoris · Neraca
> 🔗 LKPP banding realisasi vs **APBN**; LK K/L banding realisasi vs **DIPA** —
> relevan untuk uji ketaatan anggaran.

### Segmen lain yang relevan audit
- **Dana** (sumber: RM, PNBP, BLU, PLN, PDN, Hibah, SBSN, dll) → uji ketaatan
  penggunaan dana sesuai sumber & batas (mis. PNBP, hibah langsung).
- **Kewenangan**: KP, KD, Dekonsentrasi, Tugas Perbantuan, Desentralisasi,
  Urusan Bersama → menentukan entitas pertanggungjawaban.
- **Antar Entitas** (Due to/Due From) → uji **eliminasi/konsolidasi** &
  transaksi antar entitas.

## C. BAS Pemerintah Daerah
- Dasar: **Permendagri 90/2019** (klasifikasi, kodefikasi, nomenklatur);
  BAS khusus = **Permendagri 19/2020** (pengganti Lampiran III **Permendagri
  64/2013**).
- **6 level kode**: `Akun . Kelompok . Jenis . Objek . Rincian Objek . Sub
  Rincian Objek` + Uraian Akun. Contoh: `1.1.01.01.01.001` Kas di Kas Daerah.

### ⭐ Perubahan klasifikasi Permendagri 64 → 90 (penting untuk audit lintas tahun)

| Area | Permendagri 64 | Permendagri 90 |
|---|---|---|
| **Neraca (akun 1–3)** | Aset/Kewajiban/Ekuitas | **SAMA** |
| **Pendapatan (4), Belanja (5)** | 4.x, 5.1–5.3 | **SAMA** |
| **Transfer** | **akun 6** (6.1 Bagi Hasil, 6.2 Bantuan Keuangan) | **5.4 Belanja Transfer** (masuk Belanja) |
| **Pembiayaan** | akun 7 | **akun 6** |
| **Pendapatan-LO** | akun 8 (termasuk **8.5 Pendapatan Luar Biasa-LO**) | akun 7 (tanpa Pendapatan Luar Biasa-LO) |
| **Beban-LO** | akun 9 | akun 8 (**8.2 Beban Penyusutan & Amortisasi dipisah**) |

> 🔗 **Implikasi audit**: saat membandingkan LKPD **antar tahun** atau lintas
> sistem, perhatikan **pergeseran nomor akun** (Transfer & Pembiayaan berpindah,
> LO 8/9→7/8). Salah memetakan = salah klasifikasi/salah baca tren. Permendagri
> 90/2019 adalah **kriteria** klasifikasi LKPD berbasis **SIPD**.

### Contoh kode akun daerah (acuan telusur)
`1.1.01.01.01.001` Kas di Kas Daerah · `1.5.03.04.01.004` Hak Paten ·
`2.1.01.05.02.001` Utang PPh 22 · `4.1.02.01.01.001` Retribusi Pelayanan
Kesehatan Puskesmas · `5.1.01.04.12.004` Belanja Tunjangan Perumahan DPRD ·
`7.1.01.06.01.001` Pajak Hotel-LO · `8.1.01.01.01.001` Beban Gaji Pokok PNS.

## Latihan
1) Bagaimana pemutakhiran BAS terjadi. 2) Beda segmen BAS pusat vs daerah.
3) Penggunaan BAS terintegrasi perencanaan→pelaporan.

---

## Catatan verifikasi
- ⚠️ Tabel struktur: segmen **Akun** uraian tertulis "Kode Satker" → seharusnya
  **Kode Akun**; segmen **KPPN** tertulis 6 digit di tabel klasifikasi →
  seharusnya **3 digit**.
- ⚠️ Level 1 BAS Daerah menulis **"Pendapatan Daerah" 2×** → satu = **Pendapatan-
  LRA**, satu = **Pendapatan-LO** (akun LO).
- Nomor PMK/Permendagri/Kepdirjen dapat dimutakhirkan. Verifikasi versi berlaku
  (mis. update SIPD/SAKTI & Kepdirjen Perbendaharaan terbaru) sebelum dipakai
  sebagai kriteria.
