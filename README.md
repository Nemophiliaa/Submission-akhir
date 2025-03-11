# Submission-akhir

# Proyek Klasifikasi Gambar

## Deskripsi
Proyek ini bertujuan untuk mengklasifikasikan gambar menggunakan model deep learning. Dataset yang digunakan berisi gambar-gambar anjing dan kucing.

## Struktur Direktori
submission/ ├───tfjs_model │ ├───group1-shard1of1.bin │ └───model.json ├───tflite │ ├───model.tflite │ └───label.txt ├───saved_model │ ├───saved_model.pb │ └───variables ├───notebook.ipynb ├───README.md └───requirements.txt


## Instalasi
Untuk menjalankan proyek ini, Anda perlu menginstal library yang diperlukan dengan menggunakan file `requirements.txt`:

## Penggunaan
Berikut adalah langkah-langkah untuk menjalankan proyek ini:
1. Buka notebook `notebook.ipynb`.
2. Jalankan setiap cell untuk melatih model dan menyimpan hasil dalam format SavedModel, TFJS, dan TFLite.
3. Gunakan file model yang telah disimpan untuk melakukan inferensi pada data baru.
