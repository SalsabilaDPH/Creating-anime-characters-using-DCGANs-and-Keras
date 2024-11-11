# Creating anime characters using Deep Convolutional Generative Adversarial Networks (DCGANs) and Keras

<div align="center">
  <img src="https://img.shields.io/badge/TensorFlow-2.9+-blue?logo=tensorflow&logoColor=white" alt="TensorFlow Badge" />
  <img src="https://img.shields.io/badge/Keras-2.9+-purple?logo=keras&logoColor=white" alt="Keras Badge" />
  <img src="https://img.shields.io/badge/Python-3.8+-green?logo=python&logoColor=white" alt="Python Badge" />
  <img src="https://img.shields.io/badge/NumPy-1.21+-red?logo=numpy&logoColor=white" alt="NumPy Badge" />
  <img src="https://img.shields.io/badge/Matplotlib-3.5+-blue?logo=matplotlib&logoColor=white" alt="Matplotlib Badge" />
  <img src="https://img.shields.io/badge/Pandas-1.3.4+-orange?logo=pandas&logoColor=white" alt="Pandas Badge" />
  <img src="https://img.shields.io/badge/Seaborn-0.9.0+-purple?logo=seaborn&logoColor=white" alt="Seaborn Badge" />
  <img src="https://img.shields.io/badge/scikit--learn-0.20.1+-yellow?logo=scikit-learn&logoColor=white" alt="Scikit-learn Badge" />
</div>

## Dokumentasi 📄

Proyek ini bertujuan untuk mengimplementasikan **Deep Convolutional Generative Adversarial Networks (DCGANs)** untuk menghasilkan gambar baru berdasarkan dataset yang diberikan. **DCGAN** adalah jenis **GAN** yang menggunakan arsitektur convolutional untuk meningkatkan kualitas gambar yang dihasilkan. **DCGAN** adalah jenis **Generative Adversarial Network (GAN)** yang menggunakan arsitektur **convolutional neural networks (CNN)** dalam generator dan diskriminator.

Proyek ini menjelaskan cara menggunakan **DCGANs** untuk menghasilkan karakter anime secara otomatis. Ini merupakan solusi bagi pengembang game yang ingin menciptakan karakter unik untuk jutaan pemain tanpa harus menggambar setiap karakter secara manual.

### Tujuan 📌
- Memahami formulasi asli **GANs** dan dua jaringan yang dilatih secara terpisah: Generator dan Discriminator.
- Mengimplementasikan **GANs** pada dataset simulasi dan nyata.
- Mengaplikasikan **DCGANs** pada dataset karakter anime.
- Memahami proses pelatihan **DCGANs**.
- Menghasilkan gambar menggunakan **DCGAN**.
- Mengetahui bagaimana perubahan input dari latent space mempengaruhi gambar yang dihasilkan.

### Dataset yang dipakai 📊
Proyek ini memanfaatkan **Anime Face dataset** yang tersedia di Kaggle, dengan total 20.000 gambar karakter anime. Gambar-gambar ini digunakan untuk melatih model GAN agar Generator dapat menghasilkan karakter anime yang lebih realistis.

## Langkah Instalasi 🛠️

1. **Clone repositori**  
   Clone repositori ini ke komputer Anda.

2. **Install dependensi**  
   Install library yang diperlukan menggunakan `pip` seperti TensorFlow, Keras, NumPy, Matplotlib, Seaborn, Scikit-learn, dan Pandas.

3. **Latih model**  
   Jalankan skrip pelatihan untuk melatih DCGAN pada dataset.

4. **Hasilkan wajah anime baru**  
   Setelah model dilatih, Anda dapat menggunakannya untuk menghasilkan wajah anime baru berdasarkan input noise acak.


## Libraries yang digunakan 💻

- **pandas** untuk mengelola data.
- **numpy** untuk operasi matematika.
- **sklearn** untuk pembelajaran mesin dan fungsi terkait - machine-learning-pipeline.
- **seaborn** untuk memvisualisasikan data.
- **matplotlib** untuk alat plotting tambahan.
- **keras** untuk memuat kumpulan data.
- **tensorflow** untuk pembelajaran mesin dan fungsi terkait jaringan saraf.

## Analisis Teknologi yang Digunakan 🔍

### 1. **TensorFlow & Keras**: 
- Memudahkan implementasi arsitektur kompleks seperti DCGAN karena mereka mendukung lapisan konvolusi dan dekonvolusi yang dioptimalkan untuk pemrosesan gambar.

### 2. **Pandas**:
- Memudahkan manipulasi data tabular dengan sintaks yang sederhana. Ideal untuk pengolahan data sebelum pelatihan model.

### 3. **Numpy**:
- Menyediakan dukungan untuk array multidimensi dan operasi matematis yang efisien. Sangat penting dalam komputasi numerik.

### 4. **Scikit-learn**:
- Menyediakan berbagai algoritma pembelajaran mesin dan alat untuk preprocessing data. Sangat mudah digunakan untuk pemula.

### 5. **Seaborn dan Matplotlib**:
- Memungkinkan visualisasi data yang menarik dan informatif, membantu dalam analisis hasil.

### 6. **Convolutional Neural Networks (CNN)**:
- DCGANs didasarkan pada CNN, yang sangat baik untuk memproses data gambar. Lapisan konvolusi membantu model memahami hierarki spasial dalam gambar.

### 7. **GANs dan DCGANs**:
- GANs adalah jenis model generatif yang kuat yang dapat belajar untuk menghasilkan data realistis. DCGANs menggunakan lapisan konvolusi yang membuatnya sangat efektif untuk menghasilkan gambar.


## Kesimpulan ✨
Proyek ini menunjukkan bagaimana DCGANs dapat digunakan untuk menghasilkan karakter anime unik secara otomatis. Penggunaan teknologi dalam proyek DCGAN untuk menghasilkan karakter anime menunjukkan kombinasi yang baik antara kemudahan penggunaan dan kekuatan komputasi. Keras dan TensorFlow, dalam hal ini, memberikan platform yang kuat untuk membangun dan melatih model generatif, sementara Pandas dan NumPy memudahkan pengelolaan dan analisis data.
