# Description
<div align="justify">
Repository ini berisi kode yang digunakan untuk menganalisis dataset "Impact of Covid-19 Pandemic on the Global Economy". Tujuan dari proyek ini adalah untuk melakukan preprocessing dan ETL pada data, melakukan analisis data menggunakan SparkSQL, DataFrames, atau Datasets, serta membuat visualisasi untuk memperlihatkan hasil analisis. Dataset ini berisi data tentang dampak pandemi Covid-19 pada ekonomi global. Data ini terdiri dari beberapa kolom seperti tanggal, lokasi, gdp_per_capita, kasus covid-19, kematian covid-19, dll. Proyek ini terdiri dari beberapa tahap. Tahap pertama adalah melakukan preprocessing dan ETL pada data. Pada tahap ini, data akan dibersihkan, duplikat akan dihapus, dan kolom baru seperti tahun akan ditambahkan. Selanjutnya, data akan diolah menggunakan SparkSQL, DataFrames, atau Datasets untuk menjawab beberapa pertanyaan terkait dampak pandemi pada ekonomi global. Tahap selanjutnya adalah membuat visualisasi. Pada tahap ini, data yang sudah diolah akan divisualisasikan menggunakan plotly API. Beberapa jenis visualisasi yang akan dibuat antara lain grafik batang dan grafik garis. Proyek ini diharapkan dapat memberikan pemahaman lebih dalam tentang dampak pandemi Covid-19 pada ekonomi global dan juga memberikan pengalaman dalam menggunakan SparkSQL, DataFrames, atau Datasets untuk menganalisis data besar.
</div>

# Dataset
![Dataset](dataset.png)
Dataset bisa di download<a href="https://www.kaggle.com/datasets/shashwatwork/impact-of-covid19-pandemic-on-the-global-economy"> disini</a>.
<div align="justify">
Dataset "Impact of Covid-19 Pandemic on the Global Economy" adalah kumpulan data yang berisi informasi tentang dampak pandemi Covid-19 terhadap perekonomian global. Dataset ini memiliki 9 kolom yang mencakup informasi seperti kode ISO negara, lokasi, tanggal, jumlah kasus dan kematian Covid-19, indeks ketatnya kebijakan pencegahan Covid-19, jumlah penduduk, GDP per kapita, dan Indeks Pembangunan Manusia. Dataset ini dapat digunakan untuk menganalisis dampak pandemi Covid-19 terhadap perekonomian global dan membandingkan tingkat GDP per kapita antara negara yang terpengaruh pandemi dan tidak terpengaruh pandemi serta melihat korelasi antara kebijakan pencegahan Covid-19 dengan jumlah kasus Covid-19 dan kematian di suatu wilayah atau negara tertentu.
</div>

# Flowchart
![Dataset](flowchart.png)
<div align="justify">
Flowchart preprocessing data pada dataset "Impact of Covid-19 Pandemic on the Global Economy" dimulai dengan memuat data dari file yang tersedia. Proses pertama yang dilakukan adalah menghilangkan kolom yang tidak memiliki header, yang kemudian dilanjutkan dengan menghilangkan baris yang memiliki nilai null atau kosong.Setelah itu, data akan disortir berdasarkan waktu dan lokasi, dan kemudian dilakukan reset index untuk mengembalikan index yang diurutkan. Setelah proses ini selesai, pengguna akan dihadapkan pada sebuah decision point, yaitu apakah akan dilakukan proses ETL atau tidak. Jika pengguna memilih untuk melakukan proses ETL, maka langkah selanjutnya adalah mengambil kolom yang diperlukan untuk analisis dan menghitung rata-rata setiap tahun dari setiap negara selama pandemi Covid-19. Setelah itu, dilakukan visualisasi data untuk memudahkan pemahaman. Namun, jika pengguna memilih untuk tidak melakukan proses ETL, maka proses preprocessing data selesai dan data siap digunakan untuk analisis lebih lanjut.
</div>

### Contoh Kode JavaScript

```javascript
function greeting(name) {
  console.log(`Hello, ${name}!`);
}

greeting("World");
