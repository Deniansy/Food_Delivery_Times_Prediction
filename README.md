# Prediksi Waktu Pengiriman Makanan
Aplikasi web berbasis Streamlit untuk memprediksi waktu pengiriman makanan menggunakan model Regresi Linear. Proyek ini mencakup analisis data, pemodelan, hingga deployment aplikasi interaktif dengan fitur pengumpulan feedback. ➡️[STREAMLIT APP](https://fooddeliverytimesprediction-rvrkhr38h33srjhseistq9.streamlit.app/)⬅
## Fitur Utama
* Prediksi waktu pengiriman real-time berdasarkan input (jarak, cuaca, dll.).
* Implementasi model Regresi Linear yang terbukti paling akurat untuk dataset ini.
* Fitur pengumpulan feedback dari pengguna (waktu aktual, rating, komentar).
* Penyimpanan feedback otomatis ke file Excel.
* Fasilitas download data feedback untuk analisis lebih lanjut.
## Teknologi yang Digunakan
* Analisis & Model: Python, Pandas, Scikit-learn, Joblib
* Aplikasi Web: Streamlit
* Lainnya: Matplotlib, Seaborn, NumPy, Pillow, Openpyxl
## Temuan Kunci
* Faktor Paling Berpengaruh: Jarak Pengiriman dan Tingkat Lalu Lintas adalah prediktor paling signifikan.
* Model Terbaik: Linear Regression mengungguli model kompleks (Random Forest, XGBoost) karena hubungan data yang pada dasarnya sangat linear dan stabilitasnya (tidak overfitting).
