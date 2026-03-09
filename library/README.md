# Library Guide

Folder `library/` adalah sub-rak utama yang menampung semua seri buku.

## Struktur Governance (Bertingkat)

- Level root repo: konteks umum repository.
- Level `library/`: aturan global lintas seri.
- Level `library/<series>/`: aturan seri-spesifik.
- Level `library/<series>/<book-or-level>/`: panduan kerja level buku.

## Dokumen Aturan di Level Library

- Struktur dan aturan global: `library/dok/rules.md`
- Alur kontribusi lintas seri: `library/dok/contributing.md`
- Format konten dasar (default): `library/dok/style-guide.md`

## Seri yang Sudah Ada

- `library/minna-no-nihongo/`
- `library/irodori/`
- `library/shared/`

## Prinsip Konflik Aturan

Aturan level bawah boleh memperketat aturan level atas, tetapi tidak boleh bertentangan.
