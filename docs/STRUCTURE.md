# Struktur Repository

Dokumen ini menjelaskan struktur folder yang digunakan dalam repository **Japan Nihongo Books**.

Struktur ini dibuat agar materi pembelajaran bahasa Jepang tersusun secara **rapi, konsisten, dan mudah dikembangkan**.

Semua kontributor diharapkan mengikuti aturan struktur yang dijelaskan dalam dokumen ini.

---

# Struktur Utama Repository

Struktur utama repository adalah sebagai berikut:

```
japan-nihongo-books
│
├── README.md
│
├── docs/
│   ├── STRUCTURE.md
│   ├── STYLE_GUIDE.md
│   └── CONTRIBUTING.md
│
├── books/
│   ├── minna-no-nihongo/
│   ├── irodori/
│   └── lainnya/
│
└── assets/
    ├── audio/
    └── images/
```

Penjelasan folder utama:

| Folder | Fungsi                                      |
| ------ | ------------------------------------------- |
| docs   | Dokumentasi dan aturan repository           |
| books  | Berisi buku-buku pembelajaran bahasa Jepang |
| assets | Berisi file media seperti audio dan gambar  |

---

# Struktur Folder Books

Setiap buku ditempatkan di dalam folder **books**.

Contoh:

```
books/
│
├── minna-no-nihongo/
│   ├── book-1/
│   ├── book-2/
│   └── book-3/
│
├── irodori/
│   ├── starter-a1/
│   ├── elementary-a2/
│   └── intermediate-b1/
```

Aturan penamaan folder:

* menggunakan huruf kecil
* menggunakan tanda `-` sebagai pemisah kata
* tidak menggunakan spasi

Contoh yang benar:

```
minna-no-nihongo
irodori
starter-a1
```

Contoh yang salah:

```
Minna No Nihongo
Irodori Starter
Minna_no_Nihongo
```

---

# Struktur Buku

Setiap buku memiliki folder **lessons** yang berisi lesson.

Contoh:

```
book-1/
│
└── lessons/
    ├── lesson-01-perkenalan
    ├── lesson-02-ini-apa
    ├── lesson-03-lokasi-benda
```

---

# Penamaan Lesson

Setiap lesson harus menggunakan format berikut:

```
lesson-XX-nama-topik
```

Keterangan:

| Bagian     | Fungsi                      |
| ---------- | --------------------------- |
| lesson     | penanda folder lesson       |
| XX         | nomor lesson (01,02,03,...) |
| nama-topik | topik utama lesson          |

Contoh yang benar:

```
lesson-01-perkenalan
lesson-02-ini-apa
lesson-03-lokasi-benda
lesson-04-waktu
lesson-05-kegiatan-sehari-hari
```

Format ini digunakan agar:

* urutan lesson tetap rapi
* isi lesson mudah dikenali
* repository lebih mudah dinavigasi

---

# Struktur Lesson

Setiap lesson memiliki struktur file yang sama.

Contoh:

```
lesson-01-perkenalan/
│
├── vocab.md
├── grammar.md
├── kaiwa.md
├── drills.md
├── notes.md
│
└── media/
    ├── audio/
    └── images/
```

Penjelasan file:

| File       | Isi                    |
| ---------- | ---------------------- |
| vocab.md   | Daftar kosakata        |
| grammar.md | Penjelasan tata bahasa |
| kaiwa.md   | Percakapan / dialog    |
| drills.md  | Latihan                |
| notes.md   | Catatan tambahan       |

---

# Aturan Media

File media seperti audio dan gambar harus disimpan di dalam folder **media**.

Contoh:

```
lesson-01-perkenalan/
└── media/
    ├── audio/
    └── images/
```

Aturan:

* file audio ditempatkan di `audio`
* gambar ditempatkan di `images`

---

# Aturan Penamaan File

Beberapa aturan penamaan file yang harus diikuti:

1. Gunakan huruf kecil
2. Gunakan tanda `-` untuk memisahkan kata
3. Jangan menggunakan spasi
4. Jangan menggunakan karakter khusus

Contoh yang benar:

```
lesson-01-perkenalan
grammar.md
vocab.md
starter-a1
```

Contoh yang salah:

```
Lesson 1
Grammar.md
lesson_01
```

---

# Konsistensi Struktur

Semua buku dan lesson harus mengikuti struktur yang sama.

Hal ini penting agar:

* repository tetap rapi
* mudah dipahami
* mudah dikembangkan
* mudah digunakan oleh manusia dan AI

Jika ingin mengubah struktur repository, perubahan harus didiskusikan terlebih dahulu sebelum diterapkan.
