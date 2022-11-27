# Cross-Selling-Health-Insurance-Prediction
Final Project Rakamin Academy Data Science Bootcamp Batch 25. 

Persentase pelanggan Asuransi Kesehatan di Perusahaan Hello Sigma yang memiliki ketertarikan untuk membeli Asuransi Kendaraan masih sedikit. Saat ini user interested rate Asuransi Kendaraan adalah 12,3%. Hal tersebut membuat perusahaan ingin meningkatkan user interested rate Asuransi Kendaraan. Oleh karena itu ada beberapa hal yang perlu dilakukan terkait masalah tersebut, antara lain : 
- Memprediksi nasabah yang potensial untuk asuransi Kendaraan
- Menemukan faktor penting dan karakteristik utama dari user yang tertarik dengan asuransi kendaraan
- Menemukan metode apa yang membuat customer tertarik
- Meningkatkan jumlah orang yang tertarik dengan asuransi kendaraan
- Mengimplementasikan pada sebuah simulasi bisnis untuk melihat apakah model yang dibuat memberikan dampak yang positive untuk perusahaan Asuransi.


Setelah dilakukan pemrosesan pada data hingga mencari model yang relevan, didapatkan kesimpulan sebagai berikut : 

Business Insigth
- Pada nasabah yang tertarik menggunakan Asuransi Kendaraan, kondisi kendaraan sebelumnya lebih banyak yang telah mengalami kerusakan dibandingkan yang belum.
- Nasabah yang tertarik menggunakan Asuransi Kendaraan baik Male maupun Female tidak terdapat perbedaan yang signifikan.
- Pada kelompok usia kendaraan 1-2 tahun lebih banyak yang tertarik menggunakan asuransi Kendaraan dibandingkan kelompok lain seperti kelompok usia kendaraan <1 tahun dan usia kendaran >2 tahun
- Nasabah yang tertarik menggunakan Asuransi kendaraan, sebelumnya banyak yang belum menggunakan Asuransi Kendaraan.
- Ada 10 kode jenis Policy_Sales_Channel yang paling banyak dalam memberikan kontribusi ketertarikan nasabah menggunakan Asuransi Kendaraan.
- Usia Nasabah dari 33 – 52 merupakan kelompok umur yang paling banyak tertarik menggunakan Asuransi Kendaraan.
- Ada beberapa Region seperti Region California, New York, Texas, Florida dan Illonois, dimana wilayah tersebut nasabah yang tertarik menggunakan Asuransi Kendaraan lebih banyak dibandingkan Region lain.

Model 
- Model yang digunakan pada case ini adalah Regresi Logistic dan menggunakan Metric Recall 

Business Recommendation
- Perusahaan dapat memfokuskan pada nasabah yang sebelumnya belum memiliki Asuransi Kendaraan dan kondisi kendaraannya rusak
- Menggunakan top 10 jenis Policy_Sales_Channel sebagai media promosinya.
- Perusahaan dapat memfokuskan pada beberapa Region yang memiliki nasabah dengan ketertarikan Asuransi Kendaraan paling banyak dibandingkan Region lain.
- Memfokuskan promosi ke user dengan rentang umur 33-52 tahun dan pernah mengalami kerusakan pada kendaraannya serta umur kendaraannya berada pada 1-2 tahun.
