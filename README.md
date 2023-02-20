# HOTEL BOOKING CANCELLATION PREDICTION
Pada dasarnya sebuah bisnis hotel adalah pengelolaan dan pemanfaatan sebuah bangunan atau area sebagai sebuah tempat tinggal sementara waktu dengan tujuan untuk mendapatkan keuntungan secara finansial. Oleh karena itu, pemanfaatan kamar yang tersedia secara efektif dan optimal menjadi salah satu hal yang perlu diperhatikan untuk memaksimalkan keuntungan. Selain itu, sebuah bisnis hotel didasari oleh pemberian pelayanan yang terbaik untuk menciptakan kenyamanan dan pengalaman yang baik untuk seluruh konsumennya, sehingga *brand image* merupakan hal yang sangat penting.
## Problem Statement
Saat ini teknologi telah memudahkan para calon konsumen hotel untuk mencari dan melakukan pemesanan kamar hotel, khususnya dengan adanya layanan *online*. Namun, selain keuntungan yang diberikan, hal ini pun berimbas meningkatnya tingkat pembatalan pemesanan kamar hotel, sehingga menyebabkan hotel tidak dapat mengoptimalisasi ketersediaan kamar hotel dan terbuangnya beberapa persediaan hotel yang sebagian besar bersifat tidak tahan lama. Hal tersebut memberikan efek negatif terhadap bisnis dan keuntungan.
## Goals
Berdasarkan permasalahan tersebut, dibutuhkan sebuah model prediktif yang dapat digunakan untuk memprediksi pembatalan pemesanan kamar hotel. Hal ini ditujukan untuk mengoptimalkan ketersediaan kamar, sehingga dapat memaksimalkan keuntungan.
# Conclusion and Recommendation
## Conclusion
* Berdasarkan hasil analisis yang dilakukan, model dengan performa terbaik adalah XGBoost Classifier dengan  *learning_rate* : 0.01, *max_depth* : 11, dan *n_estimators* : 500.
* `deposit_type_Non_refund`, `required_car_parking_spaces`, dan `market_segment_Online_TA` merupakan 3 *feature* yang memiliki nilai paling penting dalam melakukan prediksi.
* Model dapat memprediksi 85% calon tamu hotel yang tidak akan melakukan pembatalan dan memprediksi 73% calon tamu hotel yang akan melakukan pembatalan berdasarkan hasil *f1-score*.
## Recommendation
* Menambah *feature* lain yang dapat berhubungan dengan pembatalan, seperti waktu pemesanan hingga booking dan tanggal kedatangan.
* Menggunakan model *machine learning* lain, seperti CatBoot Classifier dan Light Gradient Boosting Classifier.
* Memperketat pilihan *non refundable deposit* dengan *no cancellation policy* untuk meyakinkan calon tamu hotel untuk tidak melakukan pembatala.
* Mengonfirmasi kembali kedatangan calon tamu, khususnya yang memiliki tipe *market segment online*, sehingga dapat memasarkan kembali kamar (apabila pembatalan dikonfirmasi) untuk mengoptimalkan ketersediaan kamar dan keuntungan. 
* Memberikan kemudahan untuk calon tamu melakukan permintaan seperti kebutuhan tempat parkir, karena dengan adanya permintaan, calon memiliki kemungkinan yang lebih tinggi untuk tidak melakukan pembatalan.
* Menggunakan model prediksi ini untuk mengoptimalkan ketersediaan kamar dan memaksimalkan keuntungan.
