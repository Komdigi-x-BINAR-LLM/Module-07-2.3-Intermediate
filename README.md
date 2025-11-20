# Module-07-2.3-Intermediate-
Finetuning LLM

# Hands-on Komdigi: Modul 2.3 - Fine-Tuning Llama-3 dengan Unsloth

Selamat datang di *repository hands-on* untuk **Modul 2.3 (Intermediate): Fine-Tuning LLM**!

**Tujuan:**
Praktikum ini adalah puncak dari pembelajaran teknik efisiensi. Anda akan menggunakan *library* **Unsloth** untuk melakukan *Fine-Tuning* pada model **Llama-3-8B** menggunakan teknik **QLoRA** di Google Colab gratis (GPU T4).

**Materi Praktik:**
1.  **Setup Unsloth (2.3.6):** Menginstal dan memuat model Llama-3 dalam format 4-bit super cepat.
2.  **Data Preparation (2.3.5):** Memuat dataset format Alpaca, menerapkan **Chat Template**, dan memvisualisasikan distribusi data.
3.  **Training (2.3.2 & 2.3.6):** Melatih model menggunakan LoRA adapter dan melihat penurunan *loss*.
4.  **Inference:** Menguji model sebelum dan sesudah training untuk melihat perubahan perilaku.

**Prasyarat:**
* Akun Google (untuk Google Colab).
* Pemahaman dasar Python.
* **PENTING:** Pastikan menggunakan Runtime GPU di Colab.

---

## Cara Menjalankan Notebook

Klik *badge* di bawah untuk membuka *notebook* langsung di Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1SGs1gz8EAGdJPoeofvZRoyy4z7dQNSFk?usp=sharing)

**Hasil yang Diharapkan:**
Anda akan melihat model Llama-3 yang awalnya menjawab secara umum, menjadi bisa mengikuti instruksi spesifik dari dataset Alpaca dengan gaya yang lebih terarah, hanya dalam waktu pelatihan kurang dari 30 menit.

Selamat mencoba kekuatan *fine-tuning* modern!
