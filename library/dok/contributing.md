# Contributing Guide

Terima kasih sudah berkontribusi pada repository ini.

Repository ini memuat materi belajar Bahasa Jepang dari beberapa seri.
Saat ini seri utamanya adalah:

- Minna no Nihongo
- Irodori

## Struktur Repository

Materi utama berada di:

```text
materials/
```

Dengan pembagian:

```text
materials/
|-- shared/
|-- minna-no-nihongo/
|   |-- book-1/
|   |-- book-2/
|   |-- book-3/
|   |-- book-4/
|   `-- book-5/
`-- irodori/
    |-- starter-a1/
    `-- elementary-a2/
```

## Struktur Lesson

Setiap lesson harus memiliki file berikut:

- README.md
- vocab.md
- grammar.md
- drills.md
- kaiwa.md
- notes.md

Media diletakkan di:

- media/audio/
- media/images/

## Aturan Penambahan Materi

1. Jangan mengubah pola struktur folder utama.
2. Tambahkan materi ke seri yang sesuai (`minna-no-nihongo` atau `irodori`).
3. Simpan materi dasar yang dipakai lintas seri ke `materials/shared/`.
4. Gunakan format file lesson yang sama untuk semua seri.
5. Simpan audio di `media/audio` dan gambar di `media/images`.
6. Untuk unit Irodori, gunakan nama lesson konsisten (mis. `01`, `02`, dst.) agar mudah diindeks.
7. Jika menambah seri baru, buat folder baru di bawah `materials/` dengan pola struktur yang sama.

## Penamaan File

- Gunakan huruf kecil.
- Gunakan tanda `-` untuk pemisah kata.
- Jangan gunakan spasi.

Contoh:

```text
kata-pengantar.md
cara-penggunaan.md
penjelasan-tambahan.md
```

## Pull Request

Saat membuat Pull Request:

1. Jelaskan seri dan buku/level yang diubah.
2. Jelaskan lesson/unit yang ditambahkan atau direvisi.
3. Jelaskan jenis perubahan (vocab/grammar/drills/kaiwa/notes/media/shared).

## Aturan Khusus Minna no Nihongo

Untuk kontribusi di `materials/minna-no-nihongo/`, gunakan dokumen berikut:

- `RULES.md` untuk aturan konten dan DoD.
- `CHANGELOG.md` (global) untuk perubahan lintas buku.
- `book-x/CHANGELOG.md` untuk perubahan per buku.
- `VERSIONING.md` untuk skema versi rilis.
- `RELEASE_CHECKLIST.md` saat persiapan rilis akhir.


