# Versioning Guide (Release)

Dokumen ini mengatur versi rilis untuk `library/minna-no-nihongo`.

## Skema Versi

Gunakan semver sederhana:

- `MAJOR.MINOR.PATCH`

Contoh:

- `1.0.0`
- `1.1.0`
- `1.1.1`

## Kapan Naik Versi

- `MAJOR`:
  - Perubahan besar struktur materi atau aturan yang memengaruhi hampir semua buku/lesson.
- `MINOR`:
  - Penambahan materi signifikan (mis. selesai 1 buku penuh, atau banyak lesson baru).
- `PATCH`:
  - Perbaikan kecil (typo, revisi terjemahan, koreksi contoh).

## Status Rilis

- Gunakan label:
  - `Unreleased`
  - `vX.Y.Z - YYYY-MM-DD`

## Saat Mau Selesai (Release Candidate)

Sebelum rilis final, gunakan versi kandidat:

- `vX.Y.Z-rc.1`
- `vX.Y.Z-rc.2`

Jika validasi selesai, naikkan ke:

- `vX.Y.Z`

## Proses Singkat

1. Perbarui `CHANGELOG.md` (global + per book).
2. Cek `RELEASE_CHECKLIST.md`.
3. Tentukan versi (`rc` atau final).
4. Buat tag release di git (opsional jika diperlukan workflow tim).

