# Materi SAP — BAB VI: Akuntansi Pendapatan

> **Provenance.** Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan), BAB VI.
> Sumber mentah: `materials/pelatihan-registrasi-kap-2026/sap/bab-06/`.

> **Nilai audit.** Pendapatan = akun **berisiko kelengkapan (understatement)**
> tertinggi di LKPD. Standar pengakuan LRA vs LO, **azas bruto**, dan IPSAP 02
> (pendapatan belum disetor) langsung jadi **kriteria temuan** pendapatan.

## A. Pengakuan: LRA (kas) vs LO (akrual)

| | Pendapatan-LRA | Pendapatan-LO |
|---|---|---|
| Dasar | **PSAP 02 par 21** | PSAP terkait LO |
| Diakui saat | **diterima di RKUN/RKUD** (basis kas) | **timbul hak** ATAU **direalisasi** (akrual) |
| Klasifikasi | jenis pendapatan | sumber pendapatan |
| Azas | **bruto** | **bruto** |

- **IPSAP 02** memperluas pendapatan-LRA: termasuk kas di **bendahara
  penerimaan** (bagian BUN/BUD) yang **belum disetor**, kas yang **digunakan
  langsung** satker/SKPD (wajib lapor), **hibah langsung**, & kas via otoritas
  BUN/BUD.
- **Pengembalian/koreksi**:
  | Sifat | LRA | LO |
  |---|---|---|
  | Recurring | pengurang pendapatan-LRA | pengurang pendapatan-LO |
  | Nonrecurring, periode sama | pengurang pendapatan-LRA | pengurang pendapatan-LO |
  | Nonrecurring, periode lalu | **pengurang SAL** | **pengurang Ekuitas** |

> 🔗 **⭐ Implikasi audit** (`04-program-audit-per-akun.md` — Pendapatan):
> - **Azas bruto** → uji apakah pendapatan dicatat **bruto**, bukan neto.
>   Pungutan dicatat neto (biaya dikompensasi) = **understatement pendapatan**
>   → temuan klasik.
> - **IPSAP 02** → uji **kelengkapan**: pendapatan diterima bendahara/SKPD yang
>   **belum disetor/belum tercatat** = risiko pendapatan hilang/kurang catat
>   (telusuri karcis/SKR/STS → kas → LRA).
> - **LRA vs LO timing** → uji **cut-off** & pisah pengakuan kas vs akrual.
> - **Pengembalian periode lalu** → pastikan dibebankan ke **SAL/Ekuitas**, bukan
>   mengurangi pendapatan tahun berjalan (salah saji).

## B. Mekanisme akrual: piutang & realisasi
- **Saat penetapan/SKP terbit** → akui **Pendapatan-LO** & **Piutang** (akrual),
  belum ada LRA.
- **Saat kas diterima** → akui **Pendapatan-LRA** (kas) & hapus piutang di LO.
- Contoh **SKP PKB Rp50jt** (terbit Mar, bayar Agt):
  - Terbit: Dr Piutang Pajak / Cr Pendapatan PKB-LO.
  - Bayar (LO): Dr RK PPKD / Cr Piutang Pajak.
  - Bayar (LRA): Dr Estimasi Perubahan SAL / Cr Pendapatan PKB-LRA.

> 🔗 Akui Piutang saat SKP → **piutang pajak/retribusi** menjadi objek uji
> (`04`: aging, penyisihan, konfirmasi/SKP). Pendapatan-LO > LRA bila ada
> piutang akhir tahun → konsisten dengan **formula konversi** (BAB III).

## C. Empat pola jurnal pendapatan (LRA vs LO)
| Pola | Contoh | Catatan audit |
|---|---|---|
| **Sama** LRA & LO | Pendapatan pajak tunai | Keduanya tercatat |
| **Beda** | Jual aset di atas/bawah nilai buku → LRA catat harga jual; LO catat surplus/defisit | Cek surplus/defisit-LO penjualan aset |
| **LRA saja** (LO hanya Neraca) | Jual aset = nilai buku | Tak ada pendapatan-LO, hanya tukar aset↔kas |
| **LO saja** (LRA tanpa jurnal) | **Hibah barang non-tunai** | Risiko **kelengkapan**: hibah in-kind sering tak tercatat |

> Pasangan **RK PPKD ↔ RK SKPD** & **Kas di Kas Daerah** muncul saat
> penyetoran/pendapatan langsung → 🔗 titik **eliminasi konsolidasi** (BAB V/X).

## Rujukan
- Daerah: **Lampiran II Permendagri 64/2013**. Pusat: **PMK 225/PMK.05/2016**.

## Latihan (self-check)
1. Jurnal penerbitan SKP Daerah → *Dr Piutang / Cr Pendapatan-LO*.
2. Jurnal pajak self-assessment → *saat setor: LO Dr Kas/RK / Cr Pendapatan-LO;
   LRA Dr Perubahan SAL / Cr Pendapatan-LRA*.
3. Jurnal setor retribusi ke Kasda → *Dr RK PPKD / Cr Kas di Bend. Penerimaan*.

---

## Catatan verifikasi
- ⚠️ Indikator BAB VI di materi juga menyebut "akuntansi belanja dan beban" —
  itu materi **BAB VII** (artefak salin).
- Pengakuan & ilustrasi mengacu PSAP 02/IPSAP 02 + Permendagri 64/2013 & PMK
  225/2016; nama akun pusat ≠ daerah. Verifikasi versi BAS yang berlaku (SIPD
  Permendagri 90/2019) saat menyusun jurnal aktual.
