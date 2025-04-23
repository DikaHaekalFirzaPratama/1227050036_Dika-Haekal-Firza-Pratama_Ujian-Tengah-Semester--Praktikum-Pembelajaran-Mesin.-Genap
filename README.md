# 1227050036_Dika-Haekal-Firza-Pratama_Ujian-Tengah-Semester--Praktikum-Pembelajaran-Mesin.-Genap

# UTS Naive Bayes Classifier: Citrus Dataset

Repositori ini berisi implementasi model klasifikasi buah jeruk dan grapefruit menggunakan algoritma **Naive Bayes** dengan bahasa pemrograman Python.

## Dataset
Dataset yang digunakan berasal dari Kaggle: [Oranges vs. Grapefruit](https://www.kaggle.com/datasets/joshmcadams/oranges-vs-grapefruit)

File: `citrus.csv`

## Algoritma
- **Naive Bayes** (Gaussian Naive Bayes)

## Langkah-langkah Pembuatan Model
1. **Import Library**: Mengimpor library seperti `pandas`, `numpy`, `sklearn`, dan lainnya seperti `matplotlib` untuk visualisasi atau `seaborn` untuk analisis lebih lanjut.
2. **Load Dataset**: Membaca file `citrus.csv` ke dalam DataFrame.
3. **Eksplorasi Data**: Melihat distribusi label (grapefruit/orange).
4. **Preprocessing**:
   - Memisahkan fitur (`diameter`, `weight`, `red`, `green`, `blue`) dan label (`name`).
   - Melakukan normalisasi fitur dengan `MinMaxScaler`.
5. **Split Data**: Membagi dataset menjadi data latih dan data uji (75:25).
6. **Model Training**: Melatih model Gaussian Naive Bayes.
7. **Evaluasi Model**:
   - Menghitung akurasi.
   - Menampilkan Confusion Matrix dan Classification Report.

## Hasil Evaluasi
- **Akurasi**: ± 92%
- **Confusion Matrix**:
  - Menunjukkan jumlah prediksi benar/salah per kelas.
- **Classification Report**:
  - Precision, Recall, F1-score untuk masing-masing label.

## Library yang Digunakan
- `pandas`
- `scikit-learn`

## Cara Menjalankan
1. Pastikan file `citrus.csv` ada di folder yang sama dengan file Python `.py`.
2. Buka folder proyek dan file Python.
3. Pastikan Python sudah terpasang dan terkonfigurasi dengan benar.
4. Untuk menjalankan skrip, klik tombol **Run**
