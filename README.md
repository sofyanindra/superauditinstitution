# superauditinstitution

Asisten **Pemeriksaan Keuangan Negara** untuk pemeriksa/Partner Kantor Akuntan
Publik (KAP) yang terdaftar / sedang registrasi di Badan Pemeriksa Keuangan
(BPK) RI.

Repo ini berisi **Claude Code Skill** `audit-pkn` yang membantu menjalankan
audit di lingkungan pemeriksaan keuangan pemerintahan Indonesia — mencakup
ketiga jenis pemeriksaan (Keuangan, Kinerja, PDTT) di seluruh siklus
perencanaan → pelaksanaan → pelaporan.

## Apa yang dibantu

- **Perencanaan, risiko & materialitas** — pemahaman entitas, penilaian SPI &
  risiko (termasuk fraud), penetapan materialitas, strategi & Program
  Pemeriksaan (P2).
- **Program/prosedur audit per akun** — kas, piutang, persediaan, aset tetap,
  pendapatan, belanja/pengadaan, bansos & hibah, kewajiban, ekuitas, CaLK.
- **Penyusunan temuan & LHP** — temuan 5 atribut
  (kondisi–kriteria–sebab–akibat–rekomendasi) dan kerangka LHP (LK, SPI,
  Kepatuhan).
- **Penentuan opini & reviu SAP/SPKN** — logika opini WTP/WDP/TW/TMP, empat
  kriteria opini, evaluasi salah saji, reviu kesesuaian SAP (PP 71/2010) &
  kepatuhan SPKN (Peraturan BPK 1/2017).

## Struktur

```
.claude/skills/audit-pkn/
├── SKILL.md                         # entri & navigasi skill
├── references/                      # basis pengetahuan domain
│   ├── 01-dasar-hukum-dan-standar.md
│   ├── 02-jenis-dan-tahapan-pemeriksaan.md
│   ├── 03-perencanaan-risiko-materialitas.md
│   ├── 04-program-audit-per-akun.md
│   ├── 05-pemeriksaan-kinerja.md
│   ├── 06-pdtt.md
│   ├── 07-temuan-dan-lhp.md
│   ├── 08-opini-dan-reviu-sap.md
│   └── 09-glosarium.md
└── templates/                       # dokumen kerja siap isi
    ├── program-pemeriksaan-P2.md
    ├── kertas-kerja-pemeriksaan.md
    ├── temuan-pemeriksaan.md
    └── lhp-keuangan.md
```

## Cara pakai

Skill ini aktif otomatis di Claude Code ketika Anda membahas pemeriksaan
keuangan negara (mis. "bantu susun program pemeriksaan aset tetap LKPD",
"rumuskan temuan kekurangan volume", "opini apa untuk salah saji material tapi
tidak pervasif?"). Anda juga dapat memintanya secara eksplisit.

Contoh permintaan:
- "Susun P2 untuk pemeriksaan belanja modal di Pemkab X."
- "Buat draf temuan SPI untuk pencatatan aset tetap yang tidak tertib."
- "Reviu apakah pengakuan pendapatan ini sesuai SAP akrual."
- "Tentukan opini dari daftar salah saji tak terkoreksi berikut."

## Dasar standar & regulasi (verifikasi ke sumber resmi terkini)

- **SPKN** — Peraturan BPK No. 1 Tahun 2017 (mengacu ISSAI).
- **KAP Terdaftar di BPK** — Peraturan BPK No. 2 Tahun 2024.
- **SAP** — PP No. 71 Tahun 2010 (basis akrual).
- **Paket UU keuangan negara** — UU 17/2003, UU 1/2004, UU 15/2004, UU 15/2006.

## Disclaimer

Skill ini adalah **alat bantu pembelajaran & kerja**, bukan pengganti SPKN,
SAP, peraturan resmi, atau **judgment profesional** pemeriksa. Peraturan dapat
berubah — selalu verifikasi ke sumber resmi (`peraturan.bpk.go.id`,
`jdih.bpk.go.id`, `ksap.org`). Skill tidak menerbitkan opini final maupun
menandatangani LHP. Jaga kerahasiaan data entitas yang diperiksa.
