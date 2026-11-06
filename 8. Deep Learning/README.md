# Tugas Praktikum Deep Learning

Terdapat dua tugas pada modul ini. Masing-masing dikerjakan pada notebook yang berbeda.

Template tersedia dalam dua versi framework. **Pilih salah satu** dan gunakan framework yang sama untuk kedua tugas:

| Framework | Folder |
| --- | --- |
| TensorFlow / Keras | `TensorFlow/` |
| PyTorch | `PyTorch/` |

Isi tugas pada kedua versi sama persis, yang berbeda hanya petunjuk teknis sesuai framework.

## Tugas 1 - Customer Churn Prediction

**Dataset:** https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling

**File notebook:** `1_DL_NRP.ipynb`

Dataset ini berisi data 10.000 nasabah bank, seperti skor kredit, negara, usia, saldo, dan status keaktifan. Fiturnya merupakan campuran numerik dan kategorikal. Tujuannya adalah memprediksi apakah seorang nasabah akan berhenti menjadi nasabah (churn) atau tidak.

Pada tugas ini kalian akan membangun dan membandingkan beberapa model:
- Logistic Regression (baseline)
- ANN sederhana (1 hidden layer)
- ANN lebih dalam dengan Dropout
- ANN dengan class weight untuk menangani data imbalanced

Perhatikan learning curve setiap model untuk melihat apakah terjadi overfitting atau underfitting.

## Tugas 2 - Fashion-MNIST Classification

**Dataset:** https://www.kaggle.com/datasets/zalando-research/fashionmnist

**File notebook:** `2_DL_NRP.ipynb`

Dataset ini berisi 70.000 gambar grayscale berukuran 28×28 piksel dari 10 jenis pakaian, seperti kaos, celana, sepatu, dan tas. Tujuannya adalah mengklasifikasikan jenis pakaian dari gambar.

Pada tugas ini kalian akan membangun dan membandingkan tiga model:
- ANN (baseline)
- CNN sederhana
- CNN dengan Batch Normalization dan Dropout

Karena ANN dan CNN membutuhkan bentuk input yang berbeda, baca baik-baik keterangan di setiap section sebelum menulis kode. Disarankan menggunakan GPU (Google Colab atau Kaggle Notebook).

Simpan model terbaik di akhir notebook, karena model tersebut akan digunakan kembali pada tugas Deployment.

## Ketentuan Pengerjaan

- Kerjakan secara mandiri.
- Isi bagian analisis dan kesimpulan berdasarkan hasil eksperimen kalian sendiri, bukan hasil orang lain.
- Ganti nama dan NRP pada tabel di bagian atas notebook.
- Pastikan semua cell sudah dijalankan dan output-nya terlihat sebelum dikumpulkan.
- Kumpulkan file notebook dengan format penamaan: `1_DL_NRP.ipynb` dan `2_DL_NRP.ipynb`
