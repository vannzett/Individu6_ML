```markdown
# 🐍 Python NumPy Fundamentals

Repo ini berisi materi pembelajaran dasar hingga fundamental mengenai penggunaan library **NumPy** di Python. Materi disusun dalam format Jupyter Notebook (`.ipynb`) yang interaktif.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![NumPy](https://img.shields.io/badge/NumPy-1.16+-green.svg)

## 📖 Tentang NumPy
*NumPy (Numerical Python) adalah library inti untuk komputasi ilmiah di Python. Library ini menyediakan objek array multidimensi berkinerja tinggi, serta berbagai alat untuk bekerja dengan array tersebut.*

Mengapa harus menggunakan NumPy dibandingkan List bawaan Python?
- 🗜️ **Size (Ukuran)**: Struktur data NumPy memakan ruang memori yang jauh lebih sedikit.
- ⚡ **Performance (Performa)**: Kecepatan eksekusinya jauh lebih cepat dibandingkan List Python.
- 🧮 **Functionality (Fungsionalitas)**: Memiliki fungsi-fungsi matematika dan aljabar linear yang sudah dioptimasi (terintegrasi dengan SciPy).

## 📚 Daftar Materi
Notebook pada repo ini mencakup pembahasan berikut:

1. **Setup & Instalasi**
   - Import library dan pengecekan versi.
2. **Pembuatan Array (Creating Arrays)**
   - Membuat Vektor 1D (Baris & Kolom).
   - Membuat Matrix 2D.
   - Fungsi generate array: `np.zeros()`, `np.ones()`, `np.linspace()`.
   - Membuat Array 3D.
3. **Akses Elemen (Indexing & Slicing)**
   - Mengakses baris dan kolom pada 2D Matrix.
   - Teknik *Slicing* (menyeleksi bagian tertentu dari matrix).
   - Studi kasus kompleks: Akses elemen pada Matrix 3D.
4. **Tipe Data & Manajemen Memori**
   - Menampilkan dan mengubah tipe data (`dtype`, `astype`).
   - Optimalisasi memori menggunakan `.nbytes` (contoh: `int32` vs `uint8`).
5. **Deskripsi Array**
   - Mengetahui atribut array: `.shape`, `.size`, `.ndim`.
6. **Fungsi Bawaan Statistik (Built-in Functions)**
   - fungsi dasar: `max`, `min`, `mean`, `median`, `std`, `var`.
   - Fungsi matematika: `np.power()`, `np.sqrt()`.
   - Penggunaan parameter `axis` untuk kalkulasi berbasis baris/kolom (`np.argmax`, `np.argmin`).
7. **Reshape Matrix**
   - Mengubah bentuk array tanpa mengubah data menggunakan `np.reshape()`.
8. **Operasi Matrix (Matrix Operations)**
   - Penjumlahan & Pengurangan (*Element-wise*).
   - Perkalian & Pembagian Skalar.
   - Perkalian *Element-wise* (`*`).
   - Transpose Matrix (`.T`).
   - Perkalian Matrix Sesungguhnya (*Dot Product*).
