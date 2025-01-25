# Aplikasi Konversi Suhu
 
Aplikasi Konversi Suhu adalah aplikasi berbasis Java Swing yang memungkinkan pengguna untuk mengonversi nilai suhu antara berbagai skala suhu, termasuk Celcius, Fahrenheit, Reamur, dan Kelvin. Aplikasi ini menyediakan antarmuka pengguna yang interaktif dan mudah digunakan.

---

## Fitur Utama

- **Konversi Suhu**: Mendukung konversi antara empat skala suhu: Celcius (°C), Fahrenheit (°F), Reamur (°Ré), dan Kelvin (K).
- **Mode Konversi**:
  - Dari skala asal ke skala tujuan.
  - Dari skala tujuan kembali ke skala asal.
- **Input dan Output**:
  - Input angka suhu secara manual.
  - Hasil konversi ditampilkan dalam format yang jelas.
- **Konversi Otomatis**: Hasil akan diperbarui secara otomatis setiap kali input suhu diubah.
- **Validasi Input**: Aplikasi memverifikasi input agar hanya angka desimal yang dapat dimasukkan.
- **Reset dan Keluar**:
  - Tombol "Hapus" untuk mereset input dan output.
  - Tombol "Keluar" untuk menutup aplikasi.

---

## Struktur Antarmuka Pengguna

1. **Input Suhu**:
   - TextField untuk memasukkan suhu yang ingin dikonversi.
   
2. **Pilihan Skala**:
   - Dropdown (ComboBox) untuk memilih skala asal.
   - Dropdown (ComboBox) untuk memilih skala tujuan.

3. **Mode Konversi**:
   - RadioButton untuk memilih arah konversi: dari asal ke tujuan atau sebaliknya.

4. **Hasil Konversi**:
   - TextField untuk menampilkan hasil konversi.

5. **Tombol**:
   - Tombol "Konversi" untuk memulai konversi.
   - Tombol "Hapus" untuk mereset aplikasi.
   - Tombol "Keluar" untuk menutup aplikasi.

---

## Cara Menggunakan

1. Jalankan aplikasi dengan mengeksekusi file `aplikasiKonversiSuhu`.
2. Masukkan nilai suhu pada field **Input Suhu**.
3. Pilih skala asal dan tujuan menggunakan dropdown.
4. Pilih mode konversi dengan memilih salah satu dari RadioButton:
   - "Dari asal ke tujuan"
   - "Dari tujuan ke asal"
5. Klik tombol **Konversi** untuk mendapatkan hasil.
6. Jika ingin mencoba lagi, gunakan tombol **Hapus** untuk mereset.
7. Klik tombol **Keluar** untuk menutup aplikasi.

---

## Kode Utama

### Metode Konversi
Metode `konversiSuhu` menangani logika konversi suhu. Berikut adalah rumus konversi yang diterapkan:

- **Celcius ke Fahrenheit**: `(input * 9/5) + 32`
- **Celcius ke Reamur**: `input * 4/5`
- **Celcius ke Kelvin**: `input + 273.15`
- **Fahrenheit ke Celcius**: `(input - 32) * 5/9`
- **Fahrenheit ke Reamur**: `(input - 32) * 4/9`
- **Fahrenheit ke Kelvin**: `(input - 32) * 5/9 + 273.15`
- **Reamur ke Celcius**: `input * 5/4`
- **Reamur ke Fahrenheit**: `(input * 9/4) + 32`
- **Reamur ke Kelvin**: `(input * 5/4) + 273.15`
- **Kelvin ke Celcius**: `input - 273.15`
- **Kelvin ke Fahrenheit**: `(input - 273.15) * 9/5 + 32`
- **Kelvin ke Reamur**: `(input - 273.15) * 4/5`

---

## Validasi Input
- Aplikasi memastikan bahwa input yang dimasukkan hanya berupa angka desimal.
- Jika input tidak valid, pengguna akan mendapatkan pesan kesalahan.

---

## Persyaratan Sistem

- **Java Development Kit (JDK)**: Versi 8 atau lebih baru.
- **IDE**: NetBeans atau IDE lain yang mendukung Java Swing.

---

## Petunjuk Instalasi

1. Pastikan JDK terinstal di sistem Anda.
2. Unduh atau salin file source code `aplikasiKonversiSuhu.java`.
3. Buka file di IDE seperti NetBeans.
4. Jalankan file melalui IDE.

---

## Catatan

- Jika tidak memilih mode konversi (RadioButton), aplikasi akan menampilkan peringatan.
- Hasil konversi ditampilkan dengan dua angka di belakang koma.

---


## Pembuat Aplikasi
Ahmad Dzul Fauzil Azhim - 2210010389

## Demo


