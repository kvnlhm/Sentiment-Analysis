# Capstone Project: Analisis Sentimen Ulasan IMDB dengan IBM Granite

Proyek ini merupakan bagian dari Capstone Project yang berfokus pada analisis sentimen ulasan film dari dataset IMDB. Dengan memanfaatkan kekuatan Large Language Model (LLM) IBM Granite melalui API Replicate, proyek ini bertujuan untuk mengklasifikasikan sentimen ulasan (positif atau negatif), mengevaluasi akurasi model, dan mendapatkan wawasan (insight) yang berarti dari data.

## 🎯 Tujuan Proyek

- **Klasifikasi Otomatis**: Mengotomatiskan proses klasifikasi sentimen pada ulasan film menggunakan model AI.
- **Evaluasi Kinerja**: Mengevaluasi akurasi model IBM Granite dengan membandingkan hasil klasifikasi otomatis dengan label sentimen asli.
- **Visualisasi Data**: Menyajikan hasil analisis sentimen dan matriks evaluasi dalam bentuk visual untuk pemahaman yang lebih baik.
- **Wawasan Interaktif**: Memungkinkan interaksi langsung dengan model AI untuk mendapatkan wawasan tambahan tentang dataset.

## 📁 Struktur Repositori

```
.
├── Capstone_Project_Sentiment_Analysis.ipynb  # Notebook Google Colab berisi semua kode
├── IMDB.csv                                   # Dataset yang digunakan
└── README.md                                  # Dokumen penjelasan proyek
```

## 🛠️ Persyaratan

Untuk menjalankan proyek ini, Anda membutuhkan:

- **Google Colab**: Platform untuk menjalankan notebook Python.
- **Replicate API Token**: Token API dari Replicate untuk mengakses model IBM Granite. Token ini harus disimpan di Google Colab Secrets dengan nama variabel `REPLICATE_API_TOKEN`.
- **Dataset**: File `IMDB.csv` yang sudah diunggah ke lingkungan Google Colab.

## 🚀 Cara Menjalankan Kode

1. **Clone Repositori**: Buka repositori ini di GitHub dan klik tombol "Open in Colab" untuk membuka notebook secara langsung.

2. **Siapkan API Token**: Di Google Colab, klik ikon kunci (Secrets) di sisi kiri, lalu tambahkan variabel lingkungan baru dengan nama `REPLICATE_API_TOKEN` dan tempelkan token API Anda.

3. **Jalankan Setiap Sel**: Jalankan setiap sel di notebook `Capstone_Project_Sentiment_Analysis.ipynb` secara berurutan.

## 📊 Hasil dan Analisis

Kode dalam notebook akan menghasilkan beberapa output, di antaranya:

- **Laporan Klasifikasi**: Menunjukkan metrik kinerja seperti akurasi, presisi, recall, dan F1-score.
- **Matriks Kebingungan (Confusion Matrix)**: Visualisasi yang menunjukkan seberapa sering model membuat prediksi yang benar dan salah.
- **Grafik Distribusi Sentimen**: Diagram batang yang menampilkan proporsi ulasan positif, negatif, dan tidak terklasifikasi.

Output ini akan memberikan wawasan mendalam tentang seberapa efektif model IBM Granite dalam mengklasifikasikan sentimen pada data ulasan.

## 📝 Wawasan & Temuan

[Bagian ini dapat Anda isi setelah menjalankan kode. Contoh:]

- Model mencapai akurasi sebesar XX% pada sampel data.
- Sebagian besar kesalahan klasifikasi terjadi pada ulasan yang mengandung sarkasme atau sentimen campuran.
- Analisis menunjukkan bahwa XX% dari ulasan yang dianalisis memiliki sentimen positif, sementara YY% bersifat negatif.

## 💡 Rekomendasi

[Bagian ini dapat Anda isi berdasarkan wawasan yang Anda temukan. Contoh:]

- **Peningkatan Model**: Melakukan penyempurnaan (refining) prompt dengan menambahkan contoh ulasan yang ambigu untuk melatih model agar lebih baik dalam menangani kasus-kasus sulit.
- **Strategi Bisnis**: Menggunakan hasil analisis untuk mengidentifikasi aspek-aspek film yang paling disukai atau tidak disukai oleh penonton, yang dapat menjadi masukan untuk produksi film di masa depan.

## 🔧 Teknologi yang Digunakan

- **IBM Granite**: Large Language Model untuk analisis sentimen
- **Replicate API**: Platform untuk mengakses model IBM Granite
- **Python**: Bahasa pemrograman utama
- **Google Colab**: Environment untuk menjalankan notebook
- **Pandas**: Untuk manipulasi data
- **Matplotlib/Seaborn**: Untuk visualisasi data
- **Scikit-learn**: Untuk evaluasi model

## 📈 Metrik Evaluasi

Proyek ini menggunakan beberapa metrik untuk mengevaluasi kinerja model:

- **Accuracy**: Proporsi prediksi yang benar
- **Precision**: Proporsi prediksi positif yang benar
- **Recall**: Proporsi kasus positif yang teridentifikasi dengan benar
- **F1-Score**: Harmonic mean dari precision dan recall

## 🤝 Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan:

1. Fork repositori ini
2. Buat branch fitur baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan Anda (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

**Catatan**: Proyek ini dibuat sebagai bagian dari Capstone Project dan bertujuan untuk demonstrasi kemampuan analisis sentimen menggunakan IBM Granite LLM.
