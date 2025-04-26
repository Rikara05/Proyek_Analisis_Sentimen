# Proyek Analisis Sentimen Ulasan Shopee

Proyek ini bertujuan untuk melakukan analisis sentimen terhadap data ulasan produk dari Shopee menggunakan teknik Web Scraping, Pemrosesan Teks, dan Machine Learning.

---

## 📑 Daftar Isi
- [Deskripsi Proyek](#deskripsi-proyek)
- [Extended Description](#extended-description)
- [Struktur Folder dan File](#struktur-folder-dan-file)
- [Cara Menjalankan Proyek](#cara-menjalankan-proyek)

---

## 📌 Deskripsi Proyek

- Mengambil data ulasan produk dari Shopee.
- Melakukan pra-pemrosesan teks seperti cleaning, tokenization, dan stopwords removal.
- Melatih model machine learning untuk mengklasifikasikan sentimen ulasan menjadi **positif** atau **negatif**.

---

## 📚 Extended Description

### Latar Belakang

Dalam era digital saat ini, ulasan konsumen terhadap produk online memiliki pengaruh besar terhadap keputusan pembelian. Analisis sentimen terhadap ulasan ini menjadi penting untuk memahami opini pelanggan secara otomatis, terutama dalam platform e-commerce seperti Shopee.

Dengan menggunakan teknik Web Scraping dan Machine Learning, proyek ini bertujuan untuk mengotomatisasi proses pengumpulan data dan mengkategorikan sentimen pengguna terhadap produk-produk yang mereka beli.

### Tujuan Proyek

- Mengumpulkan data ulasan produk dari Shopee secara otomatis.
- Melakukan analisis sentimen terhadap ulasan yang telah dikumpulkan.
- Membangun model klasifikasi yang dapat memprediksi sentimen baru berdasarkan data ulasan.

### Manfaat Proyek

- Memberikan insight yang berguna bagi penjual dalam memahami kepuasan pelanggan.
- Membantu pengembangan sistem rekomendasi produk berdasarkan sentimen ulasan.
- Menjadi dasar untuk penelitian lebih lanjut di bidang pemrosesan bahasa alami (NLP).

### Alur Kerja Proyek

1. **Data Collection** — Melakukan scraping data ulasan dari website Shopee.
2. **Data Preprocessing** — Membersihkan data teks, menghapus karakter khusus, dan menghilangkan stopwords.
3. **Model Building** — Melatih model Machine Learning (seperti Naive Bayes, SVM, atau Neural Network) untuk klasifikasi sentimen.
4. **Evaluation** — Mengevaluasi performa model menggunakan metrik seperti akurasi, precision, recall, dan F1-score.
5. **Deployment (Opsional)** — Mengembangkan API atau aplikasi sederhana untuk mengklasifikasikan ulasan secara real-time.

---

## 📂 Struktur Folder dan File

| File/Folder               | Deskripsi                                                |
|----------------------------|-----------------------------------------------------------|
| `Scraping.ipynb`           | Notebook untuk scraping ulasan dari Shopee.               |
| `pelatihan_model.ipynb`    | Notebook untuk preprocessing data dan pelatihan model.    |
| `shoppe_reviews.csv`       | Dataset hasil scraping dari Shopee.                       |
| `requirements.txt`         | Daftar library/dependencies yang digunakan.               |

---

## ⚙️ Cara Menjalankan Proyek

1. **Clone repository ini**:
   ```bash
   git clone https://github.com/Rikara05/Proyek_Analisis_Sentimen.git
   cd Proyek_Analisis_Sentimen
