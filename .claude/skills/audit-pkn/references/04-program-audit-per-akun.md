# 04 — Program Audit per Akun (Pemeriksaan Keuangan)

Panduan prosedur substantif & uji pengendalian utama per akun LKPD/LKPP.
Untuk tiap akun: **asersi kunci → risiko khas → prosedur → bukti**. Sesuaikan
dengan hasil penilaian risiko (`03-perencanaan-risiko-materialitas.md`) — daftar
ini menu, bukan kewajiban menjalankan semuanya.

Teknik dasar yang dipakai berulang: **vouching** (dari catatan → ke dokumen
sumber, menguji keterjadian), **tracing** (dari dokumen sumber → ke catatan,
menguji kelengkapan), **rekalkulasi**, **konfirmasi**, **observasi/inspeksi
fisik**, **rekonsiliasi**, **prosedur analitis**, **cut-off test**.

---

## 1. Kas & Setara Kas
- **Asersi kunci**: keberadaan, kelengkapan, hak, penilaian (kas valas),
  penyajian (kas BLUD/dana BOS/kas di bendahara).
- **Risiko khas**: saldo kas di bendahara tak disetor, kas fiktif, selisih kas,
  rekening tidak dilaporkan, dana mengendap.
- **Prosedur**:
  - Rekonsiliasi saldo Neraca ↔ rekening koran ↔ BKU bendahara; uji rekonsiliasi
    bank dan pos rekonsiliasi (deposit in transit, outstanding cheque).
  - **Cash opname** (perhitungan kas mendadak) di bendahara pengeluaran/
    penerimaan; bandingkan fisik vs catatan; telusuri selisih.
  - **Konfirmasi bank** atas seluruh rekening (saldo, pemegang, blokir, bunga).
  - Uji **cut-off** penerimaan/pengeluaran akhir tahun.
  - Telusuri sisa UP/TUP/GU yang belum disetor ke kas daerah per 31 Des.

## 2. Piutang (Pajak/Retribusi, Lain-lain PAD)
- **Asersi kunci**: keberadaan, hak, kelengkapan, penilaian (penyisihan).
- **Risiko khas**: piutang tak tertagih tak disisihkan, piutang fiktif/kadaluarsa,
  kurang catat ketetapan.
- **Prosedur**:
  - Uji **umur piutang** (*aging*) & kebijakan **penyisihan piutang tidak
    tertagih**; rekalkulasi sesuai kebijakan akuntansi entitas.
  - **Konfirmasi** ke wajib pajak/penyewa utama atau uji ke SKP/SKR & bukti
    bayar (vouching/tracing).
  - Uji kelengkapan: telusuri ketetapan (SKPD/SKRD) ke pencatatan piutang.
  - Reviu penghapusan piutang — dasar hukum & otorisasi.

## 3. Persediaan
- **Asersi kunci**: keberadaan, kelengkapan, penilaian.
- **Risiko khas**: stok opname tidak dilakukan, persediaan usang, beda metode
  penilaian, persediaan unit layanan (obat, ATK, barang pakai habis) tak tercatat.
- **Prosedur**:
  - Hadiri/uji **stock opname** akhir tahun; uji sampel hitung fisik dua arah.
  - Uji **penilaian** (harga perolehan/harga terakhir/FIFO sesuai kebijakan).
  - Uji **cut-off** penerimaan & pengeluaran barang.
  - Identifikasi persediaan rusak/usang/kadaluarsa → dampak penyajian.

## 4. Aset Tetap (akun berisiko tinggi & sering jadi temuan)
- **Asersi kunci**: keberadaan, hak, kelengkapan, penilaian (kapitalisasi &
  penyusutan), penyajian.
- **Risiko khas**: aset tak ditemukan fisiknya, double-record, belum disusutkan,
  konstruksi dalam pengerjaan (KDP) macet, aset belum bersertifikat,
  kapitalisasi belanja keliru (belanja modal vs barang/jasa), hibah/mutasi tak
  tercatat, aset dikuasai pihak lain.
- **Prosedur**:
  - Rekonsiliasi **KIB / SIMDA-BMD ↔ Neraca**; uji mutasi tambah/kurang.
  - **Cek fisik** sampel aset (cocokkan nomor inventaris, kondisi, lokasi,
    penguasaan); telusuri aset di Neraca → fisik (keberadaan) & fisik → catatan
    (kelengkapan).
  - Uji **kapitalisasi**: pisahkan belanja modal yang menambah masa manfaat vs
    pemeliharaan; cek thresholds kapitalisasi entitas.
  - Rekalkulasi **penyusutan** (metode, masa manfaat, akumulasi).
  - Reviu **KDP**: dokumen kontrak, progres fisik, mangkrak, reklasifikasi ke
    aset definitif saat selesai.
  - Uji legalitas: sertifikat tanah, bukti kepemilikan kendaraan; aset
    sengketa/dikuasai pihak ketiga.

## 5. Pendapatan (PAD, Transfer, Lain-lain Pendapatan yang Sah)
- **Asersi kunci**: keterjadian, kelengkapan, akurasi, cut-off, klasifikasi.
- **Risiko khas**: pendapatan kurang catat (kelengkapan = risiko utama),
  pungutan tak disetor, salah klasifikasi LRA vs LO (akrual), pengakuan
  pendapatan transfer/DAK keliru.
- **Prosedur**:
  - Prosedur analitis: bandingkan realisasi vs target & tren tahun lalu; selidiki
    deviasi signifikan.
  - **Tracing** penerimaan dari dokumen sumber (karcis/SKR/STS) → kas → LRA untuk
    menguji **kelengkapan**.
  - Rekonsiliasi pendapatan transfer dengan dokumen pusat (DAU/DAK/DBH).
  - Uji **cut-off** & pisah pengakuan **LRA (basis kas)** vs **LO (akrual)**.
  - Reviu pengelolaan retribusi/pajak daerah (penetapan, penagihan, penyetoran).

## 6. Belanja (Operasi, Modal, Tak Terduga) — termasuk pengadaan
- **Asersi kunci**: keterjadian, akurasi, kelengkapan, cut-off, klasifikasi.
- **Risiko khas**: belanja fiktif/mark-up, kekurangan volume pekerjaan,
  keterlambatan tanpa denda, pemecahan paket, perjalanan dinas fiktif/ganda,
  salah klasifikasi (modal vs barang/jasa), kelebihan bayar.
- **Prosedur**:
  - **Vouching** sampel belanja ke SPP/SPM/SP2D, kontrak, BAST, faktur, bukti
    bayar pajak (PPN/PPh).
  - Uji **pengadaan barang/jasa**: kepatuhan proses (Perpres pengadaan),
    kewajaran HPS, kesesuaian spesifikasi & volume, **cek fisik** hasil pekerjaan,
    perhitungan **denda keterlambatan**.
  - Uji **perjalanan dinas**: kesesuaian SPD, bukti riil, *at cost*, kemungkinan
    ganda/fiktif (rekonsiliasi tiket/hotel).
  - Uji **cut-off** & utang belanja akhir tahun (akrual beban vs realisasi LRA).
  - Uji potongan & setoran **pajak** atas belanja.

## 7. Belanja Bantuan Sosial (Bansos) & Hibah
- **Risiko khas**: penerima tak memenuhi syarat/fiktif, tanpa proposal/LPJ,
  tidak tepat sasaran, penyaluran ganda.
- **Prosedur**: uji kelengkapan dokumen (proposal, NPHD, LPJ), verifikasi
  eksistensi penerima (sampel), kesesuaian dengan keputusan kepala daerah,
  rekonsiliasi daftar penerima.

## 8. Kewajiban / Utang
- **Asersi kunci**: kelengkapan (risiko utama — *understatement*), keberadaan,
  penilaian.
- **Prosedur**: cari **utang tak tercatat** (*search for unrecorded
  liabilities*) — periksa pembayaran setelah tanggal Neraca, faktur belum
  dibayar, BAST akhir tahun; konfirmasi ke kreditur; uji utang PFK/perhitungan
  pihak ketiga (pajak/iuran yang belum disetor).

## 9. Ekuitas & Pembiayaan
- **Prosedur**: uji mutasi ekuitas (LPE) dapat dijelaskan (koreksi, surplus/
  defisit LO, dampak akrual); rekonsiliasi SiLPA/SAL (LRA ↔ LP-SAL ↔ LAK ↔
  Neraca); uji penyertaan modal & investasi (metode ekuitas/biaya).

## 10. Pengungkapan & CaLK
- Uji **kecukupan pengungkapan**: kebijakan akuntansi, rincian pos signifikan,
  kejadian setelah tanggal pelaporan, kontinjensi, pihak berelasi, informasi
  yang diharuskan SAP.
- Konsistensi angka CaLK ↔ muka laporan.

---

## Pemetaan prosedur ↔ asersi (ringkas)

| Asersi | Prosedur paling kuat |
|---|---|
| Keberadaan/Keterjadian | Inspeksi fisik, konfirmasi, vouching ke dokumen sumber |
| Kelengkapan | Tracing dari sumber → catatan, *search for unrecorded*, analitis |
| Hak & Kewajiban | Inspeksi dokumen kepemilikan/kontrak, konfirmasi |
| Penilaian & Alokasi | Rekalkulasi, uji estimasi/penyisihan/penyusutan |
| Penyajian & Pengungkapan | Reviu CaLK vs SAP, uji klasifikasi |

## Kecukupan & ketepatan bukti

- **Cukup** = kuantitas memadai (dipengaruhi risiko & kualitas bukti).
- **Tepat** = relevan + andal. Keandalan naik bila: dari sumber independen,
  SPI efektif, diperoleh langsung pemeriksa, berbentuk dokumen/elektronik asli.
- Setiap prosedur & simpulannya **wajib** didokumentasikan di KKP dengan
  *tickmark* yang dijelaskan.
