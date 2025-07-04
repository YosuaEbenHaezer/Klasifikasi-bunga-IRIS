# Klasifikasi Data Bunga Iris

Repositori ini berisi berbagai pendekatan klasifikasi terhadap dataset bunga **Iris**, menggunakan algoritma pohon keputusan dan K-Nearest Neighbors (KNN) di R. File dalam repositori ini terdiri dari file `.Rmd`, `.html`, serta dataset `.csv` yang digunakan untuk pelatihan dan pengujian.

## 📁 Daftar File

### 1. Decision Tree (Pohon Keputusan)
- `101_1_DT_CTREE dan 10_2_DT_RPART.Rmd`  
  Notebook R Markdown untuk membangun model klasifikasi menggunakan algoritma:
  - **CTREE (Conditional Inference Tree)**
  - **RPART (Recursive Partitioning Tree / CART)**

- `101_1_DT_CTREE-dan-10_2_DT_RPART.html`  
  Hasil render dari file Rmd di atas dalam bentuk HTML.

---

### 2. Decision Tree with C4.5 (J48)
- `DecisionTreeWithC48 fungsi J48.Rmd`  
  Notebook R Markdown untuk klasifikasi menggunakan algoritma **C4.5 (J48)** dari WEKA melalui R.

- `DecisionTreeWithC48-fungsi-J48.html`  
  Output HTML dari notebook di atas.

---

### 3. K-Nearest Neighbors (KNN)
- `KNN.Rmd`  
  Notebook R Markdown untuk membangun model klasifikasi menggunakan algoritma **KNN**.

- `KNN.html`  
  Hasil render HTML dari proses klasifikasi menggunakan KNN.

---

### 4. Dataset
- `datairis.csv`  
  Dataset utama bunga Iris untuk proses pelatihan model klasifikasi.

- `datairisTesting.csv`  
  Dataset pengujian (testing) untuk menguji akurasi model yang dibangun.

---

## 📌 Algoritma yang Digunakan

1. **CTREE** – Conditional inference tree berdasarkan uji statistik.
2. **RPART** – Decision tree berbasis CART (Classification and Regression Tree).
3. **C4.5 (J48)** – Pohon keputusan berbasis information gain ratio.
4. **KNN** – K-Nearest Neighbors untuk klasifikasi berbasis kedekatan jarak.

---

## 📝 Tujuan
Proyek ini bertujuan untuk membandingkan performa berbagai algoritma klasifikasi terhadap dataset Iris, serta mengevaluasi akurasi dan efektivitas masing-masing metode.

---

## ⚙️ Tools
- Bahasa: **R**
- Library: `rpart`, `party`, `RWeka`, `class`, dll
- IDE: RStudio
