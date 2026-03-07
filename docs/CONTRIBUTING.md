# Panduan Kontribusi

Dokumen ini menjelaskan cara berkontribusi pada repository **Japan Nihongo Books**.

Repository ini dirancang untuk memungkinkan kolaborasi antara:

* kontributor manusia
* bantuan AI

Tujuan dari panduan ini adalah menjaga agar repository tetap **rapi, konsisten, dan mudah dikembangkan**.

---

# Prinsip Kontribusi

Semua kontributor diharapkan mengikuti prinsip berikut:

1. Menjaga struktur repository tetap konsisten
2. Mengikuti style guide yang telah ditentukan
3. Tidak mengubah struktur folder tanpa diskusi
4. Menjaga kualitas materi pembelajaran

Dokumen yang harus dibaca sebelum berkontribusi:

* `docs/STRUCTURE.md`
* `docs/STYLE_GUIDE.md`
* `docs/style-guide/images.md`
* `docs/style-guide/audio.md`

---

# Cara Menambahkan Lesson Baru

Untuk menambahkan lesson baru, ikuti langkah berikut.

## 1. Buat Folder Lesson

Gunakan format berikut:

```id="v6zsjr"
lesson-XX-nama-topik
```

Contoh:

```id="oxh5rg"
lesson-01-perkenalan
lesson-02-ini-apa
lesson-03-lokasi-benda
```

---

## 2. Buat Struktur File Lesson

Setiap lesson harus memiliki struktur berikut:

```id="grz09s"
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

Semua lesson harus mengikuti struktur ini.

---

# Cara Menambahkan Konten

Konten harus mengikuti aturan pada:

```
docs/STYLE_GUIDE.md
```

Hal yang perlu diperhatikan:

* gunakan format Markdown
* gunakan tabel untuk kosakata
* gunakan contoh kalimat yang jelas
* gunakan bahasa yang mudah dipahami

---

# Aturan Penggunaan Gambar

Semua gambar harus mengikuti aturan pada:

```
docs/style-guide/images.md
```

Ringkasan aturan:

* gambar harus jelas
* tidak terlalu kompleks
* gunakan emoji jika cukup
* gunakan SVG jika membutuhkan ikon

---

# Aturan Penggunaan Audio

Semua audio harus mengikuti aturan pada:

```
docs/style-guide/audio.md
```

Ringkasan aturan:

* gunakan format MP3
* audio harus jelas
* simpan di folder `media/audio`

---

# Aturan Penamaan File

Gunakan aturan berikut:

* huruf kecil
* gunakan tanda `-`
* tidak menggunakan spasi

Contoh yang benar:

```
lesson-01-perkenalan
grammar.md
vocab.md
kaiwa-01.mp3
```

Contoh yang salah:

```
Lesson 1
Grammar.md
lesson_01
```

---

# Penggunaan AI

Repository ini memperbolehkan penggunaan AI untuk membantu:

* menulis materi
* memperbaiki penjelasan
* membuat contoh kalimat

Namun AI **tidak boleh**:

* mengubah struktur repository
* mengubah aturan style guide
* memindahkan folder atau file tanpa diskusi

Semua hasil AI harus tetap diperiksa oleh kontributor manusia.

---

# Aturan Commit

Gunakan pesan commit yang jelas.

Contoh commit yang baik:

```
menambahkan lesson 01 perkenalan
menambahkan kosakata lesson 02
memperbaiki penjelasan grammar lesson 03
```

Hindari commit seperti:

```
update
fix
perbaikan
```

---

# Diskusi Perubahan Struktur

Jika ingin:

* mengubah struktur folder
* mengubah format lesson
* menambahkan jenis media baru

maka perubahan tersebut harus didiskusikan terlebih dahulu sebelum diterapkan.

---

# Tujuan Kolaborasi

Repository ini bertujuan membangun **perpustakaan digital pembelajaran bahasa Jepang** yang:

* rapi
* konsisten
* mudah dipelajari
* mudah dikembangkan

Semua kontributor diharapkan membantu menjaga kualitas materi.
