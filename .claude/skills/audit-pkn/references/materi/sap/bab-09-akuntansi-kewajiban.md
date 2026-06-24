# Materi SAP — BAB IX: Akuntansi Kewajiban

> **Provenance.** Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan), BAB IX.
> Sumber mentah: `materials/pelatihan-registrasi-kap-2026/sap/bab-09/`.

> **Nilai audit.** Kewajiban = akun berisiko **understatement/kelengkapan**
> tertinggi → asersi utama **kelengkapan**. Inti uji = ***search for unrecorded
> liabilities*** (`04`).

## Kewajiban (umum)
- **Definisi**: utang dari peristiwa masa lalu → aliran **keluar** sumber daya.
- **Pengakuan**: saat **dana pinjaman diterima** atau **kewajiban timbul**
  (besar kemungkinan & terukur andal).
- **Pengukuran**: **nilai nominal**; valas → kurs tengah BI.

## A. Kewajiban jangka pendek (≤12 bln)
| Jenis | Catatan | 🔗 Audit |
|---|---|---|
| **Bagian lancar utang JP** | porsi jatuh tempo ≤12 bln (mis. 10 M dari 100 M) | Uji reklasifikasi & penyajian |
| **Utang Bunga** | bunga terutang akhir periode | *Accrued interest*, rekalkulasi |
| **Utang PFK** | **Penerimaan PFK − Pengeluaran PFK** (pungutan pihak ketiga belum disetor) | ⭐ **PFK belum disetor = temuan klasik** (pajak/iuran dipungut tak disetor) |
| **Utang belanja** | beban diakui, kas belum keluar | **Cut-off & unrecorded liabilities** |

> ⭐ **Utang belanja (BAST tanpa pembayaran)** — contoh ATK Rp5 jt: saat **BAST**
> Dr Beban / Cr **Utang Belanja**; saat **bayar (UP)** Dr Utang / Cr Kas + Belanja
> (LRA). → 🔗 inti **gap LRA-kas vs LO-akrual** (BAB VII) & **search for
> unrecorded liabilities** (`04`).

## B. Kewajiban jangka panjang (>12 bln)
- **Refinancing/roll-over**: tetap jangka panjang **hanya jika** ada **perjanjian
  pendanaan kembali sebelum LK disetujui** & kebijakan di tangan entitas; bila
  tidak → **jangka pendek**.
- **Covenant** (payable on demand bila dilanggar): tetap JP hanya jika pemberi
  pinjaman setuju tak menagih **dan** tak mungkin pelanggaran berikutnya dalam
  12 bln.
- Klasifikasi: Utang DN-Perbankan; Utang DN-Obligasi; Utang Luar Negeri; Utang
  JP Lainnya.

> 🔗 **Audit penyajian** (`08`-reviu SAP): klasifikasi jangka pendek vs panjang
> = pertimbangan **substansi** (refinancing, covenant) → salah klasifikasi
> mempengaruhi rasio likuiditas & opini.

### Jurnal kewajiban jangka panjang (PPKD)
| Transaksi | Inti jurnal |
|---|---|
| Penerimaan pembiayaan | Dr Kas / Cr Kewajiban JP (Neraca); Dr Perubahan SAL / Cr Penerimaan Pembiayaan (LRA) |
| Bayar bunga | Dr **Beban Bunga** / Cr Kas (LO); Dr **Bunga Utang** / Cr Perubahan SAL (LRA) |
| Pelunasan pokok | Dr Kewajiban JP / Cr Kas; Dr **Pengeluaran Pembiayaan** / Cr Perubahan SAL |
| Reklasifikasi | Dr Kewajiban JP / Cr **Bagian Lancar** Kewajiban JP |

> ⭐ **Bunga vs pokok**: **bunga → beban/operasi (LO) + LRA**; **pokok →
> pembiayaan** (bukan belanja). Penerimaan pinjaman → **penerimaan pembiayaan**,
> bukan pendapatan. → 🔗 konsisten dengan klasifikasi LAK (BAB III) & uji
> kewajaran pembiayaan.

## Latihan (self-check)
1. **Tagihan listrik akhir tahun** (bayar tahun berikutnya) → Dr Beban Jasa
   Listrik / Cr **Utang Belanja Jasa** (akrual; belanja-LRA menyusul saat
   dibayar). → uji **cut-off/unrecorded liabilities**.
2. **Penyerahan aset tetap dari perjanjian pembiayaan pusat** → Dr Aset Tetap /
   Cr **Kewajiban Jangka Panjang** (utang ke Pempus) → uji eksistensi utang &
   penyajian.

---

## Catatan verifikasi
- ⚠️ Pada paste terdapat **kalimat nyasar** ("…Now, let go… Enjoy the journey")
  di tengah uraian Utang DN-Obligasi → **bukan bagian materi**, diabaikan.
- Pengakuan/penyajian mengacu PSAP 09 + Permendagri 64/2013 & PMK 225/2016.
  Verifikasi kebijakan akuntansi entitas (mis. pengakuan utang belanja & PFK).
