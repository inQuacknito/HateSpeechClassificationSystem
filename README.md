# KLASIFIKASI TEKS TWITTER YANG MENGANDUNG PERKATAAN MENYINGGUNG DAN UJARAN KEBENCIAN MENGGUNAKAN ALGORITMA KNN

Oleh :
- Muhammad Dwiki Ramdhani - G64180032
- Mohammad Thareeq Izzulhaq - G64180041
- Muhammad Rayhan Adyatma - G64180064

## Latar belakang

- Seiring berkembangnya teknologi, terutama internet yang berkembang dengan sangat cepat, semakin banyak juga orang yang menggunakan media sosial.
- Media sosial yang berada di sekitar kita memberikan kebebasan untuk menyampaikan perasaan maupun pendapat secara tertulis. Media sosial juga menjadikan dunia seperti tidak memiliki perbatasan, informasi beredar secara cepat dalam hitungan detik.
- Twitter adalah salah satu media sosial yang banyak dipakai oleh masyarakat indonesia.
- Tak jarang kasus Cyberbullying terjadi yang berasal dari Twitter yang dimulai dari tweet hate speech.


## Ruang lingkup

- Bahasa pemrograman: Python 3.6
- Tools: Google colab, Kaggle
- Social Media: Twitter        

## Metodologi

### K-Nearest Neighbors (K-NN)
metode yang menggunakan algoritma supervised learning dimana hasil dari data yang baru diklasifikasikan berdasarkan mayoritas dari kategori k-tetangga terdekat.

### Term Frequency - Inverse Document Frequency (TF-IDF)
metode pengukuran statistik yang mengevaluasi keberadaan kata pada dokumen yang terkumpul di antara kumpulan dokumen lainnya.

### Euclidean Distance
perhitungan jarak dari 2 buah titik dalam Euclidean space.<br>
<img alt="Rumus Euclidean" src="https://github.com/inQuacknito/HateSpeechClassificationSystem/blob/master/images/euclidean_distance.svg">

## Hasil dan Pembahasan

Dari model yang dibuat didapatkan skor sebagai berikut:
- Precision: 84% 
- F1: 80%
- Recall: 76% 

## Pengujian Sistem

| Input | Output |
|-------|--------|
| Saya benci presiden tevyat karena dia terlalu thampfan | Tweet merupakan Ujaran kebencian |
| Lukisan milik USER lumayan, menurut gw lebih bagus lagi kalo warnanya lebih bervariasi | Tweet bukan merupakan Ujaran kebencian dan tidak mengandung kata kasar |
| Dasar cewek matre kapok gue jalan sama lo | Tweet mengandung kata kasar |
| Kenapa sih USER kurang bersyukur banget! Udah dikasih mobil malah minta pesawat jet, dasar manusia tidak bersyukur | Tweet merupakan Ujaran kebencian dan mengandung kata kasar|

## Kesimpulan dan Saran
Klasifikasi tweet pada twitter cukup membantu untuk mengidentifikasi tweet yang mengandung ujaran kebencian dan perkataan menyinggung.
<br><br>
Saran : Diperlukan pengolahan dengan metode lain dan tahap preprocessing yang lebih rinci lagi agar hasil lebih akurat.


## Akses sistem
sistem klasifikasi dapat diakses pada link berikut:<br>
https://colab.research.google.com/drive/1JuCS5QDJx8m73kWHUXqtcVSExd4GJCBi?usp=sharing
