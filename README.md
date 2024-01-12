# Dicoding Belajar Pengembangan Machine Learning - Submission Proyek Kedua : Membuat Model Machine Learning dengan Data Time Series

## Deskripsi Proyek
Proyek ini merupakan submission kedua dari kelas Belajar Pengembangan Machine Learning yang diselenggarakan oleh Dicoding. Pada proyek ini, saya membuat model machine learning dengan data time series. Dataset yang digunakan adalah Hourly Energy Consumption data yang saya dapatkan dari [Kaggle](https://www.kaggle.com/robikscube/hourly-energy-consumption). Model yang saya buat adalah model LSTM (Long Short-Term Memory) dengan menggunakan framework TensorFlow.

## Dataset
Dataset yang digunakan adalah Hourly Energy Consumption data yang saya dapatkan dari [Kaggle](https://www.kaggle.com/robikscube/hourly-energy-consumption). Dataset ini berisi data konsumsi energi listrik PJM East Region dari tahun 2001 hingga 2018. Dataset ini memiliki 2 kolom yaitu Datetime dan PJME_MW. Kolom Datetime berisi tanggal dan waktu dalam format ISO 8601 sedangkan kolom PJM_Load_MW berisi konsumsi energi listrik dalam satuan megawatt.

## Model
Model yang saya buat adalah model LSTM (Long Short-Term Memory) dengan menggunakan framework TensorFlow. Model ini saya buat dengan menggunakan 2 buah layer LSTM dan 2 buah layer Dense. Layer LSTM pertama saya buat dengan 64 unit sedangkan layer LSTM kedua saya buat dengan 64 unit. Layer Dense saya buat dengan 30 unit, 10 unit, dan 1 unit. Layer Dense pertama dan kedua saya beri fungsi aktivasi relu sedangkan layer Dense ketiga saya tidak beri fungsi aktivasi. Layer Dropout saya beri nilai 0.2. Model ini saya compile dengan optimizer adam dan loss function mean squared error. Model ini saya latih dengan 100 epochs dan batch size 32. Model ini saya latih dengan data training sebanyak 80% dan data validasi sebanyak 20%.
