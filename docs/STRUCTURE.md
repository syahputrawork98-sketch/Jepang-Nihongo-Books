# Repository Structure

Struktur utama repository:

```text
<repo-root>/
|-- docs/
|-- materials/
|   |-- shared/
|   |   |-- writing-system/
|   |   |   |-- hiragana.md
|   |   |   |-- katakana.md
|   |   |   `-- kanji/
|   |   |       |-- README.md
|   |   |       |-- kanji-basics.md
|   |   |       |-- 00-overview.md
|   |   |       |-- 01-konsep-onyomi-kunyomi.md
|   |   |       |-- 02-kanji-tema-harian.md
|   |   |       |-- 03-kanji-tema-sekolah.md
|   |   |       |-- 04-sejarah-singkat-kanji.md
|   |   |       |-- 05-aturan-goresan-dasar.md
|   |   |       `-- 99-ringkasan.md
|   |   |-- kata-sifat/
|   |   |   |-- README.md
|   |   |   |-- 00-overview.md
|   |   |   |-- 01-kata-sifat-i.md
|   |   |   |-- 02-kata-sifat-na.md
|   |   |   |-- 03-pola-kalimat-dasar.md
|   |   |   |-- 04-daftar-kata-sifat-umum.md
|   |   |   |-- 05-lawan-kata.md
|   |   |   |-- daftar-tematik/
|   |   |   |   |-- 01-cuaca-dan-suhu.md
|   |   |   |   |-- 02-rasa-dan-makanan.md
|   |   |   |   |-- 03-ukuran-dan-sifat-benda.md
|   |   |   |   `-- 04-kepribadian-dan-kondisi.md
|   |   |   `-- 99-ringkasan.md
|   |   |-- numbers/
|   |   |   `-- angka.md
|   |   |-- hari-dan-tanggal/
|   |   |   `-- hari-dan-tanggal.md
|   |   |-- months/
|   |   |   |-- README.md
|   |   |   |-- 00-overview.md
|   |   |   |-- 01-dasar.md
|   |   |   |-- 02-detail-penggunaan.md
|   |   |   |-- 03-kanji-per-bulan.md
|   |   |   |-- 04-latar-belakang-sejarah.md
|   |   |   `-- 99-ringkasan.md
|   |   |-- K3-APD/
|   |   |   |-- README.md
|   |   |   |-- 00-overview.md
|   |   |   |-- 01-dasar-k3.md
|   |   |   |-- 02-jenis-apd.md
|   |   |   |-- 03-cara-pakai-dan-inspeksi-apd.md
|   |   |   |-- 04-kosakata-jepang-k3-apd.md
|   |   |   `-- 99-ringkasan.md
|   |   |-- hobi/
|   |   |   |-- README.md
|   |   |   |-- 00-overview.md
|   |   |   |-- 01-kosakata-hobi-dasar.md
|   |   |   |-- 02-pola-kalimat-hobi.md
|   |   |   |-- 03-kaiwa-topik-hobi.md
|   |   |   `-- 99-ringkasan.md
|   |   `-- uang/
|   |       `-- uang.md
|   |-- minna-no-nihongo/
|   |   |-- RULES.md
|   |   |-- CHANGELOG.md
|   |   |-- VERSIONING.md
|   |   |-- RELEASE_CHECKLIST.md
|   |   |-- book-1/
|   |   |   `-- CHANGELOG.md
|   |   |-- book-2/
|   |   |   `-- CHANGELOG.md
|   |   |-- book-3/
|   |   |   `-- CHANGELOG.md
|   |   |-- book-4/
|   |   |   `-- CHANGELOG.md
|   |   `-- book-5/
|   |       `-- CHANGELOG.md
|   `-- irodori/
|       |-- starter-a1/
|       `-- elementary-a2/
```

## Struktur Konten Tiap Buku/Level

Setiap buku atau level menggunakan pola folder berikut:

```text
<book-or-level>/
|-- 00-front-matter/
|-- lessons/
|   |-- 01/
|   |-- 02/
|   |-- ...
|   `-- nn/
`-- 90-appendix/
```

## Struktur Lesson

Setiap lesson minimal berisi:

```text
<lesson>/
|-- README.md
|-- vocab.md
|-- grammar.md
|-- drills.md
|-- kaiwa.md
|-- notes.md
`-- media/
    |-- audio/
    `-- images/
```

## Catatan

- `shared/` dipakai untuk materi universal yang dipakai lintas seri.
- `Minna no Nihongo` umumnya mengikuti lesson bernomor (mis. 01-25 per buku).
- `Irodori` boleh menyesuaikan unit aslinya, tetapi tetap disimpan dalam format lesson konsisten.
