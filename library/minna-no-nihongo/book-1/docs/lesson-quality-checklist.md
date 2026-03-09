# Lesson Quality Checklist book-1

Checklist ini dipakai untuk review setiap lesson di `book-1`.

## 1. Struktur File (required)

- Folder lesson menggunakan pola `lessons/<nn>-<slug-bab>/`.
- File wajib tersedia: `README.md`, `vocab.md`, `grammar.md`, `drills.md`, `kaiwa.md`, `notes.md`.
- Folder media wajib tersedia: `media/audio/`, `media/images/`.
- Jika memakai aset eksternal, isi `media/source-attribution.md`.

## 2. README Lesson (required)

- Ada `Tujuan`, `Cakupan Materi`, dan `Hasil Belajar`.
- Grammar yang disebut di README konsisten dengan isi `grammar.md`.
- Ada status media yang jelas (minimal pointer ke folder audio/images).

## 3. Vocab (required)

- Kosakata yang dicantumkan dipakai di lesson ini.
- Tabel minimal berisi bentuk Jepang, romaji, arti.
- Tidak mencampur terlalu banyak kosakata di luar scope lesson.

## 4. Grammar (required)

- Setiap pola berisi: pola kalimat, arti/makna, dan contoh.
- Contoh minimal memuat Jepang, romaji, dan terjemahan Indonesia.
- Catatan penting partikel/nuansa ditulis jika berpotensi membingungkan pemula.

## 5. Drills (required)

- Ada variasi latihan (melengkapi, transformasi, atau produksi kalimat).
- Instruksi latihan jelas.
- Ada kunci jawaban self-check atau contoh jawaban.

## 6. Kaiwa (required)

- Dialog relevan dengan grammar dan vocab lesson.
- Setiap baris dialog memiliki Jepang, romaji, dan terjemahan.
- Alur percakapan natural untuk konteks pemula.

## 7. Notes (required)

- Berisi poin penguatan grammar/usage yang sering keliru.
- Menautkan referensi shared bila relevan.
- Memiliki log revisi internal lesson (tanggal + ringkasan).

## 8. Konsistensi Bahasa (required)

- Istilah dan romanisasi konsisten dengan style guide repo.
- Tidak ada konflik format `desu/dewa arimasen/desu ka` dalam lesson yang sama.
- Link internal markdown valid.

## Definition of Done

Lesson dinyatakan siap jika semua item `required` terpenuhi tanpa pengecualian.
