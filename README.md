# Kalkulator Standar Deviasi Relatif (RSD) - ZNT 2026

Aplikasi web *client-side* yang dirancang untuk menghitung **Rata-rata (Mean)**, **Standar Deviasi (SD)**, dan **Relatif Standar Deviasi (RSD)** secara instan. Alat ini dioptimalkan untuk memvalidasi kelayakan data sampel dalam proyek **Zona Nilai Tanah (ZNT)**.

Dilengkapi dengan antarmuka **Neumorphism** yang responsif dan dukungan *Dark Mode* untuk kenyamanan penggunaan.

---

## ✨ Fitur Utama

1. **Input Sampel Dinamis**: Mendukung penambahan hingga 15 sampel data (dibutuhkan minimal 3 sampel untuk melakukan perhitungan valid).
2. **Perhitungan Statistik Otomatis**: Secara *real-time* menghitung nilai Rata-rata, Standar Deviasi, dan persentase RSD dari data yang dimasukkan.
3. **Pilihan Skala Project ZNT & Threshold Dinamis**:
* **Skala 1:2.500** (Batas Maksimal RSD: **15%**)
* **Skala 1:10.000** (Batas Maksimal RSD: **25%**)
* **Skala 1:25.000** (Batas Maksimal RSD: **30%**)


4. **Indikator Kelayakan Otomatis**: Menampilkan status **"Mantab"** (Warna Hijau) jika hasil RSD berada di bawah atau sama dengan batas toleransi, dan status **"Tidak Mantab!"** (Warna Merah) jika melebihi batas.
5. **Neumorphic & Dark Mode UI**: Tampilan visual yang modern, bersih, dan ramah mata dengan transisi tema yang halus.
6. **Auto-Format Mata Uang**: Input secara otomatis diformat ke dalam bentuk Rupiah saat pengguna mengetik angka untuk meminimalisir kesalahan pembacaan (typo).

---

## 🛠️ Teknologi yang Digunakan

* **HTML5** (Struktur markup)
* **CSS3** (Desain Neumorphism, CSS Grid & Flexbox)
* **Vanilla JavaScript (ES6+)** (Algoritma matematika statistik, cache input agar data tidak hilang saat re-render, manipulasi DOM)

---

## 🚀 Cara Menjalankan (Lokal)

Aplikasi ini tidak memerlukan instalasi server atau *build tools*. Sepenuhnya berjalan di sisi peramban (*browser*).

1. Clone repositori ini atau unduh *source code* dalam format ZIP:
```bash
git clone https://github.com/ekabudiku/kalkulator-std-dev.git

```


2. Buka folder proyek hasil unduhan.
3. Klik dua kali pada file `index.html` untuk membukanya melalui *browser* (Chrome, Edge, Firefox, Safari).

---

## 🌐 Live Demo

Akses versi online melalui GitHub Pages:

👉 [https://ekabudiku.github.io/kalkulator-std-dev/](https://ekabudiku.github.io/kalkulator-std-dev/) *(sesuaikan dengan link github pages Anda)*

---

## 👨‍💻 Author

* **Eka Budi**
* Instagram: [@ekabudiku](https://instagram.com/ekabudiku)
