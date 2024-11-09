## Ringkasan

**Tujuan dari tugas ini adalah:**
- Students have GitHub accounts and repositories.
- Understand git workflow, branching strategy, and pull requests.
- Students could make code collaboration.

## Getting started

Ikuti langkah-langkah di bawah ini untuk fork, clone, dan menjalankan proyek ini di Google Colab agar memenuhi persyaratan tugas.

### Prasyarat

- Akun GitHub untuk melakukan fork dan clone repositori.
- Google Colab atau lingkungan Python lokal dengan PyTorch dan torchvision terpasang.

### Langkah-langkah Instalasi

1. **Fork dan Clone Repositori**:
   - Fork repositori publik ini: [https://github.com/Rietaros/pytorch_mnist_sample](https://github.com/Rietaros/pytorch_mnist_sample).
   - Clone repositori yang telah di-fork ke komputer lokal Anda:
     ```bash
     git clone https://github.com/YOUR_USERNAME/pytorch_mnist_sample.git
     ```
   - Masuk ke direktori proyek:
     ```bash
     cd pytorch_mnist_sample
     ```

2. **Jalankan di Google Colab**:
   - Buka file `pytorch-mnist.ipynb` di Google Colab.
   - Jalankan setiap sel untuk melatih model dan periksa hasil akurasi.

## Modifikasi Hyperparameter

Untuk mencapai akurasi lebih dari 90%, modifikasi hyperparameter `learning_rate` dan `momentum` pada `pytorch-mnist.ipynb` seperti berikut:

- **Nilai Default**:
  ```python
  learning_rate = 0.1
  momentum = 0.00003

- **Nilai Modifikasi**:
  ```python
  learning_rate = 0.001
  momentum = 0.99

### Membuat Branch Baru dan Commit Perubahan

1. **Buat Branch Baru**:
     ```bash
     git checkout -b parameter-testing
     ```
2. **Add dan Commit Perubahan**:
     ```bash
     git add pytorch-mnist.ipynb
     git commit -m "Update learning rate and momentum for optimizer"
     ```
3. **Push Perubahan**:
     ```bash
     git push origin parameter-testing
     ```

### Membuat Pull Request

1. **Buka repositori hasil fork Anda di GitHub.**
2. **Klik tombol "Compare & pull request" di sebelah branch parameter-testing.**
3. **Tambahkan judul dan deskripsi pull request Anda, lalu klik "Create pull request".**
