# UTS Machine Learning — Linear Regression & Logistic Regression

## Identitas Mahasiswa
- Nama: Muhammad Ridwan Arifin
- NIM: 241011400675
- Kelas: Reg B

## Isi Repository
- `tugas_UTS.ipynb`: notebook tugas yang telah dikerjakan dan dijalankan dengan output.
- `Ads_Data.csv`: dataset regresi linear.
- `Email_Data.csv`: dataset klasifikasi spam.

## Ringkasan Hasil

### Bagian A — Linear Regression
- Intercept: 29.7743
- Koefisien BiayaIklan: 9.0187
- Persamaan: ŷ = 29.7743 + 9.0187 × BiayaIklan
- RMSE training: 4.5698
- R² training: 0.9651
- RMSE testing: 10.1434
- R² testing: 0.8523
- Prediksi penjualan: biaya iklan 4.5 juta → 70.359 juta; 7 juta → 92.905 juta; 12 juta → 137.999 juta.

### Bagian B — Logistic Regression
- Intercept: -8.39097
- Koefisien JumlahLink: 0.78040
- Koefisien KataPromo: 0.72696
- Accuracy testing: 0.9333
- Precision: 0.8000
- Recall: 1.0000
- F1-score: 0.8889
- Threshold yang dipilih: 0.5

## Catatan
Model dan metrik utama diimplementasikan manual menggunakan NumPy. scikit-learn hanya digunakan pada bagian bonus sebagai pembanding. Learning rate 0.1 pada eksperimen Gradient Descent Linear Regression mengalami divergensi/overflow; hasil tersebut ditampilkan dan dijelaskan sesuai instruksi soal.
