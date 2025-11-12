# Machine Translation
Repositori ini berisi implementasi **Neural Machine Translation (NMT)** berbasis **RNN Seq2Seq**, yang membandingkan model **tanpa attention** dan **dengan attention mechanism**.

📘 **Author:** Herlina – Universitas Gadjah Mada  
🔗 [https://github.com/herlinalim-ugm/Machine-Translation](https://github.com/herlinalim-ugm/Machine-Translation)

## 📂 Struktur Proyek
```text
Machine-Translation/
│
├── NMT_Tanpa_Attention.ipynb      # Implementasi model NMT dasar tanpa attention
├── NMT_Dengan_Attention.ipynb     # Implementasi model NMT dengan mekanisme attention
│
├── train.csv                      # Dataset pelatihan
├── valid.csv                      # Dataset validasi
├── test.csv                       # Dataset pengujian
│
└── README.md                      # Dokumentasi proyek

📝 Keterangan
NMT_Tanpa_Attention.ipynb: Model encoder–decoder RNN klasik tanpa attention.
NMT_Dengan_Attention.ipynb: Model dengan penambahan mekanisme attention untuk hasil terjemahan yang lebih kontekstual.
Dataset (train/valid/test): Berisi pasangan kalimat sumber dan target untuk pelatihan, validasi, dan pengujian model.
README.md: Penjelasan struktur dan isi repositori.
