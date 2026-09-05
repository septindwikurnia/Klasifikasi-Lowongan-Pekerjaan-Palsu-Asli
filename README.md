# 💼 Klasifikasi Lowongan Pekerjaan Asli / Palsu

Project ini bertujuan untuk mendeteksi apakah suatu lowongan pekerjaan **ASLI** atau **PALSU** menggunakan model NLP.

## 📊 Model

Dashboard menyediakan tiga pilihan model:

* **LSTM** → ringan dan cepat
* **DistilBERT** → model Transformer yang lebih ringan
* **BERT** → model Transformer

### Hasil Evaluasi

| Model      | Accuracy |
| ---------- | -------: |
| LSTM       |    98.1% |
| DistilBERT |    98.0% |
| BERT       |    97.7% |

> Berdasarkan hasil pengujian pada dataset yang digunakan, LSTM memperoleh accuracy tertinggi. Ketiga model memiliki performa yang relatif serupa.

## 🔍 Prediksi

Pengguna dapat memilih model yang tersedia, kemudian memasukkan **teks lowongan pekerjaan** untuk mendapatkan hasil klasifikasi:

* **ASLI**
* **PALSU**

## 📁 Dataset

Dataset menggunakan dua sumber, yaitu:

* `dataset1.csv`
* `dataset2.csv`

Masing-masing dataset diambil sebanyak **2.500 data**, kemudian digabungkan menjadi **5.000 data**. Data menggunakan beberapa atribut yang sama, seperti:

`title`, `description`, `requirements`, `company_profile`, `location`, `salary_range`, `employment_type`, `industry`, `benefits`, dan `fraudulent`.

Label:

* `0` = Lowongan Asli
* `1` = Lowongan Palsu

## 🧠 Model yang Digunakan

* LSTM
* DistilBERT
* BERT

## 🛠️ Teknologi

* Python
* TensorFlow / Keras
* PyTorch
* Hugging Face Transformers
* Scikit-learn
* Pandas
* NumPy
* Google Colab

## 💾 Model Terlatih

Model yang telah dilatih tersedia di:

[Google Drive – Model Terlatih](https://drive.google.com/drive/folders/1BuM3OcycfM4-TDqv7BKPCEeHX4YUekrg?usp=sharing&utm_source=chatgpt.com)

## 🖥️ Dashboard

Dashboard menyediakan fitur:

1. Memilih model LSTM, DistilBERT, atau BERT.
2. Memasukkan teks lowongan pekerjaan.
3. Melakukan prediksi.
4. Menampilkan hasil klasifikasi **ASLI** atau **PALSU**.
