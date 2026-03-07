# Style Guide Audio

Dokumen ini menjelaskan aturan penggunaan audio dalam repository **Japan Nihongo Books**.

Audio digunakan untuk membantu pembelajar memahami pengucapan bahasa Jepang.

---

# Tujuan Audio

Audio digunakan untuk:

* pengucapan kosakata
* percakapan (kaiwa)
* latihan listening

---

# Format File

Gunakan format berikut:

| Format | Keterangan                       |
| ------ | -------------------------------- |
| MP3    | format utama audio               |
| WAV    | jika membutuhkan kualitas tinggi |

Format yang disarankan adalah **MP3**.

---

# Kualitas Audio

Audio harus:

* jelas
* tidak ada noise
* tidak terlalu pelan
* tidak terlalu keras

---

# Jenis Audio

Audio dapat dibagi menjadi beberapa jenis.

## Vocabulary

Audio untuk pengucapan kosakata.

Contoh:

```
watashi.mp3
gakusei.mp3
sensei.mp3
```

---

## Kaiwa

Audio untuk percakapan.

Contoh:

```
kaiwa-01.mp3
kaiwa-02.mp3
```

---

## Listening

Audio untuk latihan mendengar.

Contoh:

```
listening-01.mp3
listening-02.mp3
```

---

# Lokasi Penyimpanan Audio

Audio disimpan di folder:

```
media/audio/
```

Contoh:

```
lesson-01-perkenalan/
└── media/
    └── audio/
        ├── vocab
        ├── kaiwa
        └── listening
```

---

# Penamaan File

Gunakan aturan berikut:

* huruf kecil
* gunakan tanda `-`
* tidak menggunakan spasi

Contoh:

```
vocab-watashi.mp3
kaiwa-01.mp3
listening-01.mp3
```

---

# Ukuran File

Audio harus dioptimalkan agar repository tetap ringan.

Disarankan:

* ukuran file tidak terlalu besar
* gunakan kompresi MP3
