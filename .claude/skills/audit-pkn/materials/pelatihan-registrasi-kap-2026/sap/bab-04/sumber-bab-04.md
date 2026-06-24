# SUMBER MENTAH — BAB IV (verbatim/terstruktur)

> Arsip untuk provenance. Versi terstruktur ada di
> `references/materi/sap/bab-04-bagan-akun-standar.md`.
>
> - **Sumber**: Modul SAP, Pelatihan Registrasi KAP 2026 (BDPKN Medan). Bagian:
>   **BAB IV — Bagan Akun Standar (BAS)**.
> - **Cara perolehan**: copy-paste manual (multi-batch) + gambar (struktur kode
>   6 level, tabel banding Permendagri 64 vs 90, contoh kode akun).
> - **Tanggal ingest**: 2026-06-24.

---

## Teks (verbatim/terstruktur)

Tujuan pembelajaran: mampu menguraikan Bagan Akun Standar (BAS).
Indikator: menguraikan gambaran umum BAS; memerinci BAS Pemerintah Pusat; menelaah BAS Pemerintah Daerah.

A. GAMBARAN UMUM BAS
BAS / chart of account (COA) = daftar kodefikasi & klasifikasi transaksi keuangan, pedoman dalam perencanaan, penganggaran, pelaksanaan anggaran, & pelaporan. Digunakan dalam sistem terintegrasi (klasifikasi/kode sama di setiap tahap siklus keuangan negara). Fungsi: pedoman pencatatan; pusat aliran data; alat pengendalian disiplin fiskal & struktur pelaporan; dukung pengambilan keputusan. Single framework BAS memfasilitasi klasifikasi pengguna. BAS memuat akun pelaporan (aset, kewajiban, modal, pendapatan, belanja, pembiayaan) + klasifikasi perencanaan/penganggaran (organisasi, tempat pembayaran, lokasi, program, kegiatan, output). Akun disusun berpedoman PP 71/2010.

B. BAS PEMERINTAH PUSAT
Diatur **PMK No. 214/PMK.05/2013** (31 Des 2013) tentang BAS. Pemutakhiran via Keputusan Dirjen Perbendaharaan, terakhir 2022: **Kep-291/PB/2022** (perubahan atas Kep-331/PB/2021) tentang Kodefikasi Segmen Akun pada BAS. Perubahan Lampiran I–VI (pemutakhiran segmen akun kas & akrual, penambahan/perubahan/penonaktifan segmen akun).
Struktur BAS = **12 segmen** (Tabel IV.1):
| No | Segmen | Digit | Atribut Pelaporan |
|---|---|---|---|
| 1 | Satker | 6 | BA, Eselon 1, Konsolidasi, Satker |
| 2 | KPPN | 3 | Kode Kanwil Ditjen Perbendaharaan |
| 3 | Akun | 6 | (Kode Akun) [sumber tertulis "Kode Satker" — typo] |
| 4 | Program | 7 (3+2+2) | Kode BA, Eselon I, Program |
| 5 | Output | 7 (4+3) | Kegiatan, Fungsi, Subfungsi, Satuan |
| 6 | Dana | 10 (1+1+8) | No Register |
| 7 | Bank | 5 (1+4) | Kode KPPN |
| 8 | Kewenangan | 1 | — |
| 9 | Lokasi | 4 (2+2) | Provinsi, Kab/Kota |
| 10 | Anggaran | 1 | — |
| 11 | Antar Entitas | 6 | — |
| 12 | Cadangan | 6 | Belum digunakan |

Rincian 12 segmen:
1. **Satker** (6 digit): unit penanggung jawab pencatatan; pola satu kode Satker ↔ satu BA & satu Eselon 1; menghasilkan LK level satker, wilayah, eselon I, K/L. Atribut: BA (3), Eselon 1 (2), Konsolidasian Satker.
2. **KPPN** (3 digit): tempat pemrosesan pembayaran (Ditjen Perbendaharaan); menghasilkan LAK per KPPN & laporan gabungan satker; ada link Kanwil–KPPN. Kanwil DJPBN 3 digit (WXX).
3. **Akun** (6 digit / klasifikasi ekonomi). Kelompok akun: **APBN** (estimasi pendapatan, apropriasi belanja/transfer, estimasi penerimaan pembiayaan, apropriasi pengeluaran pembiayaan); **DIPA** (estimasi pendapatan dialokasikan, alotmen belanja/transfer/pengeluaran pembiayaan); **Komitmen** (komitmen belanja pegawai/barang/modal/bunga/subsidi/hibah/bansos/lain-lain/transfer); **Realisasi** (pendapatan-LO, pendapatan-LRA, beban, belanja, beban transfer, transfer, penerimaan/pengeluaran pembiayaan); **Transitoris** (penerimaan & pengeluaran non anggaran); **Neraca** (aset, kewajiban, ekuitas).
   Kodefikasi akun (digit awal): **1=Aset, 2=Kewajiban, 3=Ekuitas; 4=Pendapatan (LRA & LO); 5 & 6=Belanja/Transfer & Beban; 49 & 59=pendapatan-LO & beban yang tak ada di basis kas (beban penyusutan, amortisasi, penyisihan piutang tidak tertagih); 7=Pembiayaan; 8=transaksi transitoris.** Akun sama dipakai untuk APBN/DIPA/Komitmen/Realisasi (dibedakan segmen Tipe Anggaran).
   Pedoman akun belanja (LRA): Belanja Pegawai (kompensasi pegawai, kecuali pembentukan modal); Belanja Barang (barang/jasa habis pakai, pemeliharaan, perjalanan dinas, barang BLU, barang untuk diserahkan ke masyarakat); Belanja Modal (peroleh/tambah aset tetap/lainnya, manfaat >12 bln, melebihi batas kapitalisasi); Belanja Bunga Utang; Belanja Subsidi; Belanja Hibah (transfer uang/barang/jasa via naskah perjanjian); Belanja Bantuan Sosial (lindungi dari risiko sosial); Belanja Lain-lain (tak terklasifikasi, tidak biasa & tidak berulang).
4. **Program** (7 digit = BA 3 + Eselon I 2 + Program 2): penjabaran kebijakan K/L; sasaran & kinerja jelas-terukur; gambaran tiap unit Eselon I.
5. **Output** (7 digit = kegiatan 4 + output 3): atribut fungsi, subfungsi, prioritas, satuan volume.
6. **Dana** (10 digit = sumber dana 1 + cara penarikan 1 + no register 8). Sumber dana: RM, PLN, RMP, PNBP, PDN, BLU, Stimulus, Hibah (DN/LN ke RKUN), Hibah Langsung Uang/Barang/Jasa, Hibah Langsung Surat Berharga, Luncuran (LCR), Saldo Awal BLU (SBLU), SBSN. Cara penarikan: RM, Pembiayaan Pendahuluan (PP), Pembayaran Langsung (PL), Rekening Khusus (RK), Letter of Credit (LC).
7. **Bank** (5 digit = tipe rekening 1 + no urut 4): rekening Kuasa BUN. 3 tipe rekening BUN: rekening di BI/Bank Umum/Pos; rekening pengesahan (dummy); rekening transito (dummy).
8. **Kewenangan** (1 digit): Kantor Pusat (KP); Kantor Daerah (KD); Dekonsentrasi; Tugas Perbantuan; Desentralisasi; Urusan Bersama.
9. **Lokasi** (4 digit = provinsi 2 + kab/kota 2): tempat kegiatan/penerima dana; pengendalian DBH. Kode penerima dana: D=BUMD, L=lainnya (bank & non-bank), N=BUMN, K=pemkab/pemkot, R=pemprov, P=daerah penerima bagi hasil PBB.
10. **Anggaran** (1 digit): tahapan transaksi (APBN, DIPA, Realisasi, Pengembalian Realisasi, Penyesuaian Akrual). LKPP banding realisasi vs APBN; LK K/L banding realisasi vs DIPA.
11. **Antar Entitas** (6 digit): Ditagihkan Kepada Entitas Lain (Due to) & Diterima Dari Entitas Lain (Due From); lawan kode satker untuk transaksi antar entitas.
12. **Cadangan** (6 digit): belum digunakan; disediakan untuk pengembangan BAS.

C. BAS PEMERINTAH DAERAH
Pedoman perencanaan, pelaksanaan, pertanggungjawaban, pelaporan keuangan daerah. Dasar: **Permendagri No. 90 Tahun 2019** (Klasifikasi, Kodefikasi, dan Nomenklatur Perencanaan Pembangunan dan Keuangan Daerah). BAS khusus pemda diatur **Permendagri No. 19 Tahun 2020** sebagai pengganti Lampiran III **Permendagri No. 64 Tahun 2013**.
BAS digunakan dalam: pencatatan jurnal, klasifikasi buku besar, ikhtisar neraca saldo, penyajian LK. Rincian **6 level**: Level 1 = akun; 2 = kelompok; 3 = jenis; 4 = obyek; 5 = rincian obyek; 6 = sub rincian obyek. (Format kode: Akun.Kelompok.Jenis.Objek.Rincian Objek.Sub Rincian Objek + Uraian Akun.)
Level 1 (kode akun) terdiri: Aset; Kewajiban; Ekuitas; Pendapatan Daerah; Belanja Daerah; Pembiayaan Daerah; Pendapatan Daerah [tertulis 2×; satu = Pendapatan-LO]; Beban Daerah.

### Perbandingan Permendagri 64 vs Permendagri 90 (dari gambar)

**Neraca (Level 1) — SAMA:**
1.1 Aset Lancar; 1.2 Investasi Jangka Panjang; 1.3 Aset Tetap; 1.4 Dana Cadangan; 1.5 Aset Lainnya; 2.1 Kewajiban Jangka Pendek; 2.2 Kewajiban Jangka Panjang; 3.1 Ekuitas. (Identik di 64 & 90.)

**Pendapatan/Belanja/Transfer/Pembiayaan — ada PERBEDAAN:**
| Permendagri 64 | Permendagri 90 |
|---|---|
| 4.1 PAD; 4.2 Pendapatan Transfer; 4.3 Lain-lain Pendapatan Daerah yang Sah | 4.1; 4.2; 4.3 (SAMA) |
| 5.1 Belanja Operasi; 5.2 Belanja Modal; 5.3 Belanja Tak Terduga | 5.1; 5.2; 5.3 Belanja Tidak Terduga (SAMA) |
| **6.1 Transfer Bagi Hasil Pendapatan; 6.2 Transfer Bantuan Keuangan** | **5.4 Belanja Transfer** (Transfer jadi bagian Belanja) |
| 7.1 Penerimaan Pembiayaan; 7.2 Pengeluaran Pembiayaan | **6.1 Penerimaan Pembiayaan; 6.2 Pengeluaran Pembiayaan** |

**LO (Pendapatan-LO & Beban) — ada PERBEDAAN:**
| Permendagri 64 | Permendagri 90 |
|---|---|
| 8.1 PAD-LO; 8.2 Pendapatan Transfer-LO; 8.3 Lain-lain Pendapatan Daerah yang Sah-LO; 8.4 Surplus Non Operasional-LO; **8.5 Pendapatan Luar Biasa-LO** | 7.1; 7.2; 7.3; 7.4 (tanpa Pendapatan Luar Biasa-LO) |
| 9.1 Beban Operasi-LO; 9.2 Beban Transfer; 9.3 Defisit Non Operasional; 9.4 Beban Luar Biasa | 8.1 Beban Operasi-LO; **8.2 Beban Penyusutan dan Amortisasi**; 8.3 Beban Transfer; 8.4 Beban Tak Terduga; 8.5 Defisit Non Operasional |

### Contoh kode akun (6 level)
- `1.1.01.01.01.001` Kas di Kas Daerah (menampung seluruh penerimaan & pengeluaran daerah).
- `1.1.01.02 / .01 / .001` Kas di Bendahara Penerimaan (kas di bawah tanggung jawab bendahara penerimaan, dari PAD pada SKPD).
- `1.5.03.04.01.004` Hak Paten (aset tak berwujud — hak eksklusif inventor).
- `2.1.01.05.02.001` Utang PPh 22 (utang pemerintah sebagai pemotong/pemungut PPh 22).
- `4.1.02.01.01.001` Retribusi Pelayanan Kesehatan di Puskesmas.
- `5.1.01.04.12.004` Belanja Tunjangan Perumahan DPRD.
- `6.1.01.01.01.001` Pelampauan Penerimaan PAD-Pajak Kendaraan Bermotor (PKB).
- `7.1.01.06.01.001` Pajak Hotel-LO.
- `8.1.01.01.01.001` Beban Gaji Pokok PNS.
- (Contoh akun piutang pusat: `115113` Piutang PPh Panas Bumi; `115129` Piutang PPh Non Migas Lainnya; `115154` Piutang PBB Perhutanan; `115173` Piutang Bunga/Denda Penagihan PPh.)

Untuk BAS lebih rinci: Permendagri No. 90 Tahun 2019.

LATIHAN:
1. Uraikan bagaimana perubahan/pemutakhiran pada BAS dapat terjadi.
2. Apa perbedaan segmen BAS pada pemerintah daerah dan pemerintah pusat.
3. Uraikan penggunaan BAS dalam pengelolaan keuangan negara terintegrasi (perencanaan → penganggaran → pelaksanaan → pelaporan).
