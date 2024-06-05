# TUGAS PENGKODEAAN DAN PEMROGRAMAN 
NAMA   : MUHAMMAD SOLEHUDIN

KELAS  : PEMROGRAMAN DAN PENGKODEAN / D

NIM    : 12030122130144

# BERIKUT ADALAH CARA MENJALANKAN  KODE PYTHON  YANG TERHUBUNG KE FILE JENIS CSV
1. masukan buka visual code dan tambhakan extension python pada visual code
2. domload library python yang dibutuhkan yang terdiri dari
   
   a. pandas
   
   b. matplotlib
   
   c. kmeans
   
   d. seaborn
   
3. buat tabel csv untuk kebutuhan pengkodiangan , berikan nama file data.csv
4. open folder tempat  kode python yang akan di jalankan  pada visual code
5. jalankan kode yang tertera di atas
6. langkah akhir jalankan terminal untuk menghasilkan output yang tertampil di bawah ini, yang terdiri dari
   
   a. histogram
   
   b. bar chart
   
   c. cluster
   
   d. box plot 


#berikut hasil dari kode python yang di jalankan 

## histogram 
1. soal Histogram Usia: Buatlah histogram untuk menunjukkan distribusi usia.
   
Fungsi: Menampilkan distribusi data usia dalam bentuk grafik batang

Interpretasi Grafik: Distribusi Usia
Grafik yang ditampilkan adalah histogram untuk kolom 'Usia'. Berikut adalah interpretasi dari grafik tersebut:

Sumbu X (Horizontal): Menunjukkan rentang usia (Usia).
Sumbu Y (Vertikal): Menunjukkan frekuensi atau jumlah kejadian untuk setiap rentang usia.
Histogram (Bar): Menunjukkan berapa banyak data (frekuensi) yang berada dalam rentang usia tertentu.
Pengamatan dari Grafik:

Rentang usia yang paling sering muncul adalah sekitar 25, 30, dan 40 tahun dengan frekuensi tertinggi (2).
Rentang usia 35 dan 50 tahun memiliki frekuensi yang lebih rendah dibandingkan dengan rentang usia lainnya (1).
Rentang usia 45 tahun memiliki frekuensi yang paling rendah (0).
Ini memberikan gambaran bahwa distribusi usia dalam dataset memiliki beberapa puncak pada usia 25, 30, dan 40 tahun. Frekuensi usia menurun pada rentang usia 35, 45, dan 50 tahun. Hal ini menunjukkan variasi dalam distribusi usia tanpa pola distribusi yang halus, sehingga puncak frekuensi lebih terlihat jelas pada usia tertentu.


![Cuplikan layar 2024-06-05 071252](https://github.com/muhammadsolehudin3123/muhammad-solehudin_pengkodean-/assets/152485242/d6ca6882-37d9-4b25-999e-8efb10185f08)

## bar chart
2. soal Bar Chart Kota: Buatlah bar chart untuk menunjukkan jumlah individu di setiap kota.
   
Fungsi: Menampilkan jumlah orang yang tinggal di setiap kota dalam bentuk grafik batang.

Interpretasi Grafik: Jumlah Orang per Kota
Grafik yang ditampilkan adalah bar chart untuk kolom 'Jumlah Orang' per kota. Berikut adalah interpretasi dari grafik tersebut:

Sumbu X (Horizontal): Menunjukkan nama-nama kota.
Sumbu Y (Vertikal): Menunjukkan jumlah orang di setiap kota.
Bar (Batang): Menunjukkan berapa banyak orang yang berada di setiap kota.
Pengamatan dari Grafik:

Jumlah orang di setiap kota adalah sama, yaitu 1 orang per kota.
Kota-kota yang ditampilkan mencakup New York, Los Angeles, Chicago, Houston, Phoenix, Philadelphia, San Antonio, San Diego, Dallas, San Jose, Austin, Jacksonville, Fort Worth, dan Columbus.
Warna bar berbeda-beda untuk setiap kota, memberikan visualisasi yang lebih menarik dan mudah untuk membedakan kota-kota tersebut.
Ini memberikan gambaran bahwa dalam dataset ini, setiap kota memiliki jumlah orang yang sama, yaitu satu orang per kota. Hal ini menunjukkan distribusi yang merata tanpa adanya kota yang lebih dominan dalam jumlah orang.


![Cuplikan layar 2024-06-05 071311](https://github.com/muhammadsolehudin3123/muhammad-solehudin_pengkodean-/assets/152485242/8083e266-76fb-4c4d-8885-19051aadcc9c)

## cluster 
3. soal Cluster Berdasarkan Usia: Lakukan clustering pada data berdasarkan usia dan visualisasikan hasil clustering tersebut.
   
Fungsi: Mengelompokkan data berdasarkan usia menggunakan algoritma KMeans.

Interpretasi Grafik: Kluster Usia
Grafik yang ditampilkan adalah scatter plot yang menunjukkan kluster-kluster usia. Berikut adalah interpretasi dari grafik tersebut:

Sumbu X (Horizontal): Menunjukkan rentang usia (Usia).
Sumbu Y (Vertikal): Menunjukkan kluster yang berbeda (Kluster).
Titik (Scatter): Menunjukkan data individu yang dikategorikan ke dalam kluster-kluster tertentu berdasarkan usia.
Pengamatan dari Grafik:

Kluster 0 (Merah): Titik-titik kluster 0 berkisar pada usia 25 hingga 34 tahun, dengan sebagian besar data terkonsentrasi pada rentang usia ini. Semua titik berada pada posisi vertikal 0.
Kluster 1 (Hijau): Titik-titik kluster 1 berada pada usia 45 dan 50 tahun. Semua titik berada pada posisi vertikal 1.
Kluster 2 (Biru): Titik-titik kluster 2 berkisar pada usia 38 hingga 40 tahun, dengan data terkonsentrasi pada rentang usia ini. Semua titik berada pada posisi vertikal 2.
Ini memberikan gambaran bahwa data usia dalam dataset terbagi menjadi tiga kluster yang berbeda:

Kluster 0: Mengelompokkan individu yang berusia antara 25 hingga 34 tahun.
Kluster 1: Mengelompokkan individu yang berusia 45 dan 50 tahun.
Kluster 2: Mengelompokkan individu yang berusia antara 38 hingga 40 tahun.
Dengan melihat grafik ini, kita dapat memahami bagaimana usia dalam dataset dikelompokkan ke dalam kluster-kluster yang berbeda, yang dapat membantu dalam analisis lebih lanjut atau pengambilan keputusan yang berbasis pada usia.

![Cuplikan layar 2024-06-05 071323](https://github.com/muhammadsolehudin3123/muhammad-solehudin_pengkodean-/assets/152485242/ab316239-abd8-4578-8d92-1a5a8c4b0063)

## Box Plot (Usia)
4. soal Box Plot Usia: Buatlah box plot untuk menunjukkan distribusi usia.
   
Fungsi: Menampilkan ringkasan statistik usia dalam bentuk box plot

Interpretasi Grafik: Box Plot Usia
Grafik yang ditampilkan adalah box plot untuk kolom 'Usia'. Berikut adalah interpretasi dari grafik tersebut:

Sumbu X (Horizontal): Menunjukkan rentang usia (Usia).
Sumbu Y (Vertikal): Menunjukkan jumlah (dalam hal ini, grafik adalah univariat, sehingga semua data diplot pada posisi vertikal yang sama).
Pengamatan dari Grafik:

Box Plot (Kotak): Menunjukkan rentang interkuartil (IQR), yaitu dari kuartil pertama (Q1) hingga kuartil ketiga (Q3). Ini mencakup 50% data tengah.
Rentang IQR untuk usia berkisar antara sekitar 28 hingga 40 tahun.
Garis Tengah (Median): Garis di dalam kotak menunjukkan median usia, yaitu sekitar 33 tahun.
Whiskers (Garis Horizontal): Menunjukkan rentang data di luar IQR yang masih dianggap sebagai data yang tidak anomali.
Whiskers menunjukkan rentang usia dari sekitar 24 hingga 50 tahun.
Outliers: Tidak ada titik outlier yang ditampilkan pada grafik ini, yang berarti semua data berada dalam rentang whiskers.
Ini memberikan gambaran bahwa distribusi usia dalam dataset memiliki median di sekitar 33 tahun, dengan rentang interkuartil dari sekitar 28 hingga 40 tahun. Rentang usia secara keseluruhan adalah dari sekitar 24 hingga 50 tahun. Box plot ini membantu kita memahami sebaran dan konsentrasi data usia dalam dataset, dengan menunjukkan di mana sebagian besar data berada dan seberapa jauh sebarannya.


![Cuplikan layar 2024-06-05 071334](https://github.com/muhammadsolehudin3123/muhammad-solehudin_pengkodean-/assets/152485242/0144cf15-a7ce-4206-9381-af48e4a91312)
