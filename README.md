 Capstone Project: Clustering dan Insight Data Tanaman Padi Sumatera

 Project Overview
Proyek ini menganalisis data produksi tanaman padi di beberapa provinsi di Sumatera menggunakan AI Granite Model dari IBM untuk:
- Menemukan pola distribusi & korelasi data.
- Memberikan insight & temuan berbasis LLM.
- Merekomendasikan strategi peningkatan produksi.

 Raw Dataset
-Nama File: `Data_Tanaman_Padi_Sumatera_version_1.csv`
- Ukuran: 224 baris, 7 kolom (Provinsi, Tahun, Produksi, Luas Panen, Curah hujan, Kelembapan, Suhu rata-rata)

 Tools
- 📁 Google Colab Notebook
- 🤖 IBM Granite Model** (via Replicate API)
- 📊 LangChain + Python (Pandas, Matplotlib, Seaborn)

 Analytical Result
- Distribusi fitur menunjukkan variasi produksi signifikan antar wilayah.
- Korelasi positif antara luas panen & hasil produksi.
- Curah hujan & kelembapan berkorelasi sedang dengan produksi.

 Insight & Findings
Insight detail dihasilkan menggunakan IBM Granite Model:
- Model mendeskripsikan pola distribusi data.
- Memberikan saran segmentasi data & potensi cluster.
- Menyarankan monitoring suhu & curah hujan musiman.

 Conclusion & Recommendations
- Tingkatkan pengelolaan air & irigasi.
- Rekomendasi penjadwalan tanam optimal per provinsi.
- Tingkatkan akurasi data lapangan untuk input AI di masa depan.

 AI Support Explanation
- **Granite Model** digunakan untuk menganalisis ringkasan statistik & visualisasi.
- Prompt disusun otomatis berdasarkan output `describe()`, histogram, dan heatmap.
- Jawaban LLM membantu penulis menarik insight praktis & saran kebijakan.

 How to Run
1. Upload CSV ke Google Colab.
2. Jalankan notebook step-by-step.
3. Masukkan `Replicate API Token` via `userdata`.
4. Lihat insight di output cell.

---
