# Capstone Project: Riset Pasar untuk Film Indonesia di Netflix

## Project Overview
Proyek ini bertujuan untuk menganalisis katalog konten Indonesia di platform Netflix (berdasarkan data hingga 2022) untuk mengidentifikasi tren, pola, dan celah pasar. Tujuannya adalah untuk memberikan rekomendasi strategis yang actionable bagi Production House di Indonesia yang ingin menembus pasar platform streaming global.

## Raw Dataset Link
Dataset yang digunakan adalah "Netflix Movies and TV Shows" yang diunduh langsung dari Kaggle menggunakan API.
https://www.kaggle.com/datasets/shivamb/netflix-shows

## Insight & Findings
* **Dominasi Genre:** Ditemukan bahwa genre **Horor** dan **Drama** merupakan pilar utama dari konten Indonesia yang tersedia di Netflix, menunjukkan adanya permintaan yang kuat untuk tipe cerita ini.
* **Aktor Kunci:** Aktor tertentu seperti **Reza Rahadian** dan **Maudy Koesneadi** memiliki frekuensi penampilan tertinggi, menandakan nilai jual mereka di platform ini.
* **Celah Pasar:** Terdapat peluang signifikan pada genre yang masih jarang, terutama **Komedi Keluarga** dan **Sci-Fi**, yang dapat dimanfaatkan oleh Production House untuk menawarkan konten yang unik dan berbeda.

## AI Support Explanation
AI digunakan dalam proyek ini untuk memperkaya analisis kualitatif. Secara spesifik, model **Zero-Shot Text Classification** (`facebook/bart-large-mnli`) dari library Hugging Face digunakan untuk menganalisis deskripsi plot film. AI membantu mengkategorikan film ke dalam sub-genre yang lebih spesifik (contoh: 'horor folklor' vs 'horor psikologis'), memberikan pemahaman yang lebih dalam mengenai nuansa narasi yang berhasil di platform.

## Conclusion & Recommendations
* **Rekomendasi Aman:** Memproduksi genre Horor atau Drama dengan aktor yang sudah memiliki rekam jejak di Netflix.
* **Rekomendasi Terobosan:** Mengisi kekosongan pasar dengan memproduksi genre Komedi Keluarga atau Sci-Fi berkualitas.
* **Rekomendasi Strategis:** Menekankan narasi unik lokal (seperti horor folklor) sebagai nilai jual utama di pasar internasional.
