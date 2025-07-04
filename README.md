# Image Enhancement using Histogram Equalization & CLAHE

## Deskripsi

Proyek ini merupakan bagian dari tugas akhir mata kuliah **Visi Komputer**. Tujuan utama proyek adalah melakukan **peningkatan kualitas citra malam hari** dengan menerapkan dua metode klasik dalam pengolahan citra:

- **Histogram Equalization (HE)**
- **Contrast Limited Adaptive Histogram Equalization (CLAHE)**

Perbandingan dilakukan secara visual dan kuantitatif menggunakan metrik:

- (MSE) Mean Squared Error
- PSNR (Peak Signal-to-Noise Ratio)

---

## Tools & Library

- Python 3.x
- Pillow (`PIL`)
- NumPy
- Matplotlib

Instalasi:

```bash
pip install pillow numpy matplotlib
```

---

## Struktur Proyek

```
├── citra1.jpg
├── citra2.jpg
├── citra3.jpg
├── *.png              
├── main.ipynb         
└── README.md          
```

---

## Cara Menjalankan

1. **Jalankan per cell** pada `Jupyter Notebook` atau `Google Colab` sesuai urutan:
   - Import Library
   - Definisi Kelas `ImageEnhancer`
   - Fungsi pemrosesan dan plotting
   - Eksekusi utama

---

## Hasil dan Analisis

Visualisasi dan histogram disimpan sebagai `.png`, serta metrik performa ditampilkan di console.

### Contoh Output:

- CLAHE memberikan kontras yang lebih seimbang secara lokal
- Histogram Equalization meningkatkan kontras global

---

## Kesimpulan

Metode **CLAHE** menghasilkan peningkatan kualitas citra yang lebih stabil dan efektif untuk citra dengan distribusi intensitas yang tidak merata sehingga citra yang dihasilkan lebih terang namun tetap citra malam. Sementara **Histogram Equalization** cocok untuk peningkatan global namun rentan terhadap over-enhancement sehingga citra yang dihasilkan terlalu terang hingga seperti citra siang hari.

---

## Kontak

> Mahasiswa: Suci Artiara
> NIM: D121221069
> Universitas: Hasanuddin
> Fakultas: Teknik
> Departemen: teknik Informatika
