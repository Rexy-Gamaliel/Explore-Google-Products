# Explore-Google-Products
##### Let's take a look at one of the powerful tools in our Google Product list: [TensorFlow](https://www.tensorflow.org/)

__*TensorFlow*__ adalah sebuah computional framework untuk membuat Machine Learning (ML) model.
  Dengan menggunakan framework hasil buatan Google Brain ini, komputasi untuk Machine Learning menjadi lebih **cepat dan mudah**, mulai dari memperoleh data, melatih model, membuat prediksi, dan meningkatkan kualitas hasil yang didapat.
TensorFlow menggabungkan berbagai model-model dan algoritma machine learning dan deep learning (neural networks) sehingga menjadi lebih mudah digunakan
Framework ini menggunakan bahasa **Python** sebagai front-end API, sementara mengeksekusi aplikasi dengan **C++** sehingga performanya lebih baik.
  Berbagai model yang dapat kita latih dan jalankan misalnya mengenali digit hasil tulis tangan, image recognition, natural language processing, simulasi berbasis persamaan diferensial parsial, dll.

![TensorFlow Logo](https://www.gstatic.com/devrel-devsite/prod/vfe8af62599ec445552c3fb43608c37ff46463c9fce3b14d8ee63b2e71edddffd/tensorflow/images/logo.png)

### How TensorFlow works
  TensorFlow memungkinkan pengguna untuk membuat dataflow graph, yakni struktur yang mendeskripsikan bagaimana data diproses melalui graph atau runtutan processing node.
Setiap node merepresentasikan operasi matematika, dan setiap garis yang menghubungkan node merupakan array multidimensi/tensor
  Dalam implementasinya dengan bahasa Python, node dan tensor merupakan object, dan aplikasi yang dibuat dari TensorFlow merupakan aplikasi Python itu sendiri.
Operasi matematikanya itu sendiri tidak dilakukan dalam bahasa Python, melainkan binaries C++ yang lebih high-performant.
Python sebagai bahasa pemrograman tingkat tinggi menyediakan abstraksi sehingga lebih user-friendly
Aplikasi-aplikasi yang dibuat TensorFlow dapat dijalankan di banyak tempat: local machine, cloud, Android dan iOS, CPU atau GPU.

### Benefits of using TensorFlow
  Keuntungan terbesar dari menggunakan TensorFlow adalah **abstaksi**. TensorFlow menyediakan berbagai toolkit yang memungkinkan penggunanya membuat model pada tingkat abstraksi yang dikehendaki.
  Misal, kita dapat menggunakan API dengan tingkat lebih rendah untuk membuat model dengan menentukan serangkaian operasi matematis. Sebagai alternatif, kita dapat menggunakan API dengan tingkat yang lebih tinggi untuk menentukan arsitektur yang telah ditetapkan, seperti regresi linear atau neural network.
  Intinya adalah, daripada kita harus berurusan dengan detail dari algoritma yang diimplementasikan, atau bingung bagaimana menggunakan hasil suatu fungsi untuk digunakan fungsi lainnya, developer cukup fokus pada logika umum dari aplikasi yang dibuatnya. Detail lainnya ditangani TensorFlow di belakang layar.
  TensorFlow juga menawarkan kemudahan dalam debugging dan mengintrospeksi aplikasi yang dibuat. Mode eager execution memungkinkan kita mengevaluasi serta memodifikasi setiap operasi graph secara terpisah dan transparan, dibandingkan membangun keseluruhan graph yang mengawang-awang lalu mengevaluasinya sekaligus. TensorBoard juga menyediakan visualisasi melalui dashboard web yang interaktif.
