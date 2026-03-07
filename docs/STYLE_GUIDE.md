# STYLE GUIDE

Panduan ini menjelaskan aturan penulisan konten untuk repository **Japan Nihongo Books**.

Tujuannya adalah memastikan semua materi:

- konsisten
- mudah dipahami
- mudah dikembangkan
- mudah diproses oleh sistem otomatis atau AI

Panduan ini berlaku untuk semua buku, lesson, dan materi di dalam repository.

---

# 1. Prinsip Penulisan

Semua konten harus mengikuti prinsip berikut.

## 1.1 Jelas

Gunakan bahasa yang mudah dipahami.

Hindari kalimat panjang dan rumit.

Contoh baik:

```
Pola ini digunakan untuk memperkenalkan diri.
```

Contoh buruk:

```
Pola ini biasanya dalam beberapa situasi tertentu digunakan oleh penutur untuk memperkenalkan dirinya kepada orang lain.
```

---

## 1.2 Ringkas

Tuliskan informasi seperlunya.

Hindari paragraf yang terlalu panjang.

Gunakan:

- tabel
- daftar
- contoh

jika memungkinkan.

---

## 1.3 Konsisten

Gunakan format yang sama di seluruh repository.

Contoh:

- struktur lesson sama
- format tabel kosakata sama
- format grammar sama

---

## 1.4 Terstruktur

Gunakan heading yang jelas.

Contoh struktur:

```
# Judul
## Subjudul
### Detail
```

---

# 2. Bahasa yang Digunakan

Konten utama menggunakan **Bahasa Indonesia**.

Namun tetap menyertakan:

- Bahasa Jepang
- Hiragana
- Romaji (jika diperlukan)

---

# 3. Aturan Penulisan Bahasa Jepang

Gunakan format berikut.

| Elemen | Aturan |
|------|------|
| Kanji | digunakan jika ada |
| Hiragana | selalu disertakan |
| Romaji | digunakan pada kosakata dan percakapan |

Contoh:

```
日本
にほん
Nihon
```

---

# 4. Struktur Lesson

Setiap lesson harus memiliki struktur berikut.

```
lesson-XX-topic
```

Contoh:

```
lesson-01-perkenalan
lesson-02-ini-apa
lesson-03-lokasi-benda
```

Di dalam folder lesson harus terdapat file berikut.

```
vocab.md
grammar.md
kaiwa.md
drills.md
notes.md
```

Penjelasan:

| File | Fungsi |
|-----|------|
| vocab.md | daftar kosakata |
| grammar.md | penjelasan tata bahasa |
| kaiwa.md | contoh percakapan |
| drills.md | latihan |
| notes.md | catatan tambahan |

---

# 5. Format Kosakata

Kosakata harus ditulis dalam bentuk tabel.

Gunakan format berikut.

| Bahasa Jepang | Hiragana | Romaji | Jenis Kata | Arti | Contoh |
|---------------|----------|--------|-----------|------|-------|

Contoh:

| Bahasa Jepang | Hiragana | Romaji | Jenis Kata | Arti | Contoh |
|---------------|----------|--------|-----------|------|-------|
| 私 | わたし | watashi | kata ganti | saya | 私は学生です |
| 学生 | がくせい | gakusei | kata benda | mahasiswa | 私は学生です |
| 先生 | せんせい | sensei | kata benda | guru | 先生は日本人です |

---

# 6. Format Grammar

Setiap grammar harus mengikuti struktur berikut.

## Pola

```
A は B です
```

## Makna

```
A adalah B
```

## Penjelasan

Digunakan untuk menyatakan identitas atau kategori.

## Contoh

```
私は学生です。
わたしはがくせいです。
Watashi wa gakusei desu.
Saya adalah mahasiswa.
```

Contoh lain:

```
田中さんは先生です。
たなかさんはせんせいです。
Tanaka-san wa sensei desu.
Tanaka adalah guru.
```

---

# 7. Format Contoh Kalimat

Gunakan urutan berikut.

```
日本語
Hiragana
Romaji
Terjemahan
```

Contoh:

```
日本へ行きます。
にほんへいきます。
Nihon e ikimasu.
Saya pergi ke Jepang.
```

---

# 8. Format Percakapan (Kaiwa)

Gunakan format berikut.

```
A: 日本語
   Hiragana
   Romaji
   Terjemahan
```

Contoh:

```
A: はじめまして。
   はじめまして。
   Hajimemashite.
   Senang bertemu dengan Anda.

B: はじめまして。
   はじめまして。
   Hajimemashite.
   Senang bertemu dengan Anda juga.
```

---

# 9. Format Latihan (Drills)

Gunakan format daftar.

Contoh:

```
1. Terjemahkan ke bahasa Jepang.

Saya mahasiswa.
Saya guru.
Saya orang Indonesia.
```

Atau:

```
Isi bagian kosong.

私は ______ です。
```

---

# 10. Aturan Penamaan File

Gunakan huruf kecil.

Gunakan tanda minus `-` untuk pemisah kata.

Contoh benar:

```
lesson-01-perkenalan
lesson-02-ini-apa
lesson-03-lokasi-benda
```

Contoh salah:

```
Lesson01
Lesson_01
lesson01
```

---

# 11. Aturan Aset Gambar

Jika menggunakan gambar:

- gambar harus jelas
- mudah dipahami
- mendukung materi pembelajaran

Gunakan emoji jika memungkinkan.

Contoh:

```
🍎 apel
🍞 roti
🚗 mobil
```

Jika gambar diperlukan:

- gunakan format **SVG** atau **PNG**
- simpan di folder:

```
assets/images
```

---

# 12. Aturan Aset Audio

Audio digunakan untuk membantu pelafalan.

Format audio:

```
mp3
```

Struktur penyimpanan:

```
assets/audio
```

Penamaan file:

```
lesson-01-watashi.mp3
lesson-01-gakusei.mp3
```

---

# 13. Konsistensi Format

Semua kontributor harus menjaga:

- struktur lesson
- format tabel
- format grammar
- format contoh kalimat

Agar seluruh repository tetap konsisten.

---

# 14. Tujuan Panduan Ini

Panduan ini dibuat agar materi di repository ini:

- mudah dibaca manusia
- mudah dipelajari
- mudah dikembangkan
- dapat digunakan sebagai dataset pembelajaran bahasa Jepang
