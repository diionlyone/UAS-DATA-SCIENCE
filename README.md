# Adi Subhandi Subiyono - UAS-DATA-SCIENCE
Adi Subhandi Subiyono 227006516087

# UAS Data Science — Prediksi Status Placement Mahasiswa

Repository ini berisi implementasi model klasifikasi untuk memprediksi status penempatan kerja mahasiswa (**Placed / Not Placed**) menggunakan **Regularized Logistic Regression** dengan pipeline preprocessing.

## Tujuan Analisis
1. Membangun model klasifikasi untuk memprediksi status placement.
2. Menginterpretasikan kontribusi variabel menggunakan koefisien dan *odds ratio*.
3. Mengevaluasi performa model (ROC-AUC, PR-AUC, F1-score, confusion matrix) dengan skema validasi stratified cross-validation.
4. Menyusun insight dan rekomendasi praktis berbasis hasil model tanpa klaim sebab-akibat.

## Struktur File
- **Notebook**: `Adi_Subhandi_...UAS_DATA_SCI....ipynb`  
  Berisi seluruh proses (EDA → preprocessing → tuning → evaluasi → interpretasi → rekomendasi).
- **Dataset**: `Campus Recruitment.csv`  
- **Laporan**: `Adi_Subhandi_...UAS_DATA_SCI....docx`  
- **README.md**: ringkasan proyek.

## Cara Menjalankan
### Opsi 1 — Google Colab
1. Upload notebook ke Colab atau buka notebook dari GitHub.
2. Pastikan file `Campus Recruitment.csv` tersedia (upload ke Colab atau akses dari repo).
3. Jalankan cell dari atas ke bawah.

### Opsi 2 — Local (Jupyter)
1. Install dependency:
   - `pandas`, `numpy`, `matplotlib`, `scikit-learn`
2. Jalankan notebook menggunakan Jupyter Notebook / JupyterLab.

## Catatan Penting
- Kolom **Gaji** tidak digunakan sebagai fitur karena berpotensi *data leakage* (nilai gaji umumnya tersedia setelah placement terjadi).
- Interpretasi model bersifat asosiasi statistik, bukan hubungan sebab-akibat.

## Link Cepat
- Notebook: (klik file notebook di repo ini)
- Laporan: (klik file .docx di repo ini)
