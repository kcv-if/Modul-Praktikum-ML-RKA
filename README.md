<div align="center">

# Modul Machine Learning Praktikum (Rekayasa Kecerdasan Artifisial)

<br/>

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge\&logo=tensorflow\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)

<br/>

</div>

<p align="justify">
Repositori ini berisi kumpulan modul praktikum dan tugas pembelajaran machine learning yang disusun sebagai pendamping pembelajaran teori bagi mahasiswa program studi Rekayasa Kecerdasan Artifisial. Setiap tugas dirancang untuk memberikan pengalaman langsung dalam mengimplementasikan algoritma machine learning menggunakan Python serta memahami proses penyelesaian permasalahan machine learning secara praktis.
</p>

<p align="justify">
Materi praktikum mencakup berbagai paradigma dan algoritma machine learning, mulai dari supervised learning, unsupervised learning, deep learning, hingga reinforcement learning. Setiap tugas berfokus pada implementasi, eksperimen, analisis hasil, serta evaluasi model sesuai dengan konsep yang telah dipelajari pada modul teori.
</p>

---

## Daftar Isi

* [Struktur Repositori](#struktur-repositori)
* [Daftar Praktikum](#daftar-praktikum)

  * [Supervised Learning](#supervised-learning)
  * [Unsupervised Learning](#unsupervised-learning)
  * [Deep Learning](#deep-learning)
  * [Reinforcement Learning](#reinforcement-learning)
* [Ketentuan Praktikum](#ketentuan-praktikum)
* [Credits](#credits)

---

## Struktur Repositori

```text
Modul-ML-Praktikum/
├── Tugas_KNN/
├── Tugas_NaiveBayes&LogReg/
├── Tugas_DecisionTree/
├── Tugas_SVM&ANN/
├── Tugas_Regression/
├── Tugas_K-MeansClustering/
├── Tugas_HierarchicalClustering/
├── Tugas_DBSCAN_BIRCH_EM/
├── Tugas_DeepLearning(CNN)/
└── Tugas_ReinforcementLearning/
```

Setiap folder berisi materi dan/atau notebook yang diperlukan untuk menyelesaikan tugas praktikum pada topik terkait.

---

## Daftar Praktikum

### Supervised Learning

Supervised learning merupakan paradigma machine learning yang menggunakan data berlabel untuk melatih model. Model mempelajari hubungan antara fitur input dan target output sehingga dapat menghasilkan prediksi terhadap data baru.

#### 1. K-Nearest Neighbors

Folder:

```text
Tugas_KNN/
```

Praktikum ini berfokus pada implementasi algoritma **K-Nearest Neighbors (KNN)** untuk menyelesaikan permasalahan klasifikasi.

Konsep utama yang dipraktikkan meliputi:

* Perhitungan jarak antar data
* Pemilihan nilai `K`
* Proses klasifikasi berdasarkan tetangga terdekat
* Preprocessing dan feature scaling
* Evaluasi performa model
* Analisis pengaruh nilai `K` terhadap performa

---

#### 2. Naive Bayes & Logistic Regression

Folder:

```text
Tugas_NaiveBayes&LogReg/
```

Praktikum ini membahas dua algoritma klasifikasi, yaitu **Naive Bayes** dan **Logistic Regression**.

Konsep utama yang dipraktikkan meliputi:

* Probabilitas dan Teorema Bayes
* Asumsi independensi fitur pada Naive Bayes
* Logistic Regression untuk klasifikasi
* Probabilitas prediksi kelas
* Perbandingan performa kedua algoritma
* Evaluasi menggunakan metrik klasifikasi

---

#### 3. Decision Tree

Folder:

```text
Tugas_DecisionTree/
```

Praktikum ini berfokus pada algoritma **Decision Tree** untuk klasifikasi dan/atau prediksi.

Konsep utama yang dipraktikkan meliputi:

* Struktur decision tree
* Pemilihan fitur
* Entropy dan Information Gain
* Gini Impurity
* Training dan prediction
* Pengaturan kedalaman pohon
* Analisis overfitting dan underfitting

---

#### 4. SVM & ANN

Folder:

```text
Tugas_SVM&ANN/
```

Praktikum ini membahas **Support Vector Machine (SVM)** dan **Artificial Neural Network (ANN)** sebagai algoritma untuk menyelesaikan permasalahan klasifikasi.

Konsep utama yang dipraktikkan meliputi:

* Hyperplane dan margin pada SVM
* Kernel pada SVM
* Feature scaling
* Struktur dasar Artificial Neural Network
* Forward propagation
* Training neural network
* Perbandingan performa SVM dan ANN

---

#### 5. Regression

Folder:

```text
Tugas_Regression/
```

Praktikum ini berfokus pada permasalahan **regression**, yaitu memprediksi nilai target yang bersifat kontinu.

Konsep utama yang dipraktikkan meliputi:

* Linear Regression
* Polynomial Regression
* Training dan prediction
* Evaluasi model regresi
* Analisis hubungan fitur dan target
* Overfitting dan underfitting
* Perbandingan model regresi

---

### Unsupervised Learning

Unsupervised learning merupakan paradigma machine learning yang bekerja dengan data tanpa label. Algoritma digunakan untuk menemukan pola, struktur, atau kelompok yang terdapat di dalam data.

#### 6. K-Means Clustering

Folder:

```text
Tugas_K-MeansClustering/
```

Praktikum ini membahas algoritma **K-Means Clustering** untuk mengelompokkan data berdasarkan kemiripan karakteristik.

Konsep utama yang dipraktikkan meliputi:

* Centroid
* Perhitungan jarak
* Proses iteratif K-Means
* Pemilihan jumlah cluster
* Elbow Method
* Evaluasi hasil clustering
* Visualisasi cluster

---

#### 7. Hierarchical Clustering

Folder:

```text
Tugas_HierarchicalClustering/
```

Praktikum ini membahas **Hierarchical Clustering** untuk membentuk struktur pengelompokan data secara bertingkat.

Konsep utama yang dipraktikkan meliputi:

* Agglomerative Clustering
* Distance dan linkage
* Dendrogram
* Pemilihan jumlah cluster
* Visualisasi hasil clustering
* Analisis struktur hierarki data

---

#### 8. DBSCAN, BIRCH & EM

Folder:

```text
Tugas_DBSCAN_BIRCH_EM/
```

Praktikum ini membahas beberapa algoritma clustering dengan pendekatan yang berbeda, yaitu **DBSCAN**, **BIRCH**, dan **Expectation-Maximization (EM)**.

Konsep utama yang dipraktikkan meliputi:

* Density-based clustering
* Identifikasi noise menggunakan DBSCAN
* Parameter `eps` dan `min_samples`
* Clustering pada dataset berukuran besar menggunakan BIRCH
* Probabilistic clustering menggunakan EM
* Perbandingan karakteristik dan hasil clustering

---

### Deep Learning

Deep learning merupakan subbidang machine learning yang menggunakan jaringan saraf tiruan dengan banyak lapisan untuk mempelajari representasi fitur dari data secara otomatis.

#### 9. Deep Learning (CNN)

Folder:

```text
Tugas_DeepLearning(CNN)/
```

Praktikum ini berfokus pada implementasi **Convolutional Neural Network (CNN)** untuk menyelesaikan permasalahan berbasis citra.

Konsep utama yang dipraktikkan meliputi:

* Struktur dasar neural network
* Convolution layer
* Activation function
* Pooling layer
* Feature extraction
* Fully connected layer
* Training CNN
* Evaluasi model klasifikasi citra
* Analisis hasil prediksi

---

### Reinforcement Learning

Reinforcement learning merupakan paradigma machine learning di mana sebuah agent belajar mengambil keputusan melalui interaksi dengan environment. Agent menerima reward atau penalty sebagai umpan balik untuk meningkatkan strategi pengambilan keputusan.

#### 10. Reinforcement Learning

Folder:

```text
Tugas_ReinforcementLearning/
```

Praktikum ini memperkenalkan konsep dasar **Reinforcement Learning** melalui interaksi antara agent dan environment.

Konsep utama yang dipraktikkan meliputi:

* Agent
* Environment
* State
* Action
* Reward
* Policy
* Value
* Q-Value
* Proses pembelajaran melalui interaksi
* Evaluasi strategi agent

---

## Ketentuan Praktikum

Dalam mengerjakan setiap tugas praktikum, mahasiswa diharapkan:

1. Memahami konsep algoritma sebelum melakukan implementasi.
2. Mengikuti instruksi yang terdapat pada masing-masing tugas.
3. Menjalankan seluruh kode pada notebook dan memastikan tidak terdapat error.
4. Melakukan analisis terhadap hasil eksperimen, bukan hanya menjalankan kode.
5. Menggunakan dataset sesuai dengan ketentuan yang diberikan pada tugas.
6. Menampilkan hasil evaluasi dan visualisasi yang diperlukan.
7. Menuliskan kesimpulan berdasarkan hasil eksperimen.
8. Mengumpulkan tugas sesuai dengan format dan ketentuan yang telah ditentukan.

---

## Credits

**Credits to Asisten Dosen Mata Kuliah Pembelajaran Mesin RKA 2025 and 2026:**

* 2025
  * Tamam Fajar Briliansyah
  * Cathleen Gracia
  * Daniel Adhitthana
  * Nixon Castroman
  
* 2026
  * Jeremy Mattathias Mboe
  * Jason Kumarkono
  * Afarrel Febryan Ghiffari Putra Andy
  * Safa Mashita

---
