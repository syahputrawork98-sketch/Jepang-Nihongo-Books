# Minna no Nihongo Rules

Dokumen ini mengatur perubahan pada level `library/minna-no-nihongo/`.

## 1. Scope Level Ini

Aturan di dokumen ini hanya untuk:

- struktur seri Minna no Nihongo (`book-1` s.d. `book-5`),
- standar minimum yang wajib dipenuhi semua buku,
- kualitas dasar konten lintas buku,
- logging perubahan level seri.

Status standar saat ini:

- `book-1`: standar struktur lesson final menggunakan pola `lessons/<nn>-<slug-bab>/`.
- `book-2` s.d. `book-5`: sementara masih transisi dan belum wajib mengikuti pola slug final sampai aturan khusus per buku disepakati.

## 2. Batas Tanggung Jawab

- Aturan global lintas seri: `library/docs/rules.md`.
- Aturan level buku dan cara menulis bab: `library/minna-no-nihongo/book-x/docs/writing-guide.md`.
- Dokumen ini tidak menggantikan aturan level buku.

## 3. Struktur Seri

- Buku yang valid: `book-1`, `book-2`, `book-3`, `book-4`, `book-5`.
- Struktur final wajib untuk `book-1`:
  - `00-front-matter/`
  - `lessons/<nn>-<slug-bab>/`
  - `90-appendix/`
  - `docs/`
- Untuk `book-2` s.d. `book-5`, struktur lesson masih boleh menyesuaikan draft aturan buku masing-masing selama tidak merusak konsistensi internal buku tersebut.

## 4. Standar Minimum Lesson

Setiap lesson minimal harus memiliki:

- `README.md`
- `vocab.md`
- `grammar.md`
- `drills.md`
- `kaiwa.md`
- `notes.md`
- `media/audio/`
- `media/images/`

## 5. Standar Kualitas Lintas Buku

- Contoh bahasa menggunakan kombinasi Jepang, romaji, dan Indonesia.
- Grammar minimal memiliki pola kalimat, arti, dan contoh.
- Contoh kalimat harus natural untuk pemula.
- Hindari terjemahan ambigu.
- Konsisten dengan gaya romaji repo.

## 6. Referensi Shared

- Materi universal tidak diduplikasi ke banyak lesson.
- Gunakan `library/shared/...` sebagai sumber lintas seri.

## 7. Penamaan

- Gunakan huruf kecil.
- Gunakan `-` sebagai pemisah kata.
- Jangan gunakan spasi pada nama file/folder.
- Gunakan pola folder lesson: `<nn>-<slug-bab>` (contoh `01-perkenalan-dasar`).

## 8. Logging Perubahan

- Perubahan lintas buku: `library/minna-no-nihongo/CHANGELOG.md`.
- Perubahan per buku: `library/minna-no-nihongo/book-x/CHANGELOG.md`.
- Catatan detail lesson: `library/minna-no-nihongo/book-x/lessons/<nn>-<slug-bab>/notes.md`.

## 9. Definition of Done (Seri)

Sebuah perubahan di seri Minna selesai jika:

- standar minimum lesson terpenuhi,
- link internal valid,
- catatan perubahan tercatat di changelog yang sesuai.

