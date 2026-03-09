# Library Rules

Dokumen ini adalah aturan global untuk seluruh konten di `library/`.

## 1. Scope

- Berlaku untuk semua seri di `library/<series>/`.
- Tidak menggantikan aturan seri-spesifik pada `library/<series>/docs/rules.md`.

## 2. Arsitektur Folder

```text
library/
|-- shared/
|-- <series>/
|   |-- docs/
|   |   `-- rules.md
|   |-- <book-or-level>/
|   |   |-- 00-front-matter/
|   |   |-- lessons/
|   |   |   |-- 01-nama-bab/
|   |   |   `-- nn-nama-bab/
|   |   `-- 90-appendix/
|   `-- ...
`-- ...
```

## 3. Struktur Minimal Lesson

Setiap lesson wajib berisi:

- `README.md`
- `vocab.md`
- `grammar.md`
- `drills.md`
- `kaiwa.md`
- `notes.md`
- `media/audio/`
- `media/images/`

## 4. Aturan Penamaan

- Gunakan huruf kecil.
- Gunakan `-` sebagai pemisah kata.
- Jangan gunakan spasi.
- Folder lesson wajib memakai pola: `<nn>-<slug-bab>` (contoh `01-perkenalan-dasar`).

## 5. Batas Tanggung Jawab

- `library/shared/`: materi lintas seri (hindari duplikasi ke lesson bila tidak perlu).
- `library/<series>/`: aturan dan konten seri-spesifik.
- Root repo: konteks umum saja, bukan aturan detail.

## 6. Aturan Penulisan Konten

Default format penulisan konten mengikuti `library/docs/style-guide.md`.
Setiap seri boleh menambah aturan sendiri di `library/<series>/docs/rules.md`.


