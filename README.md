# Performance Optimization & Efficiency Analysis: 5 Major European Football Leagues

## 1. Deskripsi Proyek
Proyek ini merupakan analisis data *end-to-end* yang mengevaluasi efisiensi dan performa pemain sepak bola di lima liga top Eropa (EPL, La Liga, Serie A, Bundesliga, Ligue 1) pada musim 2020/2021. Proyek ini bertujuan untuk mengubah data statistik mentah menjadi wawasan bisnis yang dapat ditindaklanjuti, seperti identifikasi pemain paling efisien (*high-conversion*) dan perbandingan performa antar liga.

## 2. Metodologi
Analisis dilakukan dengan alur kerja yang terstruktur:
* **Tools:** Python (Pandas, Matplotlib, Seaborn), Google Colab, Looker Studio.
* **Process:** 
    * **Data Wrangling:** Menggabungkan multi-dataset menjadi satu *master dataframe* dan melakukan pembersihan data (*data cleaning*).
    * **Feature Engineering:** Membuat metrik baru seperti *Conversion Rate* (Gol/Tembakan) untuk mengukur efisiensi individu.
    * **SQL Logic Simulation:** Menerapkan konsep *Window Functions* (seperti `RANK()`) melalui Pandas untuk segmentasi performa pemain.

## 3. Insight Utama (Contoh Hasil Analisis)
Berdasarkan hasil analisis data, berikut adalah temuan kuncinya:
* **Efisiensi vs Volume:** Terdapat korelasi yang menarik antara jumlah tembakan dan tingkat konversi gol. Pemain dengan volume tembakan tinggi tidak selalu memiliki efisiensi konversi tertinggi, yang mengindikasikan perbedaan kualitas dalam pengambilan keputusan di depan gawang.
* **Dominasi Liga:** Hasil visualisasi menunjukkan perbedaan karakteristik gaya bermain dan efisiensi rata-rata antar liga, yang memberikan gambaran mengenai intensitas kompetisi yang berbeda.
