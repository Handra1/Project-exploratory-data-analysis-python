# Project-exploratory-data-analysis-python
This project about learning exploratory data analysis in python (In Indonesia)

Exploratory Data Analysis: membahas tentang eksplorasi analisis data untuk mengidentifikasi data yang diperlukan dari file data2.csv.
Dasar analisis yang ada pada umumnya yaitu menghitung nilai dari sebuah data tersebut, atau biasa disebut dengan istilah count. Kita bisa memanfaatkan method info() untuk mendapatkan tipe data dari masing - masing kolom.
Tipe Data Setiap Kolom:
Disini kita akan menghitung frekuensi untuk non-numerik kolom: country, continent, fertility dan population dengan menggunakan method value_counts().
Frequency counts: Continent:
Untuk menghitung jumlah frekuensi, pertama kita pilih nama kolom yang akan kita hitung. Jika nama kolom tidak memiliki spesial karakter seperti spasi dan nama fungsi di Python, maka kita dapat menuliskan langsung dengan dot notation. Kemudian kita gunakan method value_counts() berdasarkan kolom yang dipilih.
Menuliskan parameter dropna=False untuk menghitung jumlah data apabila ada data yang hilang. Output yang ditampilkan akan berdasarkan alfabetik secara descending.
Kita juga bisa menggunakan subsetting bracket notation. 
Frequency counts: Country akan menghitung jumlah frekuensi untuk kolom Country. Karena terlalu banyak nama Negara yang ada di data tersebut, maka disini saya hanya akan menghitung top 5 saja. 
Frequency counts: fertility, data yang ada pada kolom fertility disimpan dalam bentuk string. Itulah kenapa kolom ini memiliki tipe data yang salah.
Frequency counts: population, untuk kasus di kolom population dimana terdapat nilai yang hilang, kita masih bisa untuk menghitung total nilainya dengan parameter dropna=False.
Summary Statistic: selain menghitung total frekuensi untuk masing - masing kolom, kita juga bisa menghitung kalkulasi statistik untuk kolom numerik. Sehingga kita bisa mendapatkan outliers di data tersebut. Outliers adalah nilai yang jauh lebih tinggi (atau lebih rendah) daripada data lainnya. Kita bisa menggunakan method describe() untuk menghitung summary statistic. Hanya kolom yang memiliki tipe data numerik yang akan dihitung dan ditampilkan. Kita akan mendapatkan nilai count, mean, standard deviation, minimum, maximum, 25, 50 dan 75 percent quartiles data yang dimana 50% quartile adalah median.
