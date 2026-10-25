# Notes App

Aplikasi catatan sederhana yang dibuat menggunakan Flutter dan Dart.

## Identitas

- Nama: Naffa Verlita N. Z
- Kelas: XI PPLG 1

## Fitur

- Menambahkan catatan
- Melihat daftar catatan
- Mengedit catatan
- Menghapus catatan
- Validasi judul dan isi catatan

## Teknologi

- Flutter
- Dart
- Provider untuk state management
- Material Design

## Struktur Folder

```text
lib/
├── main.dart
├── models/
│   └── note_model.dart
├── providers/
│   └── note_provider.dart
├── pages/
│   ├── home_page.dart
│   └── add_note_page.dart
└── widgets/
    └── note_card.dart
```

## Cara Menjalankan

1. Pastikan Flutter sudah terpasang.
2. Jalankan `flutter pub get`.
3. Jalankan `flutter run`.

## Catatan

Data catatan saat ini disimpan sementara di memori aplikasi. Catatan dapat hilang ketika aplikasi dimulai ulang karena belum menggunakan database permanen.
