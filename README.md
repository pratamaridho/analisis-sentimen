# Analisis Sentimen Ulasan Aplikasi Tokopedia Menggunakan IndoBERT

Proyek ini menganalisis sentimen ulasan pengguna terhadap aplikasi **Tokopedia** menggunakan model **IndoBERT**.  
Data dikumpulkan melalui proses *scraping* dan diklasifikasikan ke dalam tiga kategori: **positif**, **netral**, dan **negatif**.

## 🔍 Deskripsi Singkat
Model dilatih menggunakan tiga skema pelatihan yang berbeda untuk menemukan konfigurasi terbaik.  
Setiap skema diuji menggunakan data yang telah melalui proses *cleaning*, *tokenization*, dan *encoding*.

## 📊 Perbandingan Skema Pelatihan

| Skema | Pembeda Utama | Akurasi Testing |
|:------|:-----------------------------|:----------------|
| **Skema 1** | Pengaturan default (baseline training). | 96.75% |
| **Skema 2** | Optimasi *learning rate* dan *batch size* untuk hasil lebih stabil. | **97.20%** |
| **Skema 3** | Penambahan *epoch* dan *early stopping* untuk mengurangi overfitting. | 96.97% |

---

## 🚀 Model Terbaik
**Skema 2** menjadi model terbaik dengan akurasi **97.20%** pada data testing.

---

## 👨‍💻 Penulis
**Pratama Ridho**  
2025
