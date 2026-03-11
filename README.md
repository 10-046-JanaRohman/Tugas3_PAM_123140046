# My Profile App

Aplikasi **My Profile App** adalah aplikasi sederhana yang dibuat menggunakan Jetpack Compose di Android Studio.  
Aplikasi ini menampilkan halaman profil yang berisi foto profil, nama, bio singkat, serta informasi kontak seperti email, nomor telepon, dan lokasi.

Aplikasi ini dibuat sebagai Tugas Praktikum 3 – Pengembangan Aplikasi Mobile.

---

## Fitur Aplikasi

Aplikasi ini memiliki beberapa fitur utama:

- **Header Profil**
    - Foto profil berbentuk **lingkaran (circular image)**
    - Nama pengguna

- **Bio / Deskripsi Singkat**
    - Menampilkan informasi singkat tentang pengguna

- **Informasi Kontak**
    - Email
    - Nomor telepon
    - Lokasi

- **Tombol Follow**
    - Tombol interaksi sederhana pada halaman profil

---

## Komponen UI yang Digunakan

Aplikasi ini menggunakan beberapa komponen UI dari **Jetpack Compose**, yaitu:

- Column: untuk menyusun komponen secara vertikal
- Row: untuk menyusun informasi secara horizontal
- Box: untuk mengatur posisi layout
- Card: sebagai container utama profil
- Text: menampilkan teks
- Button: tombol interaksi
- Image: menampilkan foto profil
- Icon: ikon untuk email, phone, dan location

---

## Reusable Composable Functions

Aplikasi ini menggunakan **Composable Function yang dapat digunakan kembali**, yaitu:

### 1. ProfileHeader
Menampilkan:
- Foto profil
- Nama pengguna

### 2. InfoItem
Menampilkan informasi dengan ikon dan teks seperti:
- Email
- Phone
- Location

### 3. ProfileCard
Container utama yang berisi seluruh informasi profil.

---

## Struktur Layout

Struktur layout aplikasi menggunakan:

- Box: untuk menempatkan profil di tengah layar
- Card: sebagai tampilan kartu profil
- Column: menyusun elemen secara vertikal
- Row: menyusun ikon dan teks informasi

---

## Screenshot Aplikasi

<img width="344" height="647" alt="Screenshot 2026-03-12 013131" src="https://github.com/user-attachments/assets/e7d22963-ea05-4f9e-be40-6edf21e351f6" />

## Teknologi yang Digunakan

- Kotlin
- Jetpack Compose
- Material 3
- Android Studio

---

## Cara Menjalankan Project

1. Clone repository ini

```
https://github.com/10-046-JanaRohman/Tugas3_PAM_123140046.git
```

2. Buka project menggunakan **Android Studio**

3. Jalankan aplikasi menggunakan:
- Android Emulator
- atau perangkat Android fisik

---

## Author

Nama : Jana Rohman  
NIM : 123140046  
Mata Kuliah : Pengembangan Aplikasi Mobile  
Tugas : Praktikum 3 – My Profile App
