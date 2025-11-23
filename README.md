# prediksi-tip-untuk-waiter

# Sales Prediction Project

Project ini bertujuan untuk memprediksi **total penjualan** berdasarkan budget iklan menggunakan machine learning.

## Algoritma / Metode Prediksi

1. **Data Preprocessing**
   - Membersihkan missing value
   - Normalisasi jika diperlukan

2. **Analisis Korelasi**
   - Mengecek hubungan antara `TV`, `Radio`, `Koran` dengan `Total Penjualan`

3. **Linear Regression**
   - Input: `TV`, `Radio`, `Koran`
   - Output: `Total Penjualan`
   - Model: `y = β0 + β1*TV + β2*Radio + β3*Koran`

4. **Evaluasi Model**
   - Menggunakan **RMSE** dan **R² score**
   - Plot prediksi vs aktual untuk validasi
