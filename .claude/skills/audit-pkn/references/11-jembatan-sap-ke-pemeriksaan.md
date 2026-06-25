# 11 — Jembatan SAP → Pemeriksaan (per akun): dari kriteria akuntansi ke KKP

> **Tujuan.** Menghubungkan **materi SAP** (kriteria akuntansi yang baru diserap,
> `references/materi/sap/`) dengan **program audit** (`04-program-audit-per-akun.md`)
> agar pemeriksa dapat **mengisi KKP** secara langsung: tiap akun → **kriteria
> (PSAP)** → **asersi** → **risiko salah saji** → **prosedur** → **temuan khas**.
> Gunakan bersama template `templates/kertas-kerja-pemeriksaan.md`.

Cara pakai: pilih akun, salin baris ke KKP, jalankan prosedur, dokumentasikan
bukti & simpulan. Kriteria selalu kutip **pasal/PSAP spesifik** (verifikasi ke
PP 71/2010 & kebijakan akuntansi entitas).

## Matriks jembatan per akun

| Akun | Kriteria SAP (rujuk materi) | Asersi utama | Risiko salah saji khas | Prosedur kunci (`04`) | Temuan khas |
|---|---|---|---|---|---|
| **Kas & setara kas** | PSAP 01; setara kas deposito **<3 bln**; nominal; valas kurs tengah BI (BAB VIII) | Keberadaan, kelengkapan | Saldo bendahara tak disetor; kas fiktif; rekening tak dilaporkan | Cash opname; konfirmasi bank; rekonsiliasi; cut-off | Selisih kas; UP/TUP belum disetor 31 Des |
| **Investasi jangka pendek/panjang** | PSAP 06; metode **biaya/ekuitas/NRV** per % & pengaruh (BAB VIII) | Penilaian, hak | Metode penilaian salah; penyertaan modal kurang catat | Uji metode vs % kepemilikan & pengaruh; konfirmasi; uji hasil investasi | Penyertaan modal tak sesuai metode ekuitas |
| **Piutang + penyisihan** | PSAP; piutang=SKP/SKRD nominal; **penyisihan by umur (NRV)**; hapus buku PP 14/2005 (BAB VIII) | Keberadaan, penilaian | Penyisihan kurang/tak ada; piutang kadaluarsa; piutang fiktif | Aging; rekalkulasi penyisihan; konfirmasi/telusur SKP; uji penghapusan | Piutang tak disisihkan; penghapusan tanpa dasar |
| **Persediaan** | PSAP 05; **opname fisik**; harga perolehan **terakhir**/standar/wajar; rusak→CaLK (BAB VIII) | Keberadaan, penilaian | Opname tak dilakukan; usang dicatat; metode beda | Hadiri/uji stock opname; uji penilaian & cut-off | Persediaan tak diopname; barang usang masih di neraca |
| **Aset tetap + penyusutan** | PSAP 07; biaya perolehan; **kapitalisasi** (peningkatan vs pemeliharaan); susut semua kecuali tanah & KDP (BAB VIII) | Keberadaan, hak, penilaian | Tak ditemukan fisik; belum disusutkan; salah kapitalisasi; belum bersertifikat | Rekon KIB↔Neraca; cek fisik; rekalkulasi penyusutan; uji kapitalisasi; legalitas | Aset tak ditemukan; belanja modal salah klasifikasi; aset belum sertifikat |
| **KDP** | PSAP 08; dipindah ke aset definitif saat **selesai & siap pakai** (BAB VIII) | Keberadaan, penilaian | KDP mangkrak; tak direklasifikasi saat selesai | Reviu kontrak & progres fisik; uji reklasifikasi | KDP mangkrak; aset selesai masih di KDP |
| **Kewajiban (jk pendek/panjang)** | PSAP 09; nominal; **utang PFK = penerimaan − pengeluaran PFK**; refinancing/covenant (BAB IX) | **Kelengkapan**, penilaian | Utang tak tercatat; **PFK belum disetor**; salah klasifikasi jk pendek/panjang | **Search for unrecorded liabilities**; uji PFK; cut-off; konfirmasi kreditur | Utang belanja tak diakui; PFK dipungut tak disetor |
| **Pendapatan-LRA & LO** | PSAP 02/IPSAP 02; **azas bruto**; LRA=kas, LO=akrual/hak (BAB VI) | **Kelengkapan**, cut-off | Pendapatan kurang catat (neto, tak disetor); salah pisah LRA/LO; hibah in-kind tak dicatat | Tracing penerimaan (karcis/SKR/STS)→kas→LRA; uji azas bruto; cut-off; rekon transfer | Pungutan dicatat neto; pendapatan tak disetor; hibah barang tak dicatat |
| **Belanja & beban** | PSAP; belanja=kas/RKU, beban=akrual (kewajiban/konsumsi/penurunan manfaat) (BAB VII) | Keterjadian, akurasi, klasifikasi | Belanja fiktif/mark-up; kekurangan volume; salah klasifikasi modal/barang; perjadin ganda | Vouching SP2D/BAST/kontrak; cek fisik; uji denda; cut-off; uji klasifikasi | Kekurangan volume; kelebihan bayar; belanja modal jadi barang |
| **Ekuitas & koreksi** | PSAP 10; koreksi setelah otorisasi via **Ekuitas**; retroaktif/prospektif (BAB XI); artikulasi LO→LPE→Neraca (BAB III) | Penyajian | Koreksi salah jalur; restatement tak diungkap; mutasi ekuitas tak dijelaskan | Uji mutasi LPE; rekon artikulasi; uji ikhtisar koreksi | Koreksi tak via ekuitas; restatement tak diungkap di CaLK |

## Alat rekonsiliasi turunan (BAB III & V)
- **Artikulasi**: SiLPA(LRA)→LP-SAL; S/D-LO→LPE→Ekuitas Neraca; tak nyambung =
  salah saji/kesalahan konsolidasi.
- **Konversi LRA→LO** (beban pegawai/persediaan/penyusutan/penyisihan) = uji
  roll-forward; selisih tak terjelaskan = indikasi salah saji.
- **Resiprokal RK-PPKD ↔ RK-SKPD** & **DDEL/DKEL** harus saling hapus saat
  konsolidasi.

## Dari jembatan ke KKP (langkah)
1. Tetapkan akun & asersi (dari matriks) → tujuan KKP.
2. Kutip **kriteria SAP** spesifik (pasal/PSAP) sebagai dasar uji.
3. Jalankan **prosedur kunci**; kumpulkan bukti cukup-tepat; beri tickmark.
4. Bandingkan kondisi vs kriteria → bila menyimpang, kembangkan **temuan 5
   atribut** (`07-temuan-dan-lhp.md`, template `temuan-pemeriksaan.md`).
5. Simpulkan & cross-reference ke P2/temuan.
