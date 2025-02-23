## ML-Breast_Cancer-SVM

# Latar Belakang
Kanker payudara adalah salah satu penyakit yang paling umum dan mematikan di dunia. Deteksi dini sangat penting untuk meningkatkan peluang kesembuhan. Dalam proyek ini, kami menggunakan algoritma Support Vector Machine (SVM) untuk menganalisis dan mengklasifikasikan tumor kanker payudara berdasarkan dataset Breast Cancer Wisconsin dari scikit-learn.
# Masalah
- Kanker payudara sulit didiagnosis secara akurat hanya berdasarkan gejala klinis.
- Kesalahan klasifikasi dapat menyebabkan keterlambatan dalam penanganan pasien.
- Diperlukan model yang andal dan efisien untuk membantu mendeteksi kanker sejak dini.
# Tujuan
- Mengembangkan model machine learning berbasis SVM untuk mengklasifikasikan tumor sebagai jinak (benign) atau ganas (malignant).
- Mengevaluasi performa model menggunakan akurasi, precision, recall, dan confusion matrix.
- Menganalisis hasil dan memberikan rekomendasi untuk peningkatan model.

# Versi Libraries yang Digunakan
- pandas v1.x → Untuk manipulasi dan analisis data
- numpy v2.x → Untuk perhitungan numerik dan operasi array
- seaborn v3.x → Untuk visualisasi data
- scikit-learn v1.x → Untuk membangun dan mengevaluasi model machine learning
- matplotlib v3.x → Untuk membuat grafik dan plot data

# Insight
Beberapa insight yang diperoleh dari hasil analisis proyek ini:

✅ Model SVM menunjukkan akurasi 98.25%, dengan precision 100% untuk malignant dan recall 95.35%.

✅ Confusion matrix menunjukkan bahwa model masih memiliki False Negatives (FN), yang berarti ada kasus tumor ganas yang salah diklasifikasikan sebagai jinak.

✅ Standarisasi fitur membantu meningkatkan performa model dengan memastikan distribusi data yang lebih baik.

# Saran
Proyek ini masih dapat dikembangkan lebih lanjut, misalnya dengan:

📌 Menyesuaikan threshold decision boundary untuk mengurangi False Negative.

📌 Menggunakan teknik ensemble models seperti Random Forest, AdaBoost, atau XGBoost untuk meningkatkan generalisasi model.

📌 Mencoba balancing data dengan teknik SMOTE atau class weighting jika dataset tidak seimbang.

Silakan eksplorasi dan kembangkan lebih lanjut! 🚀
