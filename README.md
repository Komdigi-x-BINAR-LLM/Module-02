# Hands-on Komdigi: Modul 2 - Eksplorasi Konsep LLM

Selamat datang di *repository hands-on* untuk **Modul 2 ("Arsitektur dan Komponen Inti pada LLM")** dari program AI Engineer Komdigi!

**Tujuan:**
Repository ini berisi *notebook* Jupyter interaktif (`1_Explorasi_Tokenization_Sampling.ipynb`) yang dirancang untuk membantu Anda **memvisualisasikan** dan **bereksperimen** dengan konsep-konsep teori kunci dari Modul 2, yaitu:
* **Tokenization:** Melihat bagaimana teks dipecah menjadi *subword tokens* menggunakan *tokenizer* Hugging Face.
* **Sampling:** Mengamati efek berbagai parameter (*Greedy Search*, *Temperature*, *Top-p*) pada teks yang dihasilkan oleh model LLM kecil.

**Prasyarat:**
* Pemahaman dasar bahasa pemrograman Python.
* Akses ke materi Modul 2.

---

## Cara Menjalankan Notebook (`1_Explorasi_Tokenization_Sampling.ipynb`)

Anda bisa menjalankan *notebook* ini menggunakan salah satu cara berikut:

### Google Colaboratory (Rekomendasi Cepat)

Klik *badge* di bawah untuk membuka *notebook* langsung di Google Colab (tidak perlu instalasi lokal).
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](<https://colab.research.google.com/drive/1g7Lj8qWHoBHapE29qQ-kFp92ZjakkciJ?usp=sharing>)

**Catatan Colab:**
* Jalankan sel pertama yang berisi `!pip install transformers torch` untuk instalasi.
* Pilih *Runtime* GPU (`Runtime > Change runtime type > GPU`) jika ingin mencoba model generatif yang sedikit lebih besar di bagian *Sampling*.

---

---

Selamat bereksperimen dengan konsep dasar LLM!
