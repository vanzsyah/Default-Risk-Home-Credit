# Analisis Risiko Kredit dengan Machine Learning

Proyek ini bertujuan untuk memprediksi risiko gagal bayar kredit menggunakan teknik machine learning. Dengan memanfaatkan dataset aplikasi kredit, proyek ini melakukan eksplorasi data (EDA), pra-pemrosesan data, pelatihan model (Logistic Regression dan LightGBM), serta memberikan rekomendasi bisnis berdasarkan hasil analisis.

## Fitur Utama
- **Pemuatan Data**: Membaca dataset dari file CSV.
- **Eksplorasi Data (EDA)**: Visualisasi distribusi target, nilai hilang, dan korelasi antar fitur.
- **Penanganan Nilai Hilang**: Mengisi nilai hilang dengan median untuk fitur numerik.
- **Encoding Fitur Kategorikal**: Mengubah fitur kategorikal menjadi numerik menggunakan Label Encoding.
- **Standarisasi Fitur**: Menormalkan fitur numerik dengan StandardScaler.
- **Pelatihan Model**: Membandingkan performa Logistic Regression dan LightGBM.
- **Analisis Hasil**: Menghasilkan rekomendasi bisnis berdasarkan fitur penting dan performa model.

## Instalasi
1. Pastikan Python 3.x dan pip sudah terinstall.
2. Clone repositori ini:
   ```bash
   git clone https://github.com/vanzsyah/Default-Risk-Home-Credit.git
   cd Default-Risk-Home-Credit