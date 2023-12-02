# E-Commerce-Churn-Prediction
Classification Model for Churn Prediction

# Analisis Data E-Commerce menggunakan Python

## Latar Belakang

Perusahaan e-commerce pada dataset ini memiliki tingkat persentase churn sebesar 16,8%. _Customer churn_ adalah salah satu hal yang perlu dicegah oleh bisnis karena biaya mempertahankan _customer_ lebih murah dibandingkan menarik _customer_ baru (Reichheld & Sasser, 1990). Berdasarkan data dari Chargebee Blog (2022) dan Recurly Research (2022) yang menunjukkan kisaran _churn rate_ yang baik untuk perusahaan _e-commerce_ sekitar 5%-10%. Maka dari itu dibutuhkan sistem yang mampu mengetahui customer mana yang memiliki kemungkinan churn lalu dilakukan _treatment_ lebih lanjut agar customer itu tidak benar-benar churn

## Objektif

Objektif utama proyek ini adalah untuk membuat sistem yang mampu mengetahui customer yang memiliki kemungkinan churn, mengidentifikasi penyebab churn, dan memberi saran agar customer tersebut tidak benar-benar churn

## Pertanyaan Riset

1. Model Machine Learning apa yang terbaik untuk memprediksi customer churn pada dasaset ini?

2. Faktor apa saja yang membuat customer akan churn?

3. Saran apa yang terbaik agar customer tidak benar-benar churn?

## Data dan Asumsi

Dataset yang digunakan dapat diunduh dari [sumber dataset](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction). Asumsi pada penelitian ini adalah saya HANYA mengolah dataset saja, perihal apakah dataset valid atau tidak, saya tidak bisa menjamin karena tidak ada kejelasan apakah data tersebut memang benar punya salah satu E-Commerce, dan tidak diketahui dari E-Commerce negara mana

## Analisis Data

Pada proyek ini, digunakan beberapa library Python seperti Pandas, NumPy, dan Matplotlib untuk melakukan analisis data. File `E-Commerce Churn Prediction.ipynb` menyajikan langkah-langkah analisis secara rinci. Namun disini saya hanya akan menampilkan hasil analisis data sesuai dengan pertanyaan riset yang sudah dibuat dan untuk tahapan analisis bisa dilihat di file `E-Commerce Churn Prediction.ipynb`

1. Hasil Pemodelan Machine Learning dengan masing-masing metric
![Logo Project](https://drive.google.com/file/d/1Y5y9Xa8-QSeAy5VuctmhK4L1YWmJRrAP/view?usp=drive_link)

2. Feature Importance
![Logo Project](https://drive.google.com/file/d/1D1KyPjjVRCFAjQCQN5wWtfDgxLomwikl/view?usp=sharing)

## Simpulan

Hasil analisis menunjukkan bahwa model yang terbaik adalah XGBoost dengan metric nya F2 score, dan dari feature importance dapat diketahui bahwa terdapat 2 fitur yang memiliki nilai yang tertinggi yaitu tenure dan complain. Untuk yang XGBoost sudah dilakukan Hyperparameter Tuning dan hasilnya tidak terlalu berbeda dari sebelum di Hyperparamter Tuning. Dan untuk saran bisnis akan didasari dari 2 fitur tertinggi Feature Importance

## Saran

Berdasarkan hasil analisis, beberapa saran yang dapat dipertimbangkan oleh pemilik bisnis E-Commerce adalah:

1. Start Membership Program

Perusahaan dapat memperpanjang Tenure dengan membuat Program Membership. Dengan Perusahaan membuat Program Membership maka Customer akan mendapatkan manfaat lebih banyak dengan membayar uang terlebih dahulu. Hal ini dilakukan agar Customer melakukan pembelian lebih sering karena sudah ikut program membership.

Menurut McKinsey "62% konsumen lebih cenderung membelanjakan lebih banyak uang setelah berlangganan program loyalitas berbayar", dan Menurut LoyaltyOne "64% anggota program bersedia membayar jika mereka menerima manfaat yang lebih baik seperti pengiriman gratis. Persentase ini bahkan meningkat jadi 70% untuk generasi millennial".

2. Start Reward Program

Perusahaan dapat memperpanjang Tenure dengan membuat Program Reward. Dengan Program Reward maka Customer akan merasa dihargai sehingga Customer akan bertahan lebih lama di Platform E-Commerce yang artinya adalah Tenurenya akan bertambah.

Dalam sebuah Laporan yang diterbitkan oleh WireCard yang berjudul The Wirecard 2019 Consumer Incentives report, dikutip bahwa: "For over half of respondents, rewards rated as extremely or very important for both big-ticket and small, habitual purchases", Selain itu juga ditulis "Over 92% of customers agree that rewards influence their purchase decision", dan lebih mengejutkannya lagi "75% of customers said they were likely to make another purchase after receiving an incentive".

3. Start Chatbot

Perusahaan dapat membuat Chatbot agar Customer segera mendapatkan jawaban dari pertanyaannya. Chatbot sendiri dapat beroperasi 24 jam tanpa henti sehingga akan meningkatkan Kenyamanan Customer. Chatbot juga bisa terhubung dengan Customer Service sehingga Customer tetap bisa mendapatkan jawaban yang lebih lengkap dari permasalahan yang dialami Customer.

Dari Artikel yang diterbitkan oleh Qontak, dikutip bahwa “Penjualan akan meningkat secara otomatis karena terciptanya kepuasan pelanggan serta hubungan yang baik dengan pelanggan. Chatbot tidak hanya dapat menjawab pertanyaan pelanggan, namun dapat dimanfaatkan untuk menawarkan katalog produk pada bisnis Anda menggunakan fitur robot marketing.”
