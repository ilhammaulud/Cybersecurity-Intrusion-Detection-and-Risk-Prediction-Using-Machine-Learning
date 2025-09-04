# Cybersecurity Intrusion Detection and Risk Prediction Using Machine Learning

## Repository Outline

1. README.md - Penjelasan gambaran umum project
2. P1M2_Ilham_Maulud.ipynb - notebook yang berisi pengolahan data dengan python
3. P1M2_Ilham_Maulud_inf.ipynb - Notebook yang berisi percobaan model dengan data inference
4. url.txt - Berisi link streamlit
5. dataset.csv - Berisi dataset yang digunakan
6. folder deployment - Berisi file yang di gunakan untuk deployment
7. XGBoost_best_model.joblib - Model yang sudah di save


## Problem Background
Dalam era digital saat ini, serangan siber menjadi ancaman serius bagi keamanan data dan jaringan organisasi. Banyak sistem masih mengandalkan metode deteksi tradisional yang kurang efektif dalam mengenali pola serangan baru. Project ini bertujuan untuk membangun model prediksi risiko intrusi siber menggunakan data transaksi jaringan, sehingga dapat mengidentifikasi potensi serangan secara otomatis dan akurat. Dengan model ini, organisasi dapat meningkatkan keamanan jaringan dan mengurangi kerugian akibat insiden siber.

## Project Output
Project ini menghasilkan model machine learning untuk deteksi risiko intrusi siber. Model ini mampu mengklasifikasikan aktivitas jaringan menjadi aman atau berisiko dengan akurasi tinggi setelah melalui proses preprocessing, scaling, dan hyperparameter tuning. Output lain dari project ini termasuk laporan evaluasi performa model (precision, recall, f1-score, dan accuracy) serta rekomendasi strategi mitigasi berdasarkan hasil prediksi.

## Data
Data yang digunakan berasal dari dataset Cybersecurity Intrusion Detection yang berisi informasi aktivitas jaringan untuk mendeteksi serangan siber. Dataset ini memiliki 10 kolom fitur yang mencakup informasi numerik dan kategorikal seperti session_id, network_packet_size, protocol_type, login_attempts, dan lainnya. Dataset terdiri dari 9.537 baris dan 10 kolom, dengan beberapa fitur kategorikal yang telah ditangani menggunakan One-Hot Encoding dan fitur numerik yang telah di-scale untuk meningkatkan performa model. Secara keseluruhan, data siap digunakan untuk training dan evaluasi model klasifikasi risiko intrusi.

## Method
Metode yang digunakan pada project ini adalah Supervised Learning untuk klasifikasi risiko intrusi siber. Prosesnya meliputi preprocessing data, yaitu menangani kolom numerik dengan scaling dan kolom kategorikal dengan One-Hot Encoding, agar data siap dimasukkan ke dalam model. Beberapa algoritma classification diuji, termasuk Decision Tree, Random Forest, Gradient Boosting, KNN, SVM, dan XGBoost. Model dievaluasi menggunakan Cross Validation untuk mendapatkan rata-rata akurasi dan standar deviasi, sehingga dapat memilih model terbaik sebelum dilakukan hyperparameter tuning.

## Stacks
Project ini menggunakan bahasa pemrograman Python dengan beberapa library dan tools utama untuk analisis data dan machine learning, antara lain:

1. Pandas dan NumPy: manipulasi data dan komputasi numerik.

2. Scikit-Learn: preprocessing data, pipeline, model machine learning, evaluasi, dan cross-validation.

3. XGBoost: implementasi model boosting untuk klasifikasi.

4. Matplotlib, Seaborn, dan Plotly: visualisasi data dan hasil analisis.

5. Streamlit: membangun aplikasi web interaktif untuk menampilkan hasil model dan dashboard.

Selain itu, project ini juga menggunakan pipelines dan ColumnTransformer untuk memudahkan preprocessing dan integrasi dengan berbagai model machine learning.

## Reference
Berikut beberapa referensi dan link pendukung yang digunakan dalam project ini:

Dataset Cybersecurity Intrusion Detection: https://www.kaggle.com/datasets/dnkumars/cybersecurity-intrusion-detection-dataset

Dokumentasi Streamlit (untuk deployment aplikasi web interaktif): https://docs.streamlit.io/

Dokumentasi Scikit-Learn (untuk machine learning & preprocessing): https://scikit-learn.org/stable/documentation.html

XGBoost Documentation: https://xgboost.readthedocs.io/

Referensi visualisasi dan dashboard interaktif: Plotly https://plotly.com/python/

Link ini digunakan sebagai acuan dalam pemodelan, evaluasi, visualisasi, dan deployment project.

---

**Referensi tambahan:**
- [Basic Writing and Syntax on Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Contoh readme](https://github.com/fahmimnalfrzki/Swift-XRT-Automation)
- [Another example](https://github.com/sanggusti/final_bangkit) (**Must read**)
- [Additional reference](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)