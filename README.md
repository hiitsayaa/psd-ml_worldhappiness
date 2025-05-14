# Prediksi Tingkat Kebahagiaan Negara dengan Linear Regression & Random Forest

Notebook ini berisi analisis perbandingan dua algoritma machine learning, yaitu **Linear Regression** dan **Random Forest Regression**, untuk memprediksi **Skor Kebahagiaan** suatu negara berdasarkan indikator dari dataset **World Happiness Report 2019**.

## Dataset
Dataset diambil dari [Kaggle - World Happiness Report](https://www.kaggle.com). 
Dataset ini memuat berbagai indikator dari masing-masing negara, seperti:
- GDP per capita  
- Social support  
- Healthy life expectancy  
- Freedom to make life choices  
- Generosity  
- Perceptions of corruption  

Variabel target yang diprediksi adalah **Score** yang merepresentasikan tingkat kebahagiaan suatu negara.

## Metode yang Digunakan

- **Linear Regression**: Metode regresi sederhana yang mengasumsikan hubungan linear antara fitur input dan target.
- **Random Forest Regression**: Metode ensemble yang menggunakan banyak pohon keputusan untuk menghasilkan prediksi yang lebih akurat dan stabil.

## Alur Pengerjaan
1. Data loading and preprocessing
2. Feature selection
3. Train-test split
4. Model training: Linear Regression & Random Forest
5. Evaluasi model menggunakan MSE dan R² Score
6. Visualisasi hasil prediksi menggunakan scatter plot
