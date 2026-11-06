# seq2seq_NLP

> Proyek *Neural Machine Translation* (NMT) menggunakan arsitektur *Sequence-to-Sequence* (Seq2Seq) berbasis LSTM untuk penerjemahan teks Bahasa Turki ke Bahasa Inggris.

## 📌 Tentang Proyek
Proyek ini mengimplementasikan model *Encoder-Decoder* Deep Learning dari awal (*from scratch*) menggunakan TensorFlow dan Keras. Proyek ini mencakup seluruh alur kerja NLP (Natural Language Processing) standar industri, mulai dari pembersihan data teks (*data cleaning*), tokenisasi, *padding*, pembangunan arsitektur LSTM, pelatihan model (*training*), hingga pengujian inferensi penerjemahan bahasa.

## 🚀 Fitur Utama
* **Data Preprocessing & Cleaning:** Normalisasi karakter Unicode, penanganan tanda baca, konversi huruf kecil (*lowercase*), dan pembersihan teks menggunakan RegEx.
* **Tokenization & Padding:** Mengonversi teks kalimat menjadi urutan token angka dan menyamakan panjang urutan menggunakan Keras `Tokenizer` dan `pad_sequences`.
* **Seq2Seq LSTM Architecture:** Membangun model *Encoder-Decoder* dengan *Embedding Layer* (256 dimensi) dan *LSTM Layer* (512 unit) untuk memetakan urutan bahasa sumber ke bahasa target.
* **Training & Evaluation:** Pelatihan model yang stabil dengan pemantauan metrik *accuracy*, *loss*, *val_accuracy*, dan *val_loss* selama beberapa *epochs*.
* **Inference Pipeline:** Fungsi inferensi untuk menerjemahkan kalimat atau teks bahasa Turki baru ke dalam bahasa Inggris secara akurat.

## 🛠️ Teknologi & Library
* **Python**
* **TensorFlow / Keras**
* **NLTK (Natural Language Toolkit)**
* **Scikit-Learn**
* **NumPy & Pandas**
* **Google Colab**

## 📂 Struktur Repositori
```text
seq2seq_NLP/
│
├── text_seq2seq.ipynb    # Jupyter Notebook lengkap berisi pipeline NLP dan pelatihan model
└── README.md             # Dokumentasi proyek
