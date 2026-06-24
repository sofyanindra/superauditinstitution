# 03 — Perencanaan, Penilaian Risiko & Materialitas

## A. Pemahaman entitas & lingkungannya

Kumpulkan & dokumentasikan pemahaman atas:
- **Mandat & struktur**: tusi entitas, struktur organisasi, SOTK, pengguna
  anggaran/kuasa pengguna anggaran (PA/KPA), bendahara.
- **Lingkungan regulasi**: UU/PP/Permendagri/Perkada yang mengikat; kebijakan
  akuntansi entitas; perubahan regulasi tahun berjalan.
- **Anggaran & realisasi**: APBD/APBN, DPA, perubahan anggaran, pagu vs
  realisasi; pos-pos signifikan & tidak biasa.
- **Proses bisnis & siklus utama**: pendapatan (pajak/retribusi/transfer),
  belanja (operasi, modal, bansos, hibah), kas, persediaan, aset tetap, utang,
  pembiayaan.
- **Sistem informasi/IT**: aplikasi keuangan (mis. SIPD), pengendalian umum &
  aplikasi, jejak audit elektronik.
- **Hasil pemeriksaan sebelumnya & TLRHP**: temuan berulang = sinyal risiko.

## B. Sistem Pengendalian Intern (SPI) — kerangka & penilaian

Gunakan **5 unsur SPI** (selaras COSO / PP 60/2008 tentang SPIP):
1. **Lingkungan pengendalian** (integritas, struktur, komitmen kompetensi).
2. **Penilaian risiko** oleh manajemen.
3. **Kegiatan pengendalian** (otorisasi, pemisahan tugas, rekonsiliasi,
   pengendalian fisik aset, reviu kinerja).
4. **Informasi & komunikasi**.
5. **Pemantauan** pengendalian intern.

Langkah:
- Pahami desain pengendalian relevan per siklus → uji **implementasi**
  (*walkthrough*) → bila akan diandalkan, lakukan **uji pengendalian**.
- Simpulkan **risiko pengendalian** (rendah/sedang/tinggi) per asersi/akun.
- **Defisiensi** pengendalian → bahan **LHP SPI** (lihat `07-temuan-dan-lhp.md`).

## C. Model risiko pemeriksaan

**Risiko Pemeriksaan (AR) = Risiko Inheren (IR) × Risiko Pengendalian (CR) ×
Risiko Deteksi (DR).**

- **IR** — kerentanan bawaan asersi terhadap salah saji (kompleksitas, estimasi,
  volume, kerentanan fraud).
- **CR** — risiko SPI tidak mencegah/mendeteksi salah saji.
- **DR** — risiko prosedur pemeriksa gagal mendeteksi salah saji yang ada.
- **RMM (Risk of Material Misstatement) = IR × CR.** Pemeriksa menetapkan AR
  rendah lalu **menyetel DR**: makin tinggi RMM → DR harus diturunkan → prosedur
  substantif diperluas/diperdalam & diarahkan ke akhir periode.

### Risiko kecurangan (fraud)
- Pertimbangkan **fraud triangle**: tekanan, peluang, rasionalisasi.
- Area rawan di sektor publik: pengadaan barang/jasa, perjalanan dinas, bansos/
  hibah, belanja fiktif/mark-up, pungutan, aset "hilang".
- Terapkan **unpredictability** (prosedur yang tidak terduga) & skeptisisme.

## D. Materialitas

Tetapkan & dokumentasikan tiga lapis materialitas:

| Jenis | Fungsi | Catatan |
|---|---|---|
| **Materialitas perencanaan (overall)** | Batas salah saji yang memengaruhi keputusan pengguna LK. | Ditetapkan atas LK secara keseluruhan. |
| **Materialitas pelaksanaan (*performance materiality*)** | Lebih rendah dari overall untuk mengantisipasi akumulasi salah saji tak terdeteksi. | Mis. 50–75% dari overall (sesuaikan risiko). |
| **Ambang salah saji sepele (*clearly trivial*)** | Di bawahnya, salah saji tidak perlu diakumulasi. | Mis. 5% dari materialitas perencanaan. |

**Pemilihan tolok ukur (benchmark)** disesuaikan karakter entitas pemerintah,
mis.: **total belanja/beban**, **total pendapatan**, atau **total aset**.
Pemerintahan berorientasi anggaran → tolok ukur berbasis **belanja** sering
relevan. Pilih persentase berdasarkan judgment & risiko, lalu dokumentasikan
rasionalnya.

> Pertimbangkan pula materialitas **kualitatif**: salah saji kecil nominal namun
> material karena sifatnya (mis. transaksi dengan pihak terkait, pelanggaran
> hukum, menutup kerugian menjadi laba, menyembunyikan ketidakpatuhan).

## E. Strategi & Program Pemeriksaan (P2)

- **Strategi pemeriksaan**: pendekatan keseluruhan (lingkup, saat, arah, sumber
  daya, pemanfaatan pekerjaan APIP/ahli).
- **Program Pemeriksaan (P2)**: penjabaran prosedur per akun/siklus —
  tujuan, asersi yang diuji, langkah kerja, pelaksana, waktu, referensi KKP.
- **PKP (Program Kerja Perorangan)**: pembagian P2 ke tiap anggota tim.
- Hubungkan **risiko & asersi → prosedur**: makin tinggi RMM suatu asersi,
  makin kuat prosedur yang dirancang.
- Gunakan template `templates/program-pemeriksaan-P2.md`.

## F. Asersi manajemen (acuan merancang prosedur)

Untuk **transaksi/peristiwa**: keterjadian (*occurrence*), kelengkapan,
akurasi, pisah batas (*cut-off*), klasifikasi.
Untuk **saldo akun**: keberadaan (*existence*), hak & kewajiban, kelengkapan,
penilaian & alokasi.
Untuk **penyajian & pengungkapan**: keterjadian/hak-kewajiban, kelengkapan,
klasifikasi & keterpahaman, akurasi & penilaian.

> Setiap langkah prosedur dalam P2 sebaiknya dipetakan ke asersi yang ditujunya
> agar lingkup pengujian lengkap & tidak berlebihan.

## Checklist perencanaan

- [ ] Pemahaman entitas & siklus signifikan terdokumentasi.
- [ ] SPI dipahami; risiko pengendalian disimpulkan per akun/asersi.
- [ ] RMM (termasuk risiko fraud) dinilai & dipetakan.
- [ ] Materialitas (overall, pelaksanaan, trivial) ditetapkan + rasional.
- [ ] P2/PKP disusun, prosedur dipetakan ke risiko/asersi, & disetujui.
