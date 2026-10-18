# Klasifikasi Kedalaman Gempa Bumi di Indonesia

Proyek AI Fundamentals Coding Challenge. Memprediksi kategori kedalaman gempa
(Dangkal / Menengah / Dalam) dari lokasi (lat, lon) dan magnitudo.

## Dataset
Earthquakes in Indonesia (Kaggle): <https://www.kaggle.com/datasets/kekavigi/earthquakes-in-indonesia>

## Hasil ringkas
| Model | Akurasi Test | Macro F1 |
|---|---|---|
| Logistic Regression | 0,769 | 0,293 |
| Random Forest | 0,865 | 0,753 |

Akurasi tebakan acuan (selalu "Dangkal"): 0,769.

## Cara menjalankan
Buka notebook di Google Colab, unggah dataset, lalu jalankan sel berurutan.
Untuk Challenge 4, simpan `GEMINI_API_KEY` di Colab Secrets.

## Batasan
Model ini bukan prediksi kapan gempa terjadi dan bukan pengganti informasi resmi BMKG.
