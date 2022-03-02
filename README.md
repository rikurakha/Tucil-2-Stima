# Tugas Kecil 2 IF2211 Strategi Algoritma
### Implementasi Convex Hull untuk Visualisasi Tes Linear Separability Dataset dengan Algoritma Divide and Conquer

Repository ini dibuat dalam rangka memenuhi Tugas Kecil 2 mata kuliah IF2211 Strategi Algoritma Semester 4 Tahun 2021/2022

## Table of Contents

- [Deskripsi Program](#deskripsi-program)
- [Struktur Repository](#struktur-repository)
- [Requirement](#requirements)
- [How to Use](#how-to-use)

## Deskripsi Program

Repository ini berisi implementasi dari algoritma devide and conquer dalam program pembuatan convex hull dari kumpulan titik data dalam bidang kartesian dua dimensi yang mana akan digunakan untuk visualisasi tes linear seperability pada dataset yang diuji coba

## Struktur Repository  

Repository ini terdiri dari 2 directory yaitu sebagai berikut

1. **`src`**, berisi source code program yang terdiri dari bahasa `Python` 
2. **`doc`**, berisi dokumen laporan dari pembuatan program
3. **`test`**, berisi text file yang memuat dataset apa yang digunakan dalam uji coba

## Requirements

Untuk menjalankan program ini, bisa menggunakan aplikasi interactive computational environment untuk menjalankan file .ipynb seperti `Jupyter Notebook` atau `Google Collab`

Jika menjalankan secara local, maka terdapat beberapa python library yang harus diinstall menggunakan `pip install` terlebih dahulu, yaitu
1. **pandas**, untuk memanipulasi data
2. **numpy**, untuk melakukan operasi perhitungan dan array
3. **matplotlib**, untuk melakukan visualisasi plotting data dan convex hull
4. **sklearn**, untuk mengambil dataset untuk uji coba

## How to Use

Berikut adalah langkah yang dapat diikuti untuk menjalankan program ini

1. Buka file `src/Tucil2_13520108.ipynb` atau bisa langsung akses link menuju Google Collab Notebook: https://colab.research.google.com/drive/1oYcSNt4-awyp1xVHUD_0EwZmyRfrxZ9B?usp=sharing
2. Untuk menjalankan program, `run` tiap blok kode secara berurutan dari atas. Untuk menjalankan seluruh program sekaligus, pilih `runtime > run all` pada option bar
3. Untuk mengganti dataset yang digunakan, silakan rubah bagian `data = datasets.load_{nama dataset}`
4. Untuk mengganti atribut yang dibandingkan, silakan rubah bagian `printConvexHull(df, {indeks atribut 1}, {indeks atribut 2})
5. Lakukan `run` sekali lagi pada blok kode yang dirubah untuk melihat perubahannya
