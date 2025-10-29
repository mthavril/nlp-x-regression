# Klasifikasi Tingkat Stres Menggunakan NLP dan Model Machine Learning
### Berdasarkan Machine Learning Life Cycle (MLLC)

Proyek ini bertujuan untuk mengklasifikasikan **tingkat stres pengguna Reddit** menggunakan teknik **Natural Language Processing (NLP)** dan **Machine Learning (ML)**. Alur kerja disusun berdasarkan tahapan **Machine Learning Life Cycle (MLLC)**, mulai dari pengambilan data hingga evaluasi model.

---

## Penulis
- **Nama:** Muthia Mutmainah Aprinelia 
- **Institusi:** Institut Teknologi Garut (ITG)

---

## Dataset
- **Sumber:** [Kaggle – Stress Level Dataset (berbasis Reddit)](--)  
- Dataset berisi data teks dengan label tingkat stres.  
- Untuk memudahkan penggunaan, satu file xlsx  telah disediakan dalam repositori ini.  

---

## Tahapan Machine Learning Life Cycle (MLLC)

### 1. Akuisisi Data
- Mengambil dataset dari Kaggle.  
- Memuat data ke dalam Google Colab.  
- Melakukan pemeriksaan awal seperti jumlah data, kolom, dan nilai kosong.

### 2. Praproses Data
- Pembersihan teks (huruf kecil, menghapus tanda baca, dan sebagainya).  
- Tokenisasi dan penghapusan stopword menggunakan **NLTK**.  
- Lemmatization.  
- Visualisasi teks menggunakan **WordCloud**.  
- Encoding label dan pembagian data menjadi data latih dan uji.  

### 3. latihan & Evaluasi Model
- Beberapa model machine learning yang digunakan:  
  - Logistic Regression  
  - Naive Bayes  
  - Support Vector Machine (SVM)  
  - Random Forest  
- Evaluasi model menggunakan metrik **akurasi**, **presisi**, **recall**, dan **F1-score**.  
- Perbandingan performa model ditampilkan dalam bentuk persentase.  

---

## Tools & Library yang Digunakan
- **Python**
- **Scikit-Learn**
- **NLTK**
- **Seaborn**
- **Matplotlib**
- **WordCloud**
- **Google Colab**

---

## Hasil
- Setiap model dievaluasi dan dibandingkan menggunakan visualisasi grafik batang.  
- Model dengan nilai akurasi tertinggi dipilih sebagai model terbaik.  

---
