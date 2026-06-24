# Materi SAP — BAB V: Siklus Akuntansi Pemerintah

> **Provenance.** Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan), BAB V.
> Sumber mentah: `materials/pelatihan-registrasi-kap-2026/sap/bab-05/`.
> *(LATIHAN BAB V belum tersedia saat ingest — akan ditambah bila ada.)*

> **Nilai audit.** BAB ini memetakan **proses akuntansi entitas** (yang
> dipahami pemeriksa pada tahap perencanaan), **pengendalian TI** sistem
> (SAKTI/SIPD = ITGC), serta **area substantif** (jurnal penyesuaian,
> konsolidasi resiprokal) yang menjadi titik uji.

## A. Sistem akuntansi: SAKTI (pusat) & SIPD/SIPKD (daerah)

**SAKTI** (pendukung **SPAN**): single database, single entry point, akrual.
Fitur yang = **pengendalian umum TI (ITGC)** untuk dievaluasi pemeriksa:

| Fitur SAKTI | Pengendalian audit terkait |
|---|---|
| **MAKER–CHECKER–APPROVER** | Pemisahan tugas (*segregation of duties*) |
| **Tracing Jurnal** | Jejak audit (jurnal ↔ sumber transaksi) |
| **ACL** (izin rekam/ubah/hapus) | Pengendalian akses |
| **Closing Period** | Kontrol penutupan periode |
| **PIN / hash / enkripsi ADK** | Otorisasi, integritas, kerahasiaan data |
| **14 Periode** (12 + unaudited + audited) | Status data yang diperiksa |

> 🔗 `03-perencanaan-risiko-materialitas.md` (pemahaman SPI/IT): saat audit
> LKPP/LKPD berbasis SAKTI/SIPD, evaluasi ITGC ini menentukan **risiko
> pengendalian** & seberapa bisa mengandalkan sistem.

**Dua ledger SAKTI**: **Accrual Ledger** (Neraca/LO/LPE) & **Cash Ledger**
(LRA), keduanya **due to/due from**. → 🔗 wujud **triple entry** (BAB I) & beda
**LRA(kas) vs LO(akrual)** (BAB III).

**SIPD** (Permendagri 70/2019) & **SIPKD** = sistem informasi/keuangan daerah.

## B. Entitas & konsolidasi daerah (area risiko audit tinggi)

| | SA-SKPD | SA-PPKD (pengguna anggaran) | SA-Konsolidator |
|---|---|---|---|
| Peran | Entitas akuntansi | Entitas akuntansi | Entitas pelaporan (wakil pemda) |
| LK | LRA, LO, Neraca, LPE, CaLK (**tanpa LP-SAL & LAK**) | + LP-SAL | LK Pemda lengkap (7 komponen) |

- Hubungan SKPD↔PPKD = **kantor pusat–cabang**. Akun resiprokal: **RK-PPKD**
  (di SKPD) ↔ **RK-SKPD** (di PPKD). **SKPKD** = satker yang merangkap PPKD &
  SKPD.
- **DDEL/DKEL** (Diterima/Ditagihkan dari/ke Entitas Lain) = transaksi antar
  entitas (mis. dana dari BUN di pusat).

> 🔗 **⭐ Titik uji audit konsolidasi**: saldo **RK-PPKD harus = RK-SKPD**
> (saling hapus saat konsolidasi); **DDEL/DKEL** harus tereliminasi. Saldo
> resiprokal tak nyambung = **salah saji LKPD klasik** → temuan. Relevan ke
> `04` (ekuitas/konsolidasi) & pemeriksaan LK Konsolidasian (BAB X).
> SA-SKPD tak menyusun **LP-SAL & LAK** → konsisten dengan pengecualian penyaji
> di BAB III.

## C. Siklus 8 langkah

1. Jurnal Anggaran & Saldo Awal → 2. Analisis & Pencatatan Transaksi →
3. Jurnal Penyesuaian → 4. Posting Buku Besar → 5. Neraca Saldo Setelah
Penyesuaian → 6. Penyusunan LK → 7. Jurnal Penutup → 8. Neraca Saldo Setelah
Penutupan.

**Dua jurnal untuk transaksi kas** (skema Permendagri 64): **Jurnal Finansial**
(akun 1/2/3/8-LO/9-Beban → LO & Neraca) **+ Jurnal Anggaran** (akun
4/5/6/7 → LRA). Transaksi non-kas → hanya finansial.
> 🔗 Inilah mengapa satu belanja kas menghasilkan **belanja (LRA)** *dan*
> **beban (LO)** — sumber beda angka yang direkonsiliasi dengan formula
> konversi LRA→LO (BAB III).

### ⭐ Jurnal penyesuaian = area substantif akhir tahun
| Penyesuaian | Prosedur audit terkait (`04`) |
|---|---|
| Persediaan (Dr Persediaan / Cr Beban) | **Stock opname** & uji penilaian |
| Penyusutan (Dr Beban Penyusutan / Cr Akum.) | **Rekalkulasi** penyusutan |
| Beban YMHD / utang (Dr Beban / Cr Utang) | **Cut-off** & *search for unrecorded liabilities* |

### Jurnal penutup
Menihilkan akun nominal: **Penutup LRA** → Surplus/Defisit-LRA → Estimasi
Perubahan SAL; **Penutup LO** → Surplus/Defisit-LO → **Ekuitas**.
> 🔗 Surplus/Defisit-LO menutup ke Ekuitas → menjelaskan artikulasi **LO→LPE→
> Neraca** (BAB III).

## Worked example (Dinas Kesehatan, Pemkab)
Neraca Saldo Setelah Penyesuaian: Dr=Cr **Rp4.312.625.000**; menampilkan akun
**belanja (5.x) & beban-LO (9.x) berpasangan**. Setelah penutupan: Dr=Cr
**Rp3.620.625.000** (tersisa akun riil). RK PPKD Rp1.768.415.000 (akun
resiprokal yang dikonsolidasi).

---

## Catatan verifikasi
- ⚠️ **Inkonsistensi kode akun**: BAB V (penjurnalan) memakai **Permendagri 64**
  (8=Pendapatan-LO, 9=Beban; 6=Transfer, 7=Pembiayaan), sedangkan BAB IV
  menampilkan **Permendagri 90** (7=Pendapatan-LO, 8=Beban; Transfer=5.4,
  Pembiayaan=6). Saat memakai contoh jurnal, **sesuaikan ke skema BAS yang
  berlaku** di entitas/tahun yang diperiksa (SIPD umumnya Permendagri 90).
- Contoh numerik memuat beda kecil antar tabel (persediaan, utang PPh 21) —
  artefak/penyederhanaan materi, bukan kaidah.
- Nomor aplikasi/sistem (SAKTI, SPAN, SIPD/SIPKD) & regulasinya dapat
  dimutakhirkan — verifikasi versi yang berlaku.
