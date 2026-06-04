# 🎓 Chatbot NLP Seleksi Calon Anggota Organisasi Kampus

Proyek ini merupakan implementasi chatbot berbasis Natural Language Processing (NLP) untuk membantu proses simulasi seleksi calon anggota organisasi kampus.

Chatbot mampu:

- Memberikan pertanyaan secara adaptif berdasarkan kualitas jawaban peserta.
- Melakukan preprocessing teks Bahasa Indonesia.
- Menghitung kualitas jawaban menggunakan TF-IDF dan Cosine Similarity.
- Memberikan feedback otomatis kepada peserta.
- Menghasilkan rekomendasi kelayakan kandidat berdasarkan berbagai indikator penilaian.

---

## 📌 Latar Belakang

Proses seleksi anggota organisasi kampus sering kali membutuhkan waktu yang cukup lama karena dilakukan secara manual oleh pewawancara.

Penelitian ini mengembangkan sistem chatbot yang dapat membantu proses wawancara awal secara otomatis menggunakan pendekatan NLP sehingga proses seleksi menjadi lebih cepat, objektif, dan konsisten.

---

## 🚀 Fitur Utama

### 1. Data Preprocessing
- Pembersihan teks
- Case folding
- Tokenization
- Stopword removal Bahasa Indonesia

### 2. Feature Engineering
- Nilai Leadership
- Skor Keaktifan
- Skor Pengalaman
- Soft Skill Score

### 3. NLP Processing
- TF-IDF Vectorization
- Cosine Similarity
- Keyword Scoring

### 4. Adaptive Questioning
Tingkat kesulitan pertanyaan disesuaikan berdasarkan kualitas jawaban peserta:

- Mudah
- Sedang
- Sulit

### 5. Automated Evaluation
Chatbot memberikan:

- Nilai jawaban
- Feedback otomatis
- Rekomendasi kandidat

---

## 📊 Dataset

Dataset yang digunakan:

- Predicting Hiring Decisions Dataset
- Kaggle Recruitment Dataset

Dataset kemudian dimodifikasi untuk menyesuaikan kebutuhan simulasi seleksi organisasi kampus.

---

## 🛠️ Teknologi yang Digunakan

- Python
- Pandas
- NumPy
- Scikit-Learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Metode yang Digunakan

### Text Preprocessing

- Lowercase Conversion
- Remove Punctuation
- Remove Numbers
- Stopword Removal
- Tokenization

### Feature Extraction

TF-IDF Vectorizer digunakan untuk mengubah teks menjadi representasi numerik.

### Similarity Measurement

Cosine Similarity digunakan untuk membandingkan jawaban peserta dengan jawaban ideal.

### Adaptive Questioning

Level pertanyaan berikutnya ditentukan berdasarkan skor jawaban sebelumnya.

---

## 📋 Alur Sistem

Dataset
↓
Preprocessing
↓
Feature Engineering
↓
TF-IDF
↓
Cosine Similarity
↓
Scoring
↓
Adaptive Questioning
↓
Feedback
↓
Final Recommendation

---

## 📷 Hasil

Sistem mampu:

✅ Membersihkan data teks Bahasa Indonesia

✅ Mengevaluasi kualitas jawaban peserta

✅ Menyesuaikan tingkat kesulitan pertanyaan

✅ Memberikan rekomendasi kandidat secara otomatis

---

## 📚 Author

Briliant Vilendro Kastilong

Teknik Informatika

Universitas Mercu Buana
