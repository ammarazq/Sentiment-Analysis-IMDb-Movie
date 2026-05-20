# Sentiment-Analysis-IMDb-Movie

## Deskripsi Project

Project ini merupakan implementasi **Sentiment Analysis** pada dataset ulasan film IMDb menggunakan beberapa metode machine learning, yaitu:

* Logistic Regression (LR)
* Support Vector Machine (SVM)
* Naive Bayes (NB)
* Stochastic Gradient Descent (SGD)

Penelitian dilakukan dengan tahapan preprocessing teks, ekstraksi fitur menggunakan TF-IDF dan Bag of Words (BoW), pelatihan model, serta evaluasi performa menggunakan accuracy, precision, recall, dan F1-score.

---

# Dataset

Dataset yang digunakan:

* **IMDb Dataset of 50K Movie Reviews**

Dataset berisi:

* 50.000 review film
* Sentimen:

  * Positive
  * Negative

---

# Library yang Digunakan

* NumPy
* Pandas
* Matplotlib
* Seaborn
* NLTK
* Scikit-learn
* BeautifulSoup4

---

# Tahapan Penelitian

## 1. Import Library

Mengimpor library yang digunakan untuk:

* manipulasi data
* preprocessing teks
* visualisasi
* machine learning
* evaluasi model

---

## 2. Data Loading

Dataset dibaca menggunakan `pandas.read_csv()`.

---

## 3. Preprocessing Text

Tahapan preprocessing meliputi:

* Removing HTML Tags
* Removing Square Brackets
* Removing Special Characters
* Stemming
* Stopword Removal

Preprocessing dilakukan untuk membersihkan teks agar model dapat mempelajari data dengan lebih optimal.

---

## 4. Train-Test Split

Dataset dibagi menjadi:

* 80% data training
* 20% data testing

menggunakan `train_test_split()`.

---

## 5. Feature Extraction

### Bag of Words (BoW)

Mengubah teks menjadi representasi frekuensi kata.

### TF-IDF

Mengubah teks menjadi representasi numerik berdasarkan pentingnya kata pada dokumen.

---

## 6. Model Training

Model yang digunakan:

* Logistic Regression
* Support Vector Machine (SVM)
* Naive Bayes
* SGD Classifier

---

## 7. Evaluasi Model

Evaluasi dilakukan menggunakan:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

# Hasil Penelitian

Berdasarkan hasil pengujian:

* TF-IDF memberikan performa yang lebih baik dibandingkan Bag of Words.
* Logistic Regression menunjukkan hasil yang lebih optimal saat menggunakan TF-IDF.
* Oleh karena itu, seluruh metode menggunakan fitur TF-IDF pada tahap evaluasi akhir.

Model terbaik diperoleh menggunakan:

## Support Vector Machine (SVM)

dengan akurasi sebesar:

# 91%

SVM mampu memberikan performa terbaik karena efektif dalam menangani data teks berdimensi tinggi.

---

# Cara Menjalankan Project

## 1. Clone Repository

```bash
git clone https://github.com/username/repository-name.git
```

---

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3. Jalankan Notebook

Gunakan:

* Google Colab
* Jupyter Notebook
* VS Code

---

# Requirements

```txt
numpy
pandas
matplotlib
seaborn
nltk
scikit-learn
beautifulsoup4
wordcloud
textblob
```

---

# Author

Name: Ammara Desma Marzooqa

Project: Sentiment Analysis IMDb Reviews using Machine Learning
