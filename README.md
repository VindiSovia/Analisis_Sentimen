# Analisis_Sentimen

Penelitian ini adalah analisis sentimen dari data media sosial yang dikumpulkan terkait dengan platform e-commerce, seperti Shopee, Tokopedia, Lazada, dan Bukalapak. Model yang digunakan adalah Random Forest dan Naive Bayes untuk memprediksi sentimen positif, negatif, atau netral dari setiap teks ulasan.

Penelitian ini menghasilkan:
- Klasifikasi Sentimen: Menggunakan model Naive Bayes dan Random Forest untuk klasifikasi sentimen teks.
- Pra-pemrosesan Teks: Melakukan pembersihan data teks, seperti menghapus tanda baca, angka, dan kata-kata yang tidak relevan.
- Visualisasi Hasil: Menampilkan metrik evaluasi, seperti akurasi, presisi, recall, dan F1-score, serta visualisasi confusion matrix.
- Evaluasi Model: Melakukan cross-validation untuk mendapatkan hasil evaluasi model yang lebih akurat.

## Dataset
Dataset didapatkan menggunakan 3 platform yaitu X, Appstore, dan Google Playstore. Dataset yang digunakan pada penelitian ini dapat diakses melalui:
https://drive.google.com/drive/folders/1lmVirvNW9k20RI_UHu6z5ac4Bfmqyb4-?usp=drive_link

## Hasil
Berdasarkan akurasi metode yang didapatkan, ditulisakan dalam bentuk tabel pada berikut ini:
## Hasil Evaluasi Model

| Sumber Dataset       | Model             | E-Commerce | Accuracy | Precision | Recall | F1 Score |
|----------------------|-------------------|------------|----------|-----------|--------|----------|
| **Google Play**      | Naive Bayes       | Bukalapak  | 0.87     | 0.88      | 0.88   | 0.87     |
|                      |                   | Shopee     | 0.88     | 0.90      | 0.88   | 0.88     |
|                      |                   | Lazada     | 0.82     | 0.83      | 0.83   | 0.82     |
|                      |                   | Tokopedia  | 0.88     | 0.90      | 0.88   | 0.88     |
|                      | Random Forest     | Bukalapak  | 0.90     | 0.92      | 0.90   | 0.90     |
|                      |                   | Shopee     | 0.93     | 0.93      | 0.93   | 0.93     |
|                      |                   | Lazada     | 0.73     | 0.77      | 0.75   | 0.73     |
|                      |                   | Tokopedia  | 0.97     | 0.97      | 0.97   | 0.97     |
|                      | Stacking Classifier | Bukalapak | 0.93     | 0.93      | 0.94   | 0.93     |
|                      |                   | Shopee     | 0.96     | 0.96      | 0.96   | 0.96     |
|                      |                   | Lazada     | 0.83     | 0.82      | 0.83   | 0.82     |
|                      |                   | Tokopedia  | 0.97     | 0.97      | 0.97   | 0.97     |
| **Appstore**         | Naive Bayes       | Bukalapak  | 0.94     | 0.94      | 0.94   | 0.93     |
|                      |                   | Shopee     | 0.86     | 0.90      | 0.86   | 0.85     |
|                      |                   | Lazada     | 0.64     | 0.66      | 0.65   | 0.63     |
|                      |                   | Tokopedia  | 0.87     | 0.88      | 0.88   | 0.87     |
|                      | Random Forest     | Bukalapak  | 0.88     | 0.89      | 0.88   | 0.88     |
|                      |                   | Shopee     | 0.96     | 0.96      | 0.96   | 0.96     |
|                      |                   | Lazada     | 0.60     | 0.65      | 0.59   | 0.55     |
|                      |                   | Tokopedia  | 0.98     | 0.98      | 0.98   | 0.98     |
|                      | Stacking Classifier | Bukalapak | 0.94     | 0.94      | 0.94   | 0.94     |
|                      |                   | Shopee     | 0.96     | 0.96      | 0.96   | 0.96     |
|                      |                   | Lazada     | 0.72     | 0.75      | 0.74   | 0.72     |
|                      |                   | Tokopedia  | 0.99     | 0.99      | 0.98   | 0.99     |
| **X**                | Naive Bayes       | Bukalapak  | 0.65     | 0.66      | 0.66   | 0.65     |
|                      |                   | Shopee     | 0.71     | 0.77      | 0.73   | 0.69     |
|                      |                   | Lazada     | 0.88     | 0.91      | 0.88   | 0.88     |
|                      |                   | Tokopedia  | 0.80     | 0.82      | 0.81   | 0.80     |
|                      | Random Forest     | Bukalapak  | 0.72     | 0.76      | 0.73   | 0.71     |
|                      |                   | Shopee     | 0.75     | 0.77      | 0.77   | 0.75     |
|                      |                   | Lazada     | 0.99     | 0.99      | 0.99   | 0.99     |
|                      |                   | Tokopedia  | 0.77     | 0.82      | 0.78   | 0.76     |
|                      | Stacking Classifier | Bukalapak | 0.76     | 0.78      | 0.76   | 0.74     |
|                      |                   | Shopee     | 0.81     | 0.82      | 0.83   | 0.81     |
|                      |                   | Lazada     | 0.98     | 0.99      | 0.98   | 0.98     |
|                      |                   | Tokopedia  | 0.77     | 0.80      | 0.78   | 0.77     |
| **Account Official di X** | Naive Bayes | Bukalapak | 0.75     | 0.79      | 0.75   | 0.73     |
|                      |                   | Shopee     | 0.91     | 0.93      | 0.91   | 0.91     |
|                      |                   | Lazada     | 0.78     | 0.80      | 0.80   | 0.77     |
|                      |                   | Tokopedia  | 0.82     | 0.85      | 0.82   | 0.81     |
|                      | Random Forest     | Bukalapak  | 0.82     | 0.86      | 0.82   | 0.81     |
|                      |                   | Shopee     | 1.00     | 1.00      | 1.00   | 1.00     |
|                      |                   | Lazada     | 0.90     | 0.91      | 0.91   | 0.90     |
|                      |                   | Tokopedia  | 0.79     | 0.82      | 0.79   | 0.78     |
|                      | Stacking Classifier | Bukalapak | 0.82     | 0.84      | 0.82   | 0.81     |
|                      |                   | Shopee     | 1.00     | 1.00      | 0.99   | 1.00     |
|                      |                   | Lazada     | 0.92     | 0.92      | 0.93   | 0.92     |
|                      |                   | Tokopedia  | 0.81     | 0.82      | 0.81   | 0.81     |
