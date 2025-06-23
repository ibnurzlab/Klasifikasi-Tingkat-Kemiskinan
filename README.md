# Klasifikasi-Tingkat-Kemiskinan
Proyek ini merupakan analisis data dan pemodelan machine learning untuk mengeksplorasi hubungan indikator sosial-ekonomi di Indonesia. Dataset berisi data Persentase Penduduk Miskin (P0) dan Rata-rata Lama Sekolah Penduduk 15+ (Tahun) per Kabupaten/Kota, serta beberapa fitur lain.

# 📊 Analisis Sosial-Ekonomi dan Klastering Kabupaten/Kota

Proyek ini merupakan analisis data dan pemodelan machine learning untuk mengeksplorasi hubungan indikator sosial-ekonomi di Indonesia, menggunakan data **Persentase Penduduk Miskin (P0)** dan **Rata-rata Lama Sekolah Penduduk 15+ (Tahun)** per Kabupaten/Kota.

---

## 🎯 Tujuan
- **Preprocessing Data**: Membersihkan dan menyiapkan data (menangani missing values dan konversi tipe data).
- **Exploratory Data Analysis (EDA)**: Menganalisis distribusi dan hubungan antar fitur.
- **Klastering & Klasifikasi**:
  - 🧮 **K-Means** untuk klastering berbasis centroid.
  - 🌐 **DBSCAN** untuk klastering berbasis densitas.
  - 📈 **Gaussian Mixture Models (GMM)** untuk klastering probabilistik.
  - 🎯 **Support Vector Machines (SVM)** untuk klasifikasi fitur.
  - 🌳 **Random Forest** sebagai baseline klasifikasi.

---

## 🔍 Insight
Pada tahap EDA, ditemukan hubungan erat antara **persentase penduduk miskin** dan **rata-rata lama sekolah**. Hubungan ini terlihat cukup jelas untuk membentuk klaster-klaster yang bermakna, sehingga proyek ini berfokus pada penerapan berbagai algoritma klastering dan klasifikasi untuk memisahkan data menjadi segmen yang lebih informatif.

---

## 🛠️ Tools & Libraries
- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Scikit-learn** untuk klastering dan klasifikasi
- Notebook dibuat dan diuji menggunakan **Jupyter Notebook** dan **Google Colab**.

---
