# Minna no Nihongo Rules

Dokumen ini adalah aturan kerja khusus untuk konten `materials/minna-no-nihongo/`.

## 1. Scope

- Struktur buku:
  - `book-1` sampai `book-5`
- Struktur lesson:
  - `lessons/01`, `lessons/02`, dst (dua digit)

## 2. Struktur Wajib per Lesson

Setiap lesson minimal harus memiliki:

- `README.md`
- `vocab.md`
- `grammar.md`
- `drills.md`
- `kaiwa.md`
- `notes.md`
- `media/audio/`
- `media/images/`

## 3. Format Konten Wajib

- Untuk contoh bahasa, gunakan kombinasi:
  - Teks Jepang
  - Romaji
  - Terjemahan Indonesia
- Bagian grammar minimal memuat:
  - Pola kalimat
  - Arti
  - Minimal 3 contoh kalimat

## 4. Referensi Materi Shared

- Materi universal jangan diduplikasi di lesson.
- Gunakan referensi ke `materials/shared/...` untuk:
  - writing system
  - angka / bulan / hari-tanggal
  - uang
  - kata sifat

## 5. Penamaan

- Gunakan huruf kecil.
- Gunakan `-` sebagai pemisah kata.
- Jangan gunakan spasi pada nama file/folder.
- Gunakan folder lesson dua digit (`01`, `02`, ...).

## 6. Kualitas Konten

- Contoh kalimat harus natural dan mudah dipahami pemula.
- Hindari terjemahan yang ambigu.
- Konsisten dengan gaya romaji yang dipakai di repo.

## 7. Logging Perubahan

- Catat perubahan lintas-buku di:
  - `materials/minna-no-nihongo/CHANGELOG.md`
- Catat perubahan per buku di:
  - `materials/minna-no-nihongo/book-x/CHANGELOG.md`
- Catat catatan detail lesson di:
  - `materials/minna-no-nihongo/book-x/lessons/xx/notes.md`

## 8. Definition of Done (DoD)

Sebuah lesson dianggap selesai jika:

- Semua file wajib terisi.
- Link internal tidak putus.
- Contoh Jepang/Romaji/Indonesia tersedia.
- Ringkasan lesson di `README.md` jelas.
- Perubahan dicatat di changelog yang sesuai.
