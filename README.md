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

### Opsi A: Google Colaboratory (Rekomendasi Cepat)

Klik *badge* di bawah untuk membuka *notebook* langsung di Google Colab (tidak perlu instalasi lokal).
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](<URL_NOTEBOOK_1_DI_GITHUB_RAW>)

**Catatan Colab:**
* Jalankan sel pertama yang berisi `!pip install transformers torch` untuk instalasi.
* Pilih *Runtime* GPU (`Runtime > Change runtime type > GPU`) jika ingin mencoba model generatif yang sedikit lebih besar di bagian *Sampling*.

*(Ganti `<URL_NOTEBOOK_1_DI_GITHUB_RAW>` dengan URL *raw* file `1_Explorasi_Tokenization_Sampling.ipynb` di GitHub Anda)*

---

### Opsi B: GitHub Codespaces / VS Code Lokal

1.  **Clone Repository Induk:** (Jika belum)
    ```bash
    git clone <URL_REPO_INDUK_ANDA>
    cd <NAMA_FOLDER_REPO>
    ```
2.  **(Opsional) Buat & Aktifkan Virtual Environment:**
    ```bash
    python -m venv .venv
    # Aktivasi (Linux/macOS): source .venv/bin/activate
    # Aktivasi (Windows): .venv\Scripts\activate
    ```
3.  **Install Dependensi:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Jalankan Notebook:**
    * Buka folder repo di VS Code / Codespaces.
    * Navigasi ke `notebooks/1_Explorasi_Tokenization_Sampling.ipynb`.
    * Pilih *kernel* Python yang benar (dari *virtual env* jika dibuat).
    * Jalankan sel-sel kode.

---

### Opsi C: Jupyter Notebook / Jupyter Lab Lokal

1.  **Clone Repository Induk:** (Sama seperti Opsi B, langkah 1)
2.  **Buat & Aktifkan Virtual Environment:** (Sama seperti Opsi B, langkah 2)
3.  **Install Dependensi:** (Sama seperti Opsi B, langkah 3)
4.  **Jalankan Jupyter:** Dari terminal (dengan *virtual env* aktif) di *root* folder repo, jalankan `jupyter notebook` atau `jupyter lab`.
5.  Navigasi ke `notebooks/1_Explorasi_Tokenization_Sampling.ipynb` dan buka.

---

Selamat bereksperimen dengan konsep dasar LLM!
