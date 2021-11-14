# Submission-Dicoding-Machine-Learning-Pemula

Data sudah menjadi komoditi yang laku untuk diperjual-belikan. Sangat penting untuk mengetahui bagaimana data dapat diproses karena dengan pemrosesan data inilah suatu data yang banyak dapat dijadikan sebagai informasi yang bernilai tinggi. Salah satu pekerjaan yang berhubungan dengan pemrosesan data ini adalah Machine Learning Developer yang memiliki pengetahuan untuk menggunakan pembelajaran mesin untuk mengenali pattern yang tersembunyi di antara banyak data dan bagaimana menggunakannya. Sebagai contoh, 75% dari pengguna Netflix memilih film berdasarkan rekomendasi algoritma machine learning aplikasi tersebut.

1. Machine Learning dapat digunakan untuk meningkatkan efisiensi dari berbagai pekerjaan.
2. Machine Learning dapat diimplementasikan ke berbagai industri dan berbagai jenis data sehingga kegunaannya sangat luas.
3. Banyak perusahaan memiliki jumlah data yang sangat besar sehingga perlu diproses dengan machine learning untuk mendapatkan informasi yang berarti.
4. Kebutuhan karier di bidang Machine Learning sangatlah tinggi dan jumlah praktisinya juga masih sedikit sehingga peluangnya masih sangat besar.
5. Pemahaman tentang machine learning adalah keharusan untuk menjadi seorang Machine Learning Developer ataupun Data Scientist.

Silabus
Pengenalan Data : Pengenalan ke machine learning dan teknik-teknik untuk pengolahan data, seperti data collecting, data cleaning, dan data processing. (7 jam 30 menit)
Supervised dan Unsupervised Learning : Memahami 2 jenis machine learning yaitu supervised dan unsupervised learning, dengan contoh model regresi linear dan decision tree. (4 jam 35 menit)
Support Vector Machine (SVM) : Menjelaskan tentang SVM, salah satu model machine learning yang populer. Di sini juga akan belajar tentang clustering dengan k-means. (2 jam 35 menit)
Dasar-Dasar Machine Learning : Menjelaskan tentang alur kerja (workflow) dari suatu proyek machine learning, dan juga menjelaskan overfitting, underfitting, dan model selection. (2 jam 40 menit)
Neural Network : Belajar mengenal dasar dari neural network. Akan diterangkan mengenai multi layer perceptron serta convolutional neural network dalam image classification. (2 jam 5 menit)
TensorFlow : Belajar tentang library TensorFlow, sebuah powerful library yang dipakai untuk mengembangkan project machine learning. (4 jam 5 menit)

Proyek Akhir : Klasifikasi Gambar
Selamat, Anda telah berada di akhir pembelajaran dalam akademi ini. Anda sudah mempelajari dasar-dasar machine learning dan bagaimana jaringan saraf bekerja. Untuk bisa lulus dari akademi ini, Anda harus mengirimkan submission berupa program jaringan saraf tiruan menggunakan TensorFlow. Program Anda harus mampu mengenali bentuk tangan yang membentuk gunting, batu, atau kertas.



Kriteria Submission
Berikut kriteria submission yang harus Anda penuhi:

Dataset yang dipakai haruslah dataset berikut : rockpaperscissors, atau gunakan link ini pada wget command: https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip.
Dataset harus dibagi menjadi train set dan validation set.
Ukuran validation set harus 40% dari total dataset (data training memiliki 1314 sampel, dan data validasi sebanyak 874 sampel).
Harus mengimplementasikan augmentasi gambar.
Menggunakan image data generator.
Model harus menggunakan model sequential.
Pelatihan model tidak melebihi waktu 30 menit.
Program dikerjakan pada Google Colaboratory.
Akurasi dari model minimal 85%.
Dapat memprediksi gambar yang diunggah ke Colab seperti gambar di bawah.
202004302318257ec23b834046174a7d426680e488905e.png
Manambahkan data diri (sesuai profil Dicoding) pada submission/project yang dikirimkan.


Saran Submission
Submission Anda akan dinilai oleh reviewer dengan penilaian bintang berskala 1-5 berdasarkan dari parameter yang ada.

Anda dapat menerapkan beberapa saran untuk mendapatkan nilai tinggi, berikut sarannya:

Akurasi dari model di atas 85%
Anda menggunakan lebih dari 1 hidden layer.
Menerapkan lebih banyak augmentasi gambar.
Anda menggunakan optimizer dan loss-function yang tidak diajarkan di kelas.
Detail penilaian submission:

Bintang 1 : Semua ketentuan terpenuhi, namun terindikasi melakukan plagiat.
Bintang 2 : Semua ketentuan terpenuhi, namun penulisan kode masih perlu diperbaiki.
Bintang 3 : Semua ketentuan terpenuhi namun hanya mengikuti seperti apa yang ada pada modul.
Bintang 4 : Semua ketentuan terpenuhi dan akurasi dari program di atas 95%.
Bintang 5 : Semua ketentuan terpenuhi, akurasi di atas 96%, dan menggunakan tiga atau lebih teknik yang tidak diajarkan di modul seperti penggunaan Callback.
Jika submission Anda ditolak maka tidak ada penilaian. Kriteria penilaian bintang di atas hanya berlaku jika submission Anda lulus.



Submission yang Tidak Sesuai Kriteria
Jika submission Anda tidak sesuai dengan kriteria, maka akan ditolak oleh reviewer, berikut poin-poinnya:

Akurasi dari model Anda di bawah 85%.
Proses pelatihan model Anda memakan waktu lebih dari 30 menit.
Tidak menambahkan data diri (sesuai profil Dicoding) pada submission/project yang dikirimkan.


Resources dan Tips
Berikut Tips yang dapat Anda terapkan untuk mempermudah Anda menyelesaikan submission:

Model merupakan klasifikasi multi kelas sehingga loss function yang digunakan bukan binary_crossentropy.
Pastikan Anda membagi direktori untuk image data generator sesuai dengan jumlah label.
Untuk export project yang Anda kerjakan di Colaboratory sebagai berkas .ipynb, klik tombol file yang berada di pojok kiri atas Colaboratory dan pilih download .ipynb.
20200501002401b773f40df397fb5aed15666f519e0e49.png

Forum Diskusi
Jika mengalami kesulitan, Anda bisa menanyakan langsung ke forum diskusi. https://www.dicoding.com/academies/184/discussions. 

Beberapa diskusi berikut ini dapat digunakan untuk membantu submission Anda: 

diskusi1,
diskusi2, atau
diskusi3.


Ketentuan Berkas Submission
Beberapa poin yang perlu diperhatikan ketika mengirimkan berkas submission:

Menggunakan bahasa pemrograman Python.
Dataset menggunakan data yang disediakan di resource.
Mengirimkan pekerjaan Anda dalam bentuk berkas .ipynb.
Program yang Anda kirim pastikan adalah berkas .ipynb yang sudah dieksekusi/dijalankan. Sederhananya, jalankan semua cell pada submission Anda. Ketika seluruh output telah keluar, baru simpan program anda dalam format .ipynb.


Ketentuan Proses Review
Beberapa hal yang perlu Anda ketahui mengenai proses review:

Tim penilai akan mengulas submission Anda dalam waktu selambatnya 3 (tiga) hari kerja, tidak termasuk hari sabtu, minggu dan libur nasional.
Tidak disarankan untuk melakukan submit berkali-kali karena akan memperlama proses penilaian yang dilakukan tim penilai.
Anda akan mendapat notifikasi hasil pengumpulan submission Anda via email, atau Anda dapat mengecek status submission pada akun Dicoding Anda.
